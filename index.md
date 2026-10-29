# 질문 40개 — 통과 체크

통과 = 노트 없이 1분 안에 ① 정의 ② 왜 필요한가 ③ 내 프로젝트에서 본 장면을 말하고 꼬리질문 1개에 답한다. 다음 날 다시 1분으로 말해 통과하면 날짜를 적는다.

| 주  | #   | 질문                                         | 파일                                | 통과 날짜 |
| --- | --- | -------------------------------------------- | ----------------------------------- | --------- |
| 1   | 1   | JVM 메모리 구조와 GC                         | java-spring/jvm-gc.md               |           |
| 1   | 2   | 가상 스레드와 플랫폼 스레드                  | java-spring/virtual-thread.md       |           |
| 1   | 3   | Spring IoC/DI와 빈 생명주기                  | java-spring/ioc-bean.md             |           |
| 1   | 4   | Spring AOP 프록시                            | java-spring/aop-proxy.md            |           |
| 1   | 5   | HashMap 동작과 equals/hashCode               | java-spring/hashmap.md              |           |
| 1   | 6   | 영속성 컨텍스트와 변경 감지                  | jpa/persistence-context.md          |           |
| 1   | 7   | N+1 원인과 해결                              | jpa/n-plus-one.md                   |           |
| 1   | 8   | 지연 로딩과 프록시                           | jpa/lazy-proxy.md                   |           |
| 1   | 9   | OSIV                                         | jpa/osiv.md                         |           |
| 1   | 10  | 컬렉션 fetch join과 페이징                   | jpa/fetch-join-paging.md            |           |
| 2   | 11  | 왜 B+Tree인가                                | db/btree.md                         |           |
| 2   | 12  | 복합 인덱스 순서와 커버링 인덱스             | db/composite-covering.md            |           |
| 2   | 13  | 실행 계획 읽기                               | db/explain.md                       |           |
| 2   | 14  | 캐시 전략과 일관성                           | db/cache.md                         |           |
| 2   | 15  | Redis는 왜 빠른가                            | db/redis.md                         |           |
| 2   | 16  | 격리 수준과 이상 현상                        | tx-lock/isolation.md                |           |
| 2   | 17  | MVCC                                         | tx-lock/mvcc.md                     |           |
| 2   | 18  | 낙관적/비관적 락과 데드락                    | tx-lock/locks.md                    |           |
| 2   | 19  | `@Transactional` 전파와 자기 호출            | tx-lock/propagation.md              |           |
| 2   | 20  | 분산 락의 함정(만료 · 펜싱 토큰)             | tx-lock/distributed-lock.md         |           |
| 3   | 21  | TCP 연결 수립과 종료                         | network/tcp.md                      |           |
| 3   | 22  | HTTP/1.1 · 2 · 3 차이                        | network/http.md                     |           |
| 3   | 23  | 타임아웃 종류와 서킷브레이커 상태            | network/timeout-circuit.md          |           |
| 3   | 24  | Kafka 파티션 · 컨슈머 그룹 · 순서            | network/kafka.md                    |           |
| 3   | 25  | 전달 보장과 멱등성                           | network/delivery-idempotency.md     |           |
| 3   | 26  | 프로세스와 스레드                            | os/process-thread.md                |           |
| 3   | 27  | 컨텍스트 스위칭 비용                         | os/context-switch.md                |           |
| 3   | 28  | 스레드 풀 · 커넥션 풀 크기 정하기            | os/pool-size.md                     |           |
| 3   | 29  | 뮤텍스 · 세마포어와 데드락 조건              | os/mutex-semaphore.md               |           |
| 3   | 30  | 가상 메모리와 페이지 폴트                    | os/virtual-memory.md                |           |
| 4   | 31  | 토큰 · 컨텍스트 · 비용 구조                  | llm/token-cost.md                   |           |
| 4   | 32  | 비결정성과 평가 방법                         | llm/eval.md                         |           |
| 4   | 33  | tool calling 동작                            | llm/tool-calling.md                 |           |
| 4   | 34  | RAG 구조와 임베딩                            | llm/rag.md                          |           |
| 4   | 35  | 프롬프트 인젝션 방어                         | llm/injection.md                    |           |
| 4   | 36  | 시스템 설계: 근접성 서비스(45분)             | design/proximity.md                 |           |
| 4   | 37  | 시스템 설계: 선착순 쿠폰(45분)               | design/coupon.md                    |           |
| 4   | 38  | 사고 장면: 같은 기사에게 배차가 두 번 됐다   | tx-lock/incident-double-dispatch.md |           |
| 4   | 39  | 사고 장면: 결제가 두 번 빠졌다               | tx-lock/incident-double-payment.md  |           |
| 4   | 40  | 사고 장면: 락이 만료된 뒤 같은 작업이 두 번  | tx-lock/incident-lock-expiry.md     |           |
