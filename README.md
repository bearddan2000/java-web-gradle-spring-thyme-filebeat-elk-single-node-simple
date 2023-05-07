# java-web-gradle-spring-thyme-filebeat-elk-single-node-simple

## Description
A thyme springboot java gradle build,
that connects to elasticsearch database single node cluster.

Loads data through filebeat and logstash.

Uses spring test + junit to unit test.

## Tech stack
- springboot
  - thyme
- gradle
  - elasticsearch drivers
  - lombok
  - junit
  - spring test
- bootstrap
- jquery
- dataTable
- filebeat
- logstash
- kibana

## Docker stack
- elasticsearch:8.2
- logstash:7.12
- kibana:7.12
- filebeat:7.12
- gradle:jdk11

## To run
`sudo ./install.sh -u`
- Endpoints
  - Get all curl -i localhost/dogs
  - Get by id curl -i localhost/dog/<id>
- [Available](http://localhost)
- [Node 1 elasticsearch webui](http://localhost:9200)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Baeldung code](https://www.baeldung.com/spring-data-elasticsearch-tutorial)
- [Springboot Application Config](https://betterjavacode.com/programming/elasticsearch-spring-boot)
- [Gradle logging plugin](https://github.com/radarsh/gradle-test-logger-plugin)
