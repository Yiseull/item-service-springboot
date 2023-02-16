# servlet-springboot
김영한님의 스프링 MVC 1편 - 백엔드 웹 개발 핵심 기술<br>

스프링 MVC - 웹 페이지 만들기

## Project Setting

IntelliJ IDEA 2021.2

[Spring Initializr](https://start.spring.io/)를 활용해서 스프링 부트 프로젝트를 만든다.
+ Project: Gradle - Groovy
+ Language: Java
+ Spring Boot: 2.7.8
+ Project Metadata
  + Group: hello
  + Artifact: item-service
  + Name: item-service
  + Package name: hello.itemservice
  + Packaging: Jar
  + Java: 11
+ Dependencies
  + Spring Web
  + Lombok
  + Thymelead

#### IntelliJ에서 빌드하도록 설정
File Setting -> Preferences Build, Execution, Deployment -> Build Tools -> Gradle
+ Build and run using: Gradle IntelliJ IDEA 변경
+ Run tests using: Gradle IntelliJ IDEA 변경

#### Lombok 사용을 위한 설정
File Setting -> Build, Execution, Deployment -> Compiler -> Annotation Processors
+ Enable annotation procession: 체크
