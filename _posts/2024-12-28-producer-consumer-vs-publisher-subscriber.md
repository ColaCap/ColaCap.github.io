---
title: "Producer-Consumer VS Publisher-Subscriber (Pub-Sub) / 생산자-소비자 패턴 VS 펍섭 패턴"
date: 2024-12-28
modified_date: 2024-12-28
---

I was initially confused about the distinctions between **message queues**, **Kafka**, **producer-consumer**, and **pub-sub** because different sources describe Kafka as a message queue, a producer-consumer system, or a pub-sub system. To clarify these concepts, I created this table to distinguish these terms.

# Key Differences

| **Aspect**                | **Producer-Consumer**                                                                                                                          | **Pub-Sub**                                                                                                                                          |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Definition**            | A design pattern where writers (producers) generate tasks/messages, and each message is processed by exactly one reader (consumer).            | A design pattern where writers (publishers) broadcast messages to a topic, and all readers (subscribers) receive the same message independently.     |
| **Purpose**               | Efficient task distribution among readers.                                                                                                     | Event broadcasting to multiple readers.                                                                                                              |
| **Kafka Implementation**  | A topic with multiple partitions assigned to consumers in the same consumer group. Each message is consumed by only one consumer in the group. | A topic with multiple consumer groups. Each group independently consumes all messages. Within a group, the message is consumed by only one consumer. |
| **Other Implementations** | ActiveMQ, RabbitMQ, In-memory queues                                                                                                           | Redis Pub/Sub, Google Pub/Sub                                                                                                                        |

# Summary

- **Producer-Consumer** and **Pub-Sub** are distinct design patterns with clear and different purposes.
- Systems like Kafka can implement both patterns flexibly, depending on the configuration.

---
---
---

저는 **메시지 큐**, **Kafka**, **Producer-Consumer**, 그리고 **Pub-Sub(펍섭)** 시스템 간의 차이점이 혼란스러웠습니다. 이는 Kafka를 메시지 큐, Producer-Consumer 시스템, 혹은 Pub-Sub 시스템으로 설명하는 경우가 있기 때문입니다. 이러한 개념을 명확히 하기 위해 이 표를 작성하여 각 용어를 구분이 쉬워지게 하였습니다.

# 주요 차이점

| **항목**                  | **Producer-Consumer**                                                                                                                           | **Pub-Sub**                                                                                                                                        |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **정의**                 | Writer(Producer)가 작업/메시지를 생성하고, 각 메시지가 정확히 하나의 Reader(Consumer)에 의해 처리되는 디자인 패턴.                            | Writer(Publisher)가 메시지를 Topic으로 브로드캐스트하고, 모든 Reader(Subscriber)가 독립적으로 동일한 메시지를 수신하는 디자인 패턴.                  |
| **목적**                 | Reader 간 효율적인 작업 분배.                                                                                                                    | 다수의 Reader에게 이벤트 브로드캐스팅.                                                                                                             |
| **Kafka 구현**           | 여러 Partition으로 나뉜 하나의 Topic이 동일한 Consumer Group의 Consumer들에게 할당됨. 그룹 내에서는 각 메시지가 하나의 Consumer에 의해서만 처리됨.                | 여러 Consumer Group이 하나의 토픽을 구독하고, 동일한 메시지를 각각 처리함. 앞과 같이 각 그룹 내에서는 한 메시지는 하나의 Consumer에 의해 처리됨.                                   |
| **기타 구현**            | ActiveMQ, RabbitMQ, In-memory Queue                                                                                                              | Redis Pub/Sub, Google Pub/Sub                                                                                                                     |

# 요약

- **Producer-Consumer**와 **Pub-Sub**는 명확하고 서로 다른 목적을 가진 디자인 패턴입니다.
- Kafka와 같은 시스템은 구성에 따라 두 패턴을 유연하게 구현할 수 있습니다.

---

This article is created in collaboration with AI. AIs can make mistakes.

본 문서는 인공지능과의 대화를 통해 정리한 문서를 인공지능을 통해 번역한 문서입니다. 인공지능은 실수할 수 있습니다.
