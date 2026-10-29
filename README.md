## 최준호 · Java/Spring 백엔드 개발자

커머스와 포인트 리워드 서비스에서 데이터 정합성 문제를 풀어 온 백엔드 개발자입니다.
외부 API와 DB를 함께 다루는 기능에서 중복 지급, 락 경합, 연동 장애가 생기지 않도록 트랜잭션 경계와 재시도·보정 구조를 설계합니다.
AI 도구(Claude Code, MCP)를 개발과 운영 업무에 적용하고, AI가 만든 결과를 검증하는 규칙과 절차를 만듭니다.

### 지금 하는 일

윈큐브마케팅에서 카드사 제휴 기프티콘 쇼핑몰과 CPS 포인트 리워드 서비스를 개발·운영하고 있습니다 (2024.04 ~).

- 외부 포인트 API 호출과 DB 기록을 단계별 트랜잭션으로 나누고 실패 보상 처리를 넣어, 출석 포인트 수백만 건 지급 중 같은 출석 중복 지급 0건
- 룰렛 티켓을 조건부 UPDATE로 먼저 차감하는 방식으로 바꿔, 동시 요청으로 생기던 티켓 이중 사용(0.07%)을 0건으로
- 쿠폰 발급 게이트웨이 교체를 레거시 경로를 유지한 병렬 경로와 스케줄 스위치로 무중단 전환, 전환 후 발송실패 0건
- 관리자 시스템에 MCP 서버를 직접 구현하고, 설정 반영 QA를 Claude Code 스킬로 자동화해 1회 QA 시간을 2시간에서 30분으로 단축

### 기술

- 주력: Java 8·11, Spring Boot 2.x, MyBatis, MySQL(Aurora), JSP
- 사용 경험: Java 21, Spring Boot 3.5, Spring Data JPA, QueryDSL, Spring Security(JWT), Jasypt, ShedLock, Bucket4j, Ehcache, Apache POI, AWS(S3, CloudFront), Jenkins
- AI 도구: Claude Code(플러그인·스킬), MCP
- 공부 중: Redis, Kafka, Docker, 테스트 코드(JUnit5, Testcontainers)

### 링크

- Blog: https://velog.io/@atelier3407/
- Email: inhacool99@gmail.com

회사 업무 코드는 사내 저장소에 있어 공개하지 않습니다. 이 계정에는 공부와 개인 프로젝트를 올립니다.
