- kafka
  - https://kafka.apache.org/
  - https://kafka-tutorials.confluent.io/
  - https://kafka.apache.org/24/documentation/streams/developer-guide

  - https://kafka.apache.org/24/javadoc/org/apache/kafka/streams/kstream/KStream.html
  - https://kafka.apache.org/24/javadoc/org/apache/kafka/clients/consumer/KafkaConsumer.html
  - https://kafka.apache.org/24/javadoc/org/apache/kafka/clients/producer/KafkaProducer.html

  - https://github.com/perkss/clojure-kafka-examples
  - https://github.com/troy-west/kstream-examples

  - https://www.confluent.io/blog/event-sourcing-using-apache-kafka/
  - https://www.confluent.io/blog/building-a-microservices-ecosystem-with-kafka-streams-and-ksql/
  - https://github.com/confluentinc/kafka-streams-examples/tree/4.0.0-post/src/main/java/io/confluent/examples/streams/microservices
  - configs
    - http://kafka.apache.org/documentation.html#configuration
    - http://kafka.apache.org/documentation.html#topicconfigs

    - http://kafka.apache.org/documentation.html#producerconfigs
    - https://kafka.apache.org/24/javadoc/org/apache/kafka/clients/producer/KafkaProducer.html

    - http://kafka.apache.org/documentation.html#consumerconfigs
    - https://kafka.apache.org/24/javadoc/org/apache/kafka/clients/consumer/KafkaConsumer.html

- clj
  - spec
    - guides
      - https://clojure.org/guides/spec
      - https://clojure.github.io/spec.alpha/clojure.spec.alpha-api.html
      - https://clojure.org/guides/test_check_beginner
        - https://github.com/clojure/test.check/blob/master/README.md
        - https://github.com/clojure/test.check/blob/master/doc/intro.md
      - https://blog.taylorwood.io/2018/10/15/clojure-spec-faq.html
    - fdef defmulti
      - https://clojuredocs.org/clojure.spec.alpha/fdef#example-5c4b535ce4b0ca44402ef629
    - code
      - https://github.com/clojure/tools.deps.alpha/blob/master/src/main/clojure/clojure/tools/deps/alpha/specs.clj
  - java.time.Instant
    - https://stackoverflow.com/questions/36639154/convert-java-util-date-to-what-java-time-type
  - regex
    - https://docs.oracle.com/javase/9/docs/api/java/util/regex/Pattern.html
  - 

- cljs
  - antd
    - 4.0 changes https://github.com/ant-design/ant-design/issues/16911


- issues
  - "attempting to call unbound transit-json..." when ineracting with kafka from repl
    - starnet.app.alpha.aux.serdes namespace must be imported 