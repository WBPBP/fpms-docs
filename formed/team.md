## 문서 개정 이력
|작성일|설명|담당자|
|:-:|:-:|:-:|
|2020.06.16|최초 작성.|송병준|
|2020.06.16|내용 추가.|송병준|

# 캡스톤디자인 개인별 수행 내역
## 프로젝트 명
Preshoes(프레슈)

## 제작학생명
|학번|이름|연락처|E-mail|
|:-:|:-:|:-:|:-:|
|201701562|송병준|010-****-2661|potados99@gmail.com|
|201701524|강은선|010-****-7047|dmstjs7047@hanmail.net|
|201501495|허설|010-****-6603|hseol96@naver.com|
|201701594|정재희|010-****-3018|wjfwogml5890@naver.com|

## 송병준

주로 아이디어의 실현 가능성을 검증하고 이를 직접 설계 및 구현하는 역할을 담당. 문서와 서류 작성 및 조교님/교수님 또는 외부 업체와의 컨택 또한 담당.

공식적으로는 안드로이드 모바일 애플리케이션 개발을 총괄하는 역할을 맡음. 이를 수행하기 위해 2학기를 마친 뒤부터 구글의 Material Degisn Guidline부터 Kotlin 예제 및 Clean Architecture 레퍼런스를 탐독하며 품질 좋고 재사용 가능하며 디버그가 용이한 소스 코드를 작성하는 능력을 배양함.

겨울방학 동안 QKSMS라는 오픈소스(GPLv3 라이센스 적용) 안드로이드 애플리케이션을 연구하며 적절하고 바람직한 실무 프로그래밍 기법을 익힘. 안드로이드 플랫폼은 물론 Clean Architecture를 적용한 REST API + Web frontend 구성의 Node.js 서비스를 직접 만들어 보며 HTTP 통신과 REST 프로그래밍 및 API 사용, 그리고 모바일 앱과 서버의 통합에 대한 이해도를 높임.

프로젝트 후반부에는 센서 모듈의 하드웨어와 소프트웨어를 전부 다시 제작하는 작업을 맡음. 기존 하드웨어를 담당하던 팀원이 임의로 설계를 바꾼 탓에 MCU의 analog입력 핀 갯수가 모자라 외장 블루투스 모듈을 사용함. UART 시리얼 통신과 Bluetooth 통신을 사용하여 보드가 센서로부터 수집한 데이터를 안전하게 모바일 애플리케이션으로 전달할 수 있는 기반을 마련함.

서버 및 블루투스 센서 모듈과의 통합을 위해 테스트 환경을 구축함. 이 과정에서 테스트 기반 개발(TDD) 방법론을 학습하고 실제로 프로젝트에 적용함. 중요 모듈마다 unit test를 진행하였고, 다른 부분에 영향 받지 않고 특정 컴포넌트의 동작을 테스트하기 위해 build variant별로 다른 동작을 수행하도록 의존성 주입(DI) 정의를 수정함.

프로젝트 전반에서 GitHub을 협업 툴로 활용하였으며, git을 포함한 버전 관리 시스템에 익숙하지 않은 팀원들에게 사용 방법을 안내함. 다른 팀원이 작성한 코드를 리뷰하고 테스트하며 버그를 찾아 내어 issue 또는 pull request로 보고함. 통합 테스트 진행중 서버나 모델에서 발생한 예상치 못한 프로그래밍 문제에 대해 몇 차례 해답을 제시함.

코드의 품질을 높여 잠재적인 버그의 가능성을 줄이고 정확한 문서화를 통해 소통의 비용을 줄이는 것에 상당한 노력을 기울임. 이미 작성한 코드도 다시 검토하며 refactoring을 꾸준히 진행함. 또한 프로젝트의 business rule과 같이 공식적인 내용은 GitHub에 마크다운 형식의 문서로 게재함으로써 소통에 있어 혼선이 없도록 하였음.

구현을 모두 마친 후 발표 자료 초안을 다듬고 내용을 추가하여 발표 영상을 녹화함. 최종 제출할 영상에 포함할 시연을 구상하고, 영상을 녹화한 다음 편집 및 자막 추가를 거쳐 IdeaBoom에 제출. 발표 시간이 부족하여 영상에 포함하지 못한 부분을 HTML로 작성하여 style을 입힌 뒤 IdeaBoom에 추가함.

## 강은선

신발에 부착될 하드웨어 완성품 및 API까지 제작하는 역할을 담당하였으나 실패함.

지난 2학기 종료 후, 전기 기초 이론과 C++, 아두이노 예제 코드를 통해 MCU 다루는 법을 학습하라는 팀장의 권유에도 불구하고 간단한 예제조차 스스로 만들지 못하였으며, 다른 팀원의 도움을 받아 LED를 켜는 코드를 간신히 작성하였음.

프로젝트의 다른 컴포넌트들(대표적으로 애플리케이션과 데이터 분석기)이 하드웨어로부터 수집한 데이터에 의존하기 때문에 하드웨어가 제일 먼저 완벽하게 완성되어야 하는 상황이었고, 시간이 5개월 넘게 주어졌으며, 팀원들이 밤샘을 불사하며 도움을 제공하였음에도 불구하고 아이디어를 검증할 프로토타입을 내놓는 데에 실패함.

프로젝트 기간 내내 책임감 없고 새로운 것을 배우는 것에 관심 없어하는 태도로 일관하며 일정을 지연시킴. 진행 도중 본래 역할에서 하차하고 발표 자료 제작을 맡았으나 프로젝트의 내용을 숙지하지 못하여 피상적인 내용만을 서술함. 후에 발표 영상 편집을 맡았으나 노트북 충전기가 고장났다는 이유로 영상 제출 당일 새벽에 일정을 지연시켰고, 결국 팀장이 완성함.

## 정재희

센서 모듈로부터 받은 샘플 데이터를 전처리하는 저수준 데이터 분석기와, 가공된 특징점으로부터 사용자에게 보여질 분석 결과를 도출하는 고수준 데이터 분석기의 구현을 담당.

방학 중에도 연구실에서 근무하며 시간이 날 때마다 족부 압력 분포를 다룬 논문을 수십 편 정독하며 센서 데이터 분석에 필요한 지식을 함양. Python과 데이터 분석 모델을 다루면서 이 프로젝트에서 필요로 하는 데이터 분석 컴포넌트를 구현할 수 있는 전문성을 확보함.

팀장이 제시한 과제를 가장 먼저 수행하였고, 다른 팀원의 구현에도 도움을 주는 등, 의욕적이고 성실한 모습을 보임. 공동으로 힘을 모아야 하는 일에 적극적으로 참여하였으며, 프로젝트 극초반에 팀 아이디어를 정하거나 프로젝트 후반에 센서 패널을 제작함에 있어 마감에 사용할 적절한 재료를 제시하는 등 공로가 큼.

졸업작품발표회 전날까지 질의응답에 대비하는 시간을 수 차례 가졌고, 맡은 부분에 대하여 훌륭하게 답변해내어 성실함과 전문성을 증명함.

## 허설

사용자 데이터를 저장하고 고수준 데이터 분석기를 host하는 API 서버 구현을 담당.

본격적인 구현을 시작하기 전에는 프로젝트에 필요한 기반 지식이 충분하지 않았으나 새로운 것을 배워보겠다는 의지와 적응력으로 레퍼런스와 예제로부터 빠르게 지식을 흡수함.

사용자의 계정 정보를 안전하게 보관해야 한다는 일념으로 일주일에 걸친 고민과 구상 끝에 데이터베이스에 저장되는 password column에 대해 단방향 해싱을 적용하는 방법을 택함. 구현 과정에서 어려움을 많이 느꼈지만 절대 포기하지 않았고, 결국 스스로 완성해냄.

프로젝트 후반에는 적절히 모듈화되고 디버그가 가능하며 기대만큼의 안정성을 보여주는 서버를 웹상에 구축하는 데에 성공함. Postman을 사용한 테스트와 검증을 통해 API의 무결성을 입증하고, 이를 모바일 앱에서 사용할 수 있도록 API documentation을 작성하여 배포함.

팀원간 의견을 조율하고 일정을 상기시키며 프로젝트를 이끄는 데에 큰 역할을 함. 졸업작품발표회 당일 시연을 설계하고 진행하였으며, 하드웨어 issue로 잠깐의 공백이 있었으나 매끄럽게 수행하여 성공적으로 마무리함.