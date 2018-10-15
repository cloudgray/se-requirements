# Software Engineering - Requirements



## Introduction

## Project Requirements

### Development Requirements

Project requirement | 코드 버전 관리 및 협업
--- | ---
Description | Github를 이용해서 소스코드를 공유
Measurable |
Achievable | 깃허브 리포지토리를 만들고, Collaborator로 등록하거나 Pull Request를 받는다
Relevant | Schedule
Specific | 같은 팀 끼리는 협업을 하기 편하게 하고, 팀 전체에서는 코드를 정기적으로 공유하여 진행상황을 서로 확인하기 쉽게 한다.
Reference |

Project requirement | 시스템 구조
--- | ---
Description | 서버와 웹 클라이언트로 구분하여 개발
Measurable | 서버와 클라이언트가 할 일을 구분하여 API를 이용해 통신한다.
Achievable | 프론트엔드에서는 비동기적으로 데이터를 요청하고, 백엔드에서는 요청에 따라 데이터를 보내준다.
Relevant | 
Specific | 데이터 전송 형태는 REST가 편할 듯.
Reference | 

Project requirement | 개발 팀 구분
--- | ---
Description | 프론트엔드/백엔드로 개발팀을 구분
Measurable | 
Achievable | 개발자의 역할 구분으로 개발 효율 향상
Relevant | 
Specific | 9명의 조원을 팀으로 구성, 각 팀마다 역할을 할당해 개발의 효율성을 올리고 미팅 등에 있어서 시간적 융통성을 부여함으로써 전체적인 개발의 효율성 및 성능을 끌어 올림
Reference | 

Project requirement | 데이터 포맷
--- | ---
Description | 판매자로부터 데이터를 가져와 다루기 쉽고 통일된 형태로 정제하기
Measurable | 여러 쇼핑몰들로부터 받아온 데이터를 처리하여 동일한 schema를 가지도록 한다. 복잡한 처리 없이 하나의 테이블 안에 넣을 수 있도록 해야 한다.
Achievable | customer들에게 제공할 데이터 형식에 대한 메뉴얼 제공
Relevant | 
Specific | 사용할 데이터베이스와 크롤링 로직에 따라 구체적인 사항이 변경될 듯
Reference | 

## Capability Requirements

### System Requirements

- Priority는 큰 숫자일수록 우선순위가 높은 것입니다.

Requirement | ??
--- | ---
Title | 로그인 기능
Priorirty | 10
Description | 회원가입/로그인 기능을 구현하여 사용자의 정보를 저장해야 함
Input(s) | 
Source(s) | 
Output(s) | 사용자 등록 및 로그인 기능
Destination(s) | 
Precondition(s) | 데이터베이스 연동 및 저장할 데이터 정하기
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

Requirement | U2RQ-1
--- | ---
Title | 개인화된 추천
Priorirty | 7
Description | 사용자마다 추천되는 품목 다르게 한다(선호도, 체형 등 데이터 이용)
Input(s) | 로그인한 사용자의 정보(신체정보, 선호도 등)
Source(s) | 자용의 정보, 옷의 리뷰 정보와 판매 정보
Output(s) | 사용자에 따른 개인적 옷 추천
Destination(s) | 
Precondition(s) | 옷에 대한 데이터가 필요함. 리뷰가 쌓이는 등의 정보.
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

Requirement | U2RQ-2
--- | ---
Title | 옷의 분류와 비교
Priorirty | 9
Description | 비슷한 제품들을 나열하고 사용자에게 보여줌으로써 사용자가 비교하여 선택할 수 있게 만든다
Input(s) | 제품 목록, 제품별 스타일 태그
Source(s) | 판매 쇼핑몰
Output(s) | 유저가 설정한 카테고리로 분류 되고 나열된 제품 리스트
Destination(s) | 
Precondition(s) | 제품들의 정보
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

Requirement | U2RQ-3
--- | ---
Title | 신체 정보에 따른 리뷰 자동 등록
Priorirty | 8
Description | 구매자의 신체 정보를 입력받아서 옷을 구매한 후에 간편하게 리뷰 등록 (신체사이즈 정보 제공 거부 가능하도록)
Input(s) | 구매자의 신체 치수 데이터
Source(s) | 구매자의 후기
Output(s) | 합쳐진 후기
Destination(s) | 
Precondition(s) | 사용자(구매자)의 정보제공 동의
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

Requirement | U2RQ-4
--- | ---
Title | 관심 품목에 대한 세일 푸시 알림 기능
Priorirty | 5
Description | 사용자가 지정한 관심 품목에 대해 쇼핑몰의 세일 정보를 푸시 알림 해준다.
Input(s) | 각 사용자가 지정한 관심 품목
Source(s) | 쇼핑몰의 세일 정보
Output(s) | 관심 품목의 세일 정보를 사용자에게 푸시 알림
Destination(s) | 
Precondition(s) | 옷 세일 정보에 대한 데이터
Postcondition(s) | 
Proposed Activity | 
WinWin Agreement(s) | 
Mainstream Scenario | 
Exception Handling Scenario | 

## System Interface Requirements

### User Interface Requirements

Project requirement | SIR-1 사용성
--- | ---
Description | 쉽게 사용할 수 있어야 한다.
Measurable | 원하는 기능을 사용할 때까지의 소요시간(클릭 횟수)
Achievable | 화면의 구성과 메뉴의 flow, 버튼의 크기 등
Relevant | UI, UX, Front
Reference | 

Project requirement | SIR-2 광고
--- | ---
Description | 광고인듯 광고가 아닌 것 처럼 끼워둘 수 있는 UI.
Measurable | 사용자가 광고임을 인지할 수 있으면서도 이용에 불편을 주지 않아야 함
Achievable | 전체적인 UI와 위화감이 없는 광고 디자인
Relevant | 
Reference | 

<!--
## Level of Service Requirements

## Evolution Requirements
-->