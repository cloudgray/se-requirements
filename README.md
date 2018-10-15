# Software Engineering - Requirements

## Introduction

## Project Requirements

### Development Requirements

Project requirement | Github 이용
--- | ---
Description | Github를 이용해서 소스코드를 공유한다
Measurable |
Achievable | Set a regular time uploading code to the ‘Github’
Relevant | Schedule
Specific | Regular uploading source code will make each developer understand other developer’s code and make them easy to collaborate.
Reference |

Project requirement | 개발 팀 구분
--- | ---
Description | 프론트엔드/백엔드로 개발팀을 구분한다
Measurable | 
Achievable | 프론트엔드/백엔드 개발자의 구분으로 개발 효율 향상
Relevant | 
Specific | 9명의 조원을 팀으로 구성, 각 팀마다 역할을 할당해 개발의 효율성을 올리고 미팅 등에 있어서 시간적 융통성을 부여함으로써 전체적인 개발의 효율성 및 성능을 끌어 올림
Reference | 

Project requirement | 시스템 구조
--- | ---
Description | 사용자가 쇼핑을 할 수 있는 웹사이트와 웹 앱을 개발한다
Measurable | 남자옷을 판매하는 온라인 쇼핑몰을 웹사이트와 웹 앱을 통해 사용자가 볼 수 있으며, 그 쇼핑몰로 direct하여 제품을 구매 할 수 있어야 함
Achievable | 사이트와 앱 내 결제는 불가능 하지만 해당 제품을 판매하는 사이트로 redirect 가능
Relevant | 
Specific | 유저의 니즈에 맞게 UI를 개발하여 보다 편리하고 정돈된 방법로 사용자가 원하는 제품을 구매할 수 있는 사이트로 redirect 함
Reference | 

Project requirement | 데이터 포맷
--- | ---
Description | customer들로부터 다루기 쉽고 통일된 형태로 데이터 받아오기
Measurable | 여러 쇼핑몰들로부터 받아온 데이터가 동일한 schema를 가져서, 복잡한 처리 없이 하나의 테이블 안에 넣을 수 있어야 함
Achievable | customer들에게 제공할 데이터 형식에 대한 메뉴얼 제공
Relevant | 
Specific | 유저의 니즈에 맞게 UI를 개발하여 보다 편리하고 정돈된 방법로 사용자가 원하는 제품을 구매할 수 있는 사이트로 redirect 함
Reference | 

## Capability Requirements

### System Requirements

Requirement | U2RQ-1 안장우
--- | ---
Title | 사람마다 코디가 다르게 보였으면 좋겠어요
Priorirty | 중상 - app의 정체성이 될 수 있음
Description | 각각 들어오는 사람마다 옷의 추천을 다르게 하여 각각의 화면 창에 나오게 한다.
Input(s) | status(몸무게, 키, 특징사항 등)를 가진 user의 login
Source(s) | user의 status, 옷의 판매 data 정보
Output(s) | 각각 user에 따른 다른 옷 추천
Destination(s) | 
Precondition(s) | 옷에 대한 데이터가 필요함
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

Requirement | U2RQ-2 이동욱
--- | ---
Title | 비슷한 종류의 옷을 비교하고 구매하기
Priorirty | 상 통합 쇼핑몰의 가장 기본적인 기능이라고 생각합니다.
Description | 각 쇼핑몰에서 판매하는 비슷한 제품들을 나열하고 사용자에게 보여줌으로써 사용자가 보다 편하게 비교하여 구매할 수 있게 만든다. 
Input(s) | 판매하는 제품들. 스타일 tag
Source(s) | 판매 쇼핑몰
Output(s) | 유저가 설정한 카테고리로 분류 되고 나열된 제품 리스트
Destination(s) | 
Precondition(s) | 제품들의 Data
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

Requirement | U2RQ-3 최규현
--- | ---
Title | 신체 정보에 따른 리뷰 자동 등록
Priorirty | 중상 - 인터넷 쇼핑에서는 사이즈 가늠을 돕는 기능이 매우 중요하기 때문에
Description | 신규회원 등록시 구매자의 신체 정보를 입력받아서 옷을 구매할 때마다 (너무 큼, 큼, 적당함, 작음. 너무 작음) 체크박스에 간편하게 체크만 하면 자동으로 리뷰 등록 (신체사이즈 정보 제공 거부 가능) 예) 키 178 몸무게 74kg  - 적당한 사이즈 입니다
Input(s) | 구매자의 신체 치수 데이타
Source(s) | 쇼핑몰 플랫폼
Output(s) | 간단한 옷 리뷰
Destination(s) | 쇼핑몰 플랫폼 (해당 쇼핑몰에 데이터 제공해줘도 될듯)
Precondition(s) | 사용자(구매자)의 정보제공 동의
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

Requirement | U2RQ-4 김윤성
--- | ---
Title | 관심 품목에 대한 세일 푸시 알림 기능
Priorirty | 중 - 관심 품목에 대한 알림을 줌에 따라 어플 사업에서 중요한 app 실행률을 높일 수 있음
Description | 사용자가 지정한 관심 품목에 대해 모든 쇼핑몰의 세일 정보를 실시간으로 푸시 알림 해준다.
Input(s) | 각 user가 지정한 본인의 관심 품목
Source(s) | 모든 쇼핑몰의 세일 database
Output(s) | 관심 품목에 대한 세일 정보를 user에게 푸시 알림
Destination(s) | 
Precondition(s) | 옷 세일 정보에 대한 데이터 필요
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

## System Interface Requirements

### User Interface Requirements

Project requirement | SIR-1
--- | ---
Description | 쉽게 사용할 수 있어야 한다.
Measurable | 구매자가 원하는 옷 페이지까지 몇 번 클릭(터치)하여 접근하는가, 버튼 사이즈는 눈으로 보기에, 손으로 터치하기에 적절한가
Achievable | 화면의 버튼 사이즈가 손가락 끝으로 누르기에 적절한 사이즈(모바일). 한 화면에 보이는 버튼 개수를 최대한 줄인다(모바일/웹 환경에 따라서 적절하게). 옷 구매 페이지로 가는데 클릭을 3번 이하로. 브랜드 목록은 1. 즐겨찾기에 추가된 브랜드 목록 먼저 띄워주고 2. 구매자 취향에 맞는 브랜드 목록을 띄워주고 3. ‘모든 브랜드’ 버튼을 누르면 전체 브랜드를 가나다 순으로 띄워준다.
Relevant | 
Reference | 

Project requirement | SIR-2
--- | ---
Description | UI 컨셉에 맞지 않거나 지나치게 화려하고 번쩍거려서 사용자의 앱 이용에 방해가 되는 광고를 지양, 앱에 녹아든 형태의 광고 제공. Developer들이 개별 쇼핑몰에게 광고 예시(메뉴얼)들을 제공함으로써 developer가 원하는 광고 컨셉을 전달 가능. 에디터’s pick의 형태와 같이 일반적인 이미지 형태의 광고가 아닌, 다른 형태의 광고를 제안해 볼 수 있음. 인터페이스 자체는 굉장히 중요하지만, 수익성과 직결돼 있어 신중함이 필요. 광고주들이나 광고를 내는 쇼핑몰의 입장에서도, 여러 광고가 한 화면에 정신없이 배치되어 주의를 분산시키는 것 보다는, 자신의 광고가 주목받는것을 원할 수 있음
Measurable | 
Achievable | 
Relevant | 
Reference | 

## Level of Service Requirements

## Evolution Requirements
