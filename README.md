## [How to make use of DBzeium and flink - Gunnar Morling](https://www.youtube.com/watch?v=Vd1z9Z2-8VE&t=135s)
1. pg_logical_emit_message can be used without outbox table
2. We can alternatively store logical payload to outbox table and CDC can capture and send it
3. Make use of pgoutput plugin name
4. [Slides](https://speakerdeck.com/gunnarmorling/change-data-streaming-patterns-with-debezium-and-apache-flink)
5. [Github code](https://github.com/gunnarmorling/streaming-examples/tree/main/debezium-kafka-flink-sql-ingest)
6. You can add CDC with additional metadata and solve many problems with powerful patterns
    1. When CDC events are emitted, add who initiated txn, what user-case
    2. Flink can enrich CDC with additonal metadata and do more magic
    3. Add business, user, device_id
7. Streaming pattersn with dbzeium ==> outbox pattern, strangular fig pattern, Audit logs
8. [Flink intro](https://speakerdeck.com/hpgrahsl/dissecting-our-legacy-the-strangler-fig-pattern-with-apache-kafka-debezium-and-mongodb-at-voxxeddays-romania-2021?slide=31)


## Commands

git add src; git commit -m "flink";git push    