# Kafka & Spark를 활용한 실시간 Datalake 구축

AWS 클라우드 기반으로 Spark를 사용해 실시간 데이터 레이크를 구성해보는 프로젝트입니다.

---

## 📚 전체 커리큘럼

| **Section** | **챕터** |
| :--- | :--- |
| **데이터레이크 소개** | 데이터레이크 구성요소 |
| | 데이터레이크 참조 아키텍처 (람다 아키텍처) |
| | 데이터레이크 참조 아키텍처 (카파 아키텍처) |
| **데이터레이크 아키텍처 설계** | git 설치하기 |
| | 파이썬 & 파이참 설치 |
| | github 레파지토리 생성 & 연결 |
| **AWS 환경생성** | AWS User 생성하기 |
| | AWS NAT Instance 만들기 |
| | AWS EC2 (Kafka Cluster) 생성하기 |
| | AWS EIP 부여하기 |
| | AWS NAT 연결하기 |
| | Ansible 설치하기 |
| | github Action 설정하기 |
| | github Action 실행하기 |
| | 번외) Billing 보기 |
| **Kafka 셋업** | Kafka 개념 |
| | Confluent Kafka 설치하기 |
| | Zookeeper 설치하기 |
| | Kafka 시작하기 |
| | Kafka 아키텍처 |
| | Broker 옵션 |
| | Topic 옵션 |
| **Kafka Producer 만들기** | Simple Producer 구현하기 |
| | Simple Producer 이해하기 |
| | 공공자전거 파이프라인 설계 |
| | 민감정보 관리하기 |
| | API 호출하기 |
| | Bicycle Producer 만들기 |
| | Producer 메커니즘과 성능 |
| | Producer 유용한 옵션들 (1/2) |
| | Producer 유용한 옵션들 (2/2) |
| **Kafka UI와 모니터링** | UI for Apache Kafka 설치하기 |
| | KPG 설치하기 |
| | Grafana Dashboard 구성하기 |
| **Kafka Consumer 만들기** | Consumer 배포환경 구성 |
| | Consumer 프로그램 구현 |
| | Sync vs Async commit |
| | Consumer Group |
| | Coordinator and Leader |
| | Partition Assignment |
| | Consumer 기타 옵션들 |
| **Spark 셋업과 기초** | Spark 서버 생성 |
| | Spark 설치하기 |
| | Spark 언어선택과 DataFrame |
| | Application 배포환경 구축 |
| | Spark apps 배포하기 |
| | Spark Program 구조 |
| | Spark Cluster 이해하기 |
| **Spark Cluster 구성** | Spark Standalone Cluster |
| | Hadoop Yarn 알아보기 |
| | Hadoop Yarn 설치하기 |
| | Spark On Yarn |
| | 배포모드 (client VS Cluster) |
| **Spark 이해** | Spark 함수 이해하기 |
| | Transform vs Action |
| | Dataframe Cache |
| | Dataframe 파티션 |
| | Partition & Executor |
| | Driver & Executor |
| | Job & Stage & Task |
| | wide vs narrow transform |
| | Spark Plan |
| | DataFrame read and write |
| **Spark SQL** | DataFrame Join |
| | DataFrame Join 유의사항 |
| | View 활용하기 |
| | DataFrame API vs SQL |
| | Spark Catalog |
| | Hive metastore |
| | Hive Metastore 연결 |
| | Write to S3 |
| | 번외) 컬럼기반 테이블 |
| **Spark Streaming** | Spark Streaming 시작하기 |
| | Kafka Source |
| | Offset Checkpoint |
| | Kafka Source Options |
| | ForeachBatch |
| | Json처리하기 |
| | Sink to S3 |
| | Streaming DataFrame View |
| **Streaming 프로그램 구성** | Streaming 프로그램 기본구조 셋팅 |
| | DataFrame 전달하기 (1/2) |
| | DataFrame 전달하기 (2/2) |
| | DataFrame checkpoint |
| | 따릉이 자전거 집계하기 |
| | AWS glue & athena |
| **실시간 Dashboard 구성** | Dashboard 구성 |
| **Spark 성능 최적화와 문제해결** | Spark 성능 Checklist |
| | Spark Executor Memory Structure |
| | Spark UDF |
| | Spark Join 전략 |
| | Spark AQE |
| | Spark Streaming As Consumer |
| | Spark 문제해결 |
| | Spark Streaming Lag 모니터링 |
| **Spark Streaming Master**| Kafka Sink |
| | Kafka Sink 프로그램 작성 |
| | Streaming Trigger |
| | Streaming Output mode |
| | Streaming Window |
| | Streaming watermark |
| **가용성 테스트** | 가용성 테스트의 개념과 목적 |
| | Zookeeper 가용성 테스트 |
| | Kafka Broker 가용성 테스트 (1/2) |
| | Kafka Broker 가용성 테스트 (2/2) |
| | Spark Executor 가용성 테스트 |
| | Spark Driver 가용성 테스트 |
| | yarn 가용성 테스트 |
| **마무리하며** | 마무리하며 |