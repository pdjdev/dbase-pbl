# 과제 수행 계획서
|조이름|조원|
|-|-|
|디베이스 (DBASE)|박동준, 박준엽, 성주원, 손열혼|

## 내용
| ② 생각(idea/hypothesis) = To-Be                                                                                                                                                                                                                                                                                                                                                                                                                                                            | ① 사실(fact) = As-Is                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ● 영화관 운영 정보시스템에 필요한 핵심 기능이 무엇인지 생각한다<br><br>● 기존의 레거시 시스템의 호환성 문제를 정확히 파악한다<br>○ 영화 예약 및 취소 시스템에서 기존 고객들의 불만사항을 듣는다<br>○ 직원 업무 관리 및 근태 시스템에서 어떤 부분이 비효율적이었는지 관리하는 매니저에게서 듣는다<br>○ 각 분점의 관리 시스템의 불만사항을 명확히 한다<br><br>● 운영 데이터베이스에 접근하는 프론트엔드를 어떠한 방식으로 구현할지 고민하여 본다<br>○ 네이티브 앱 (Java, .Net Framework 등)<br>○ 웹 앱 (JS, PHP, Node.js 등)<br><br>● 기존 레거시 시스템을 크게 2가지로 나누어 새 ERD를 설계한다<br>○ 1. 영화 예약 및 취소와 같은 서비스 시스템<br>○ 2. 직원 업무, 시설물, 근태 관리 시스템<br><br>● 실제로 운영되고 있는 영화관 정보시스템을 참고하여 본다. | ● 팀원의 대부분이 다이어그램과 데이터베이스에 대한 경험이 많지 않다<br><br>● 팀원의 대부분이 프론트엔드 개발에 대한 경험이 많지 않다<br><br>● 현재 우리를 고용한 업체는 낡은 시스템의 비효율 및 호환성 문제 때문에 고용하였다 (기존 시스템의 문제를 해결하도록 설계하여야 한다)<br><br>● 업무의 종류와 흐름을 파악하여 E-R다이어그램 형태로 설계하며 스키마를 제작하여야 한다<br><br>● 실제 영화관 직원들의 업무 및 매장별 시설물 관리에 대한 구체적인 이해가 부족하다<br><br>● 팀원 기술 스택<br>○  성주원: JS, CSS, jQuery, java, C, python<br>○  박준엽: Java, CSS, Python<br>○  박동준: Java, Pyhton, C#, VB.net, js, php<br>○  손열혼: C, Java, python |
| 문제의 원인, 결과, 가능한 해결안에 관한 학습자의 가설이나 추측 검토                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 문제에 제시된 사실과 학습자가 알고 있는 문제해결과 관련된 사실 확인                                                                                                                                                                                                                                                                                                                                                                                                                  |

| ③ 학습과제(learning issues)                                                                                                                                                                                                                                                                                                                                         | ④ 실천계획(action plans)                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ● 업무에 이용되는 정보의 종류와 흐름을 파악하여 E-R 다이어그램 형태로 표현한다<br>○ E-R 다이어그램을 제작하는데 사용할 프로그램을 조사한다<br><br>● E-R 다이어그램을 정돈되게 설계하는 방법을 배운다<br><br>● 제작한 다이어그램을 기반으로 데이터베이스 스키마를 설계한다<br><br>● 영화관의 시스템을 정확히 모르므로 분할하여 분석을 진행한다<br>○ 고객측에서의 시스템 사용 및 불만사항<br>○ 직원측에서의 업무 및 시스템 사용법<br>○ 매니저 측에서 직원 관리 방법<br><br>● 영화관 체인에서 사용할 정보시스템을 구상하여 실제로 구현 및 시연하는 것이 팀 프로젝트의 최종 목표로 한다<br> | ● 실제 서비스하고 있는 영화 예매 시스템을 참고하여 서비스를 구상해보도록 한다<br><br>● 데이터베이스 수업을 듣고 매주 팀플을 통해 진행 상황을 보고하고 피드백을 주고받도록 한다<br><br>● 올바른 데이터베이스를 설계하기 위해 정규화 이론을 배운다<br><br>● 정보시스템의 데이터베이스를 프론트엔드를 통해 접근할 계획이므로 프론트엔드 개발에 필요한 기술에 대해 조사하여 배운다<br><br>● 매주 목요일 4시 또는 7시에 회의를 진행하여 결과물을 공유하고 병합하는 회의를 가진다<br><br>● Oracle db를 활용해 개발할것으로 예상 되므로 실습으로 배우며 개인적인 시간에 복습 및 예습을 한다<br><br>● ERD cloud를 통해 다른 프로젝트들의 ERD 구성사례를 배워 데이터베이스 구조에 대한 이해력을 높인다<br><br>● ERD cloud를 통해 데이터베이스 설계를 진행한다 |
| 문제를 해결하기 위해 학습자가 학습 해야할 필요가 있는 학습내용을 선정                                                                                                                                                                                                                                                                                                                         | 문제를 해결하기 위해 학습자가 이후에 해야할 일 또는 실천 계획                                                                                                                                                                                                                                                                                                                                                                                                                                  |