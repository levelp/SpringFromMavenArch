Получил архетип проекта
```
git clone https://github.com/kolorobot/spring-mvc-quickstart-archetype.git
```

Перехожу в каталог и устанавливаю архетип
```
cd spring-mvc-quickstart-archetype
mvn install
```


HTTPS
-----
``` xml
     <Connector port="8443" protocol="org.apache.coyote.http11.Http11NioProtocol"
                maxThreads="150" SSLEnabled="true" scheme="https" secure="true"
                clientAuth="false" sslProtocol="TLS" />
```