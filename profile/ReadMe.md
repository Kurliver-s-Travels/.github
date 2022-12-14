

<p align="center"><img src="https://user-images.githubusercontent.com/79268661/184589145-0cf4e476-471d-4721-bb6d-de81f705a6d4.png"></p>

# 🐳 컬리버 여행기
> 소설 걸리버 여행기에서 걸리버는 우연히 소인국에 가게 되어 소인국 사람들에게 많은 도움을 주고 귀환하게 됩니다. 이런 점에서 신선하고 빠른 배송을 제공해주어 많은 사람의 삶에 도움을 주는 마켓컬리가 걸리버와 비슷하다고 느꼈습니다. 이번 해커톤을 통해 “컬리인”이 되어 마켓컬리와 함께 사람들의 문제를 해결하는 데 도움이 되고 싶습니다. 따라서 저희 팀이 함께하는 이 여정을 “컬리버 여행기(Kurliver’s Travels)”로 표현했습니다.

# 🐳 컬리 헥페스타 해커톤
> 컬리 헥페스타 해커톤은 다양한 분야의 사람들이 모여 어떠한 문제상황을 인식 및 아이디어 회의를 통하여 문제를 해결하는 대회입니다.

# 🧐 문제
> 마켓컬리의 물류 시스템은 DAS 방식을 사용하고 있습니다.  피킹, 다스, 패킹, 배송까지 사람이 처리하는 DAS 방식의 특성으로 인해 휴먼 에러가 발생한다는 것을 파악했습니다. 만약 패킹 중 휴먼 에러가 발생한다면 다시 피킹 과정을 수행해야 합니다. 이처럼 상호 업무 간 역행으로 인한 업무 비효율과 오배송으로 인한 고객 경험 저하를 해결하기 위해 1번 과제를 선택했습니다.

# 🔎 휴먼에러 발생 요소

기존의 인간의 개입이 필수적인 총괄지 업무 프로세스 특성상 휴먼 에러가 다수 발생합니다.

1. 지류 총괄지를 직접 들고 다님으로써 발생하는 총괄지 분실

2. 상품을 혼동하여 발생하는 오출(오피킹)

3. 문제 발생 시 책임소재 파악을 위한 총괄지 확인 과정 중 발생하는 오기록과 오확인

# 🔎 해결 아이디어

지류 총괄지 시스템을 컬리버 여행기가 개발한 디지털 방식으로 전환함으로써 휴먼 에러를 효율적으로 방지할 수 있습니다. 

✅ 첫 번째, 배분된 총괄지를 웹 화면 상으로 확인함으로써 총괄지 분실 위험이 없습니다. 

✅ 두 번째, 오피킹이 자주 발생하는 물품군을 픽업 전, QR코드 체크를 유도함으로써 오피킹을 방지할 수 있습니다. 먼저 상품 버켓(바구니)에 QR코드를 부여합니다. 픽업 전 QR코드를 확인하여 같은 제품인지 확인합니다. 신속한 배송을 위해 현재 컬리의 프로세스를 유지하되, 오피킹이 다수 발생하는 상품군에서만 확인합니다. 시간 소모를 최소화하면서 정확도를 높이기 때문에 효과적으로 휴먼 에러를 예방할 수 있습니다. 

✅ 세 번째,프로세스를 전산화하여 물류 작업 중 문제가 발생했을 때 문제 발생 지점을 더 빠르고 정확하게 확인할 수 있습니다. 책임소재 파악을 위해 종이 총괄지를 확인하는 방법은 이 안에서 또 다른 휴먼 에러를 야기합니다. 웹 화면을 통해 근로자별 작업 리스트를 한 눈에 확인하게 된다면 이런 비효율을 제거할 수 있습니다.

# 🐳 서비스 Architecture 소개
해당 서비스는 Client, Server로 이루어진 Architecture 구조입니다.


# 👩‍👩‍👧‍👦 팀 소개

## 팀원
> 해당 서비스는 FrontEnd 2명, BackEnd 2명으로 이루어져있습니다.

## Structure per Position

### 🖼 FrontEnd
❗️ 여기에 Front Stack 써주세요!


### 🛰 BackEnd

* Language : Java 11
* Framework : Spring Boot 2.7.2
* RDBMS : MySQL


## 🌐 Infra
* AWS : EC2
* Container : Docker
* Container Cloud : Docker Hub
* CI : Git Action

## 📝 Version Control
* Program : Git
* Cloud : Git Hub
* Branch Strategy : Git Flow

## 🪴 Cooperation Tool
* Docs : Notion
* Meeting Tool : Google Metting, Discord

# 프로젝트 중단 이유 ❗
해커톤 본선 진출을 하지 못하였습니다.
새롭게 뵙는분들과 여러가지 아이디어 이야기를 하고 생각을 나눌 수 있어서 좋은 기회가 되었습니다.

너무 아쉽지만 다음을 기약하여 프로젝트를 진행해보기로 하였습니다!


# 프로젝트 문서

* [✅ Notion 페이지](https://maddening-shelf-99c.notion.site/KURLY-HACK-FESTA-2022-bd4553f8e5714f10b830a7a65568aea3)
