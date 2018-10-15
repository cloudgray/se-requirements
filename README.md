# Software Engineering - Requirements

## Introduction

## Project Requirements

- 남자들이 온라인으로 옷을 구매할 때 일어나는 문제들을 해결하는 것을 목표로 한다
- 핏/사이즈 문제
  - 신체 사이즈를 포함한 리뷰를 남기기 편하게 해서 사용자들이 좀 더 현실적인 리뷰를 확인할 수 있도록 한다
- 코디 문제
  - 무난한 추천 코디를 보여줄 수 있도록 한다

### Schedule & Budget
Project requirement | schdule
--- | ---
Description | The cost of development for the software should be near zero
Measurable | For the course, there is no financial aid provided.
Achievable | The app will be developed as a project for a Software Engineering course. Freeware and free APIs will be used.
Relevant | 
Specific | Schedule
Reference |

Project requirement | budget
--- | ---
Description | Launch a web-bases native prototype app.
Measurable | The prototype app should be completed by mid-December.
Achievable | Include data crawling functions and basic UI/UX & server should be made.
Relevant | The project needs to be finished before the class ends with tangible results.
Specific | Schedule constraints.
Reference |



<!--
### Budget and Schedule
-->

### Development Requirements

Project requirement | 개발자 회의
--- | ---
Description | 팀원들이 주기적으로 만나서 service에 대한 회의를 진행한다.
Measurable | 일주일에 한 번 정도를 원칙으로 한다.
Achievable | 프로젝트에 진행에 대한 특정 주제에 대해 더 폭 넓게 서로 이해하기 위해 다 같이 모여 회의를 진행한다.
Relevant | 개발 팀 구분
Specific | 첫 2~3번의 회의는 전체 회의로 진행하되, 그 이후는 팀 구성에 따라서 유동적으로 할 수 있게 한다.
Reference |

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
Relevant | 백엔드 개발/프론트 개발
Specific | 9명의 조원을 팀으로 구성, 각 팀마다 역할을 할당해 개발의 효율성을 올리고 미팅 등에 있어서 시간적 융통성을 부여함으로써 전체적인 개발의 효율성 및 성능을 끌어 올림
Reference |

Project requirement | 백엔드 개발
--- | ---
Description | 사용 언어 : nodejs, python, mysql
Measurable |
Achievable | 서버 개발에는 nodejs, 크롤링에 python, db 구축에 mysql 쓸 예정
Relevant | 프론트엔드/백엔드로 개발팀을 구분
Specific | 각각 구성 개발에 필요한 최대한 효율적인 언어를 선택해서 사용.
Reference |

Project requirement | 프론트 개발
--- | ---
Description | 사용 언어 : 
Measurable |
Achievable | 
Relevant | 프론트엔드/백엔드로 개발팀을 구분
Specific | 
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

Requirement | U2RQ-1
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

Requirement | U2RQ-2
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

Requirement | U2RQ-3
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

Requirement | U2RQ-4
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

Requirement | U2RQ-5
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

Requirement | U2RQ-6
--- | ---
Title | 유저들의 리뷰 작성 유도
Priorirty | 7
Description | 유저들이 리뷰를 작성하는 것을 유도하기 위해 포인트제, 회원 등급제 등을 도입
Input(s) | 포인트, 회원 등급
Source(s) | 구매자의 후기
Output(s) | 자세하게 작성된 신뢰성이 있는 리뷰
Destination(s) |
Precondition(s) | 
Postcondition(s) |
Proposed Activity |
WinWin Agreement(s) |
Mainstream Scenario |
Exception Handling Scenario |

Requirement | U2RQ-7
--- | ---
Title | 추천 방식
Priorirty | 
Description | 사용자마다 추천되는 품목을 다르게 한다.
Input(s) | 에디터
Source(s) | 구매자의 정도(신체정보, 선호도)
Output(s) | 에디터에 의해 사용자에게 비교적 최적화된 옷 추천
Destination(s) |
Precondition(s) | 에디터들의 시간, 자본, 패션에 대한 정보
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
Relevant |
Reference |

Project requirement | SIR-2 광고
--- | ---
Description | 광고인듯 광고가 아닌 것 처럼 끼워둘 수 있는 UI.
Measurable | 사용자가 광고임을 인지할 수 있으면서도 이용에 불편을 주지 않아야 함
Achievable | 전체적인 UI와 위화감이 없는 광고 디자인
Relevant |
Reference |

Project requirement | 앱 처음 실행 화면
--- | ---
Description | 사용자의 회원가입/정보 입력을 받아야 한다.
Measurable |
Achievable | 이미 가입한 사용자는 로그인, 처음 사용하는 사용자는 회원가입 후 신체 정보 및 선호 정보를 입력할 수 있도록 한다.
Relevant |
Reference |

Project requirement | 앱 메인 화면
--- | ---
Description | 메인 화면에서 구입하려는 카테고리를 선택하거나 추천 코디를 선택할 수 있게 한다.
Measurable |
Achievable | 품목 카테고리를 선택하면 카테고리에 속한 품목 목록, 추천 코디를 선택하면 코디의 아이템들을 보여주는 페이로 이동한다.
Relevant |
Reference |

Project requirement | 카테고리 화면
--- | ---
Description | 카테고리를 선택하고 품목의 목록을 선택한 기준에 따라 정렬할 수 있도록 한다.
Measurable |
Achievable | 목록을 출력하고 특정한 품목을 선택하면 상품 상세 정보 화면으로 이동한다.
Relevant |
Reference |

Project requirement | 추천 코디 화면
--- | ---
Description | 추천 코디를 선택하면 코디에 포함된 품목들의 목록을 보여준다.
Measurable |
Achievable | 목록을 출력하고 특정한 품목을 선택하면 상품 상세 정보 화면으로 이동한다.
Relevant |
Reference |

Project requirement | 품목별 상세 정보 화면
--- | ---
Description | 하나의 품목의 상세 정보와 리뷰를 확인할 수 있고, 구매 페이지로 이어진다.
Measurable | 해당 품목에는 관련된 데이터가 보여지도록 한다.(구매한 사람의 size 비율, 특정 체형의 구매 비율 등)
Achievable |
Relevant |
Reference |


## Level of Service Requirements

Project requirement | LOR-1
--- | ---
Description | Meet the current security standard
Measurable | 개발자와 user간에, 상호 user간에도 접근 권한을 둔다.
Achievable | Unauthorized users shouldn’t be able to gain access to the system or the Webmail account. Each user must have access to his/her data only. 
Relevant | Security
Specific | 
Reference |

Project requirement | LOR-2
--- | ---
Description | Provide access to the application anytime, anywhere.
Measurable | web-app을 통해 이 service를 구현한다.
Achievable | Access to the system should be possible to anytime by any device.
Relevant | Esae of use
Specific | 
Reference |

Project requirement | LOR-3
--- | ---
Description | Provide intuitional GUI.
Measurable | 
Achievable | The user should be able to use the system easily without learning how to use the system.
Relevant | Easy to use
Specific | USers will be able to use the system easily.
Reference |

Project requirement | LOR-4
--- | ---
Description | Optimization for various devices.
Measurable | The service must be able to be used by various devices, at least devices with big portions of users.
Achievable | 
Relevant | Accessibility
Specific | The system should be tested in many OS versions.
Reference |

<!--
## Evolution Requirements
-->
