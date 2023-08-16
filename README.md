# myClickhouse

kafka to ClickHouse
https://clickhouse.com/docs/en/integrations/kafka#kafka-to-clickhouse

n8n을 통해 Kafka -> Clickhouse 로 통계 데이터를 적재하는 작업을 수행하였다.

kafka 를 다뤄본적이 없었기 때문에 Consumer 설정은 Kafka 에 있을거라 착각했다.

어라.. 알고보니 Consume 은 외부에서 kafka 로 topic 을 지정하여 호출하는 것이였다..!

그리고 클릭하우스에서 kafka 설정을 할때 참 많은 테이블을 만들어 줘야 해서 불편한 감이 있었다..

굳이 kafka Engine 을 만들고, 중간에 materialized view 까지 만들어줘야 한다..

 
