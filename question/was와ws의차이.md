## WAS 와 WebServer의 차이가 무엇인가요?

* WAS(Web Application Server)
  * 비즈니스 로직을 넣을 수 있다. 
  * ex) Tomcat, PHP, ASP, .NET 
* WS(Web Server)
  * 비즈니스 로직을 넣을 수 없다.
  * Nginx, Apache.. etc


## WAS 와 WS 를 분리하는 이유는?

1. Web Server 를 통해 정적인 파일들을 Application Server 까지 보내지 않고 앞단에서 빠르게 보내줄 수 있기 때문입니다.

2. 따라서 Web Server 에서는 정적 컨텐츠만 처리하도록 기능을 분배하여 서버의 부담을 줄일 수 있습니다.