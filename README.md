# 김진기 | Backend Developer

API와 데이터 파이프라인을 개발하며, 실패 상황을 재현하고 개선합니다. Java와 Spring Boot로 API를, Python으로 데이터 수집과 비동기 처리 흐름을 구현했습니다.

[기술 블로그](https://jingi723.github.io/)

## 프로젝트

### [EDGE — ETF 분석 서비스](https://github.com/alphaeveryday/edge)

데이터 수집, 정제, 저장과 후속 작업 전달을 담당했습니다. Java와 SQL로 작업 상태 조회 API를 구현하고, 저장과 메시지 전송 사이의 실패에 대비한 Outbox와 중복 처리 방지를 검증했습니다. 분석 모델과 설명 생성은 팀원이 담당했습니다.

### [선착순 쿠폰 발급](https://github.com/jingi723/coupon-system)

Java와 Spring Boot로 쿠폰 발급 API를 구현했습니다. DB와 Redis의 처리 방식을 비교하고, 동시 요청에서 재고 초과와 중복 발급이 발생하지 않는지 검증했습니다.

## 개발 기록

- [Transactional Outbox와 멱등 처리](https://jingi723.github.io/posts/edge-outbox/)
- [단계별 관측과 운영 조회 API](https://jingi723.github.io/posts/edge-observability/)
- [선착순 쿠폰 발급과 Redis](https://jingi723.github.io/posts/coupon-redis/)
