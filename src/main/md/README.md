## [Key Apache Flink Topics Covered](https://developer.confluent.io/courses/apache-flink/intro/)

1. **What Apache Flink Is**

   * A battle-hardened, high-performance **stream processing engine**
   * Used for **demanding real-time applications**

2. **Core Design Principles**

   * **Share-nothing architecture**
   * **Local state management**
   * **Event-time processing**
   * **State snapshots** for recovery

3. **The 4 Big Ideas of Flink (Foundation Concepts)**

   1. **Streaming**

      * Streams as the primary abstraction
      * Continuous, unbounded data processing
   2. **State**

      * Stateful operators
      * Local, scalable, fault-tolerant state
   3. **Time**

      * Event time vs processing time
      * Correct results despite out-of-order data
   4. **State Snapshots (Fault Tolerance)**

      * Consistent checkpoints
      * Failure recovery without data loss

4. **Flink Runtime Architecture**

   * How streaming, state, time, and snapshots interact
   * What happens internally when Flink runs an application

5. **Stream Processing Perspectives**

   * Multiple conceptual views on streams and streaming systems
   * Covered in the **first half of the course**

6. **Hands-On Learning Approach**

   * Exercises paired with most modules
   * Reinforce concepts through practice

7. **Flink SQL**

   * Used for all hands-on exercises
   * Focus on **concepts and architecture**, not SQL complexity
   * Mostly simple operations (e.g., `GROUP BY` aggregations)

8. **Integration with Apache Kafka**

   * Producing and consuming streams using **Apache Kafka**
   * Exercises run on **Confluent Cloud**

9. **Confluent Ecosystem**

   * Course provided by **Confluent**
   * Learning materials hosted on developer.confluent.io