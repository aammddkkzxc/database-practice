### 데이터베이스 학습
- MySQL 개인 학습 레포지토리
- 학습 후 정리하고 싶은 내용들만 포함되어 있습니다
- 출처 [김영한의 실전 데이터베이스 로드맵](https://www.inflearn.com/roadmaps/10479), [비전공자도 이해할 수 있는 MySQL 성능 최적화 입문/실전 (SQL 튜닝편)](https://www.inflearn.com/course/%EB%B9%84%EC%A0%84%EA%B3%B5%EC%9E%90-mysql-%EC%84%B1%EB%8A%A5%EC%B5%9C%EC%A0%95%ED%99%95-sql%ED%8A%9C%EB%8B%9D)

### 학습 내용
- MySQL 기본 ([basic](https://github.com/aammddkkzxc/database-practice/tree/main/basic))
  - 데이터 다루기 (타입 선택, 관리, 가공)
  - 조회, 정렬, 집계, 그루핑
  - 조인과 서브쿼리, 성능
  - 인덱스와 비교, LIKE 범위검색, 정렬, 성능과 손익분기점
  - 커버링 인덱스, 복합 인덱스
  - 인덱스 설계, 사용 시 주의사항
- 데이터베이스 모델링 1 ([modeling-1](https://github.com/aammddkkzxc/database-practice/tree/main/modeling-1))
  - 설계 과정, 단계별 산출물, 주의사항
  - 엔티티의 분류와 역할
  - 키, 연관관계 설계
  - 식별, 비식별 관계
  - 정규화, 역정규화
  - 네이밍, 데이터 타입 규칙
- SQL튜닝 기초 ([sql-tuning-basic](https://github.com/aammddkkzxc/database-practice/tree/main/sql-tuning-basic))
  - MySQL 내부 구조, 동작 방식
  - 클러스터링 인덱스/넌 클러스터링 인덱스
  - 실행 계획 분석법
  - 튜닝 기초 팁

### 느낀점
- SQL은 단순한 질의 언어가 아니라 데이터 구조와 저장 방식을 이해해야 최적화할 수 있는 기술임을 체감했다
- 설계의 중요성과 왜 현대적 설계엔 유연한 구조를 가장 중시하게 되었는지
- 의도한 결과를 얻는 것을 넘어서 데이터 흐름과 내부 동작을 예측, 작성한 후 꼭 눈으로 확인해보는 습관이 중요하다
