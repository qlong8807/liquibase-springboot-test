1.引入依赖

        <dependency>
            <groupId>org.liquibase</groupId>
            <artifactId>liquibase-core</artifactId>
        </dependency>
2.修改配置
spring.liquibase.enabled=true//true为开启，false为关闭。
spring.liquibase.change-log=classpath:/db/changelog/changelog-master.xml
3.写chanagelog
...
changeSet:
https://www.liquibase.org/documentation/changes/delete.html