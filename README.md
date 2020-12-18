# inflearn_spring
인프런에서 [김영한님의 spring 강의](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-%EC%9E%85%EB%AC%B8-%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8)를 수강하고 정리하는 repository 입니다.


### 강의 소개
- [x] 강의 소개 (12/15 완료)<br/><br/>

### 프로젝트 환경설정
- [x] 프로젝트 생성 (12/16)

https://start.spring.io/

> **maven / gradle**<br/>
필요한 라이브러리를 가져오고 build life cycle을 관리하는 tool<br/>
과거에는 maven 사용 요즘은 gradle 사용<br/><br/>
**Spring Boot 버전**<br/>
SNAPSHOT : 만들고 있는 중<br/>
M1 : 정식 릴리즈 된 것은 아님<br/><br/>
**Project Metadata**<br/>
Artifact : Build 되어 나오는 결과<br/><br/>
Build.gradle - dependencies를 repositories에 있는 곳에서 다운 받음



- [x] 라이브러리 살펴보기 (12/17)
> Build Tool들은 의존관계를 모두 관리함<br/>
Dependencies에서의 (*) : 중복을 제거해 준 것<br/>
test library : junit
log를 사용해야한다</br>
>> slf4j : interface</br>
logback : 실제 log를 구현체로 출력할 때 사용

- [x] view 환경설정 (12/18)
> resources > static 에 index.html 파일 생성 - localhost:8080 접속 시 Welcome page가 뜨는 것을 확인할 수 있음<br/>
https://docs.spring.io/spring-boot/docs/current/reference/html/spring-boot-features.html#boot-features-spring-mvc-welcome-page
- [x] 빌드하고 실행하기 (12/18)
> cmd 창에서 gradlew build<br/>
build>libs에 있는 jar 실행 (java -jar 파일명.jar)<br/>
gradlew clean 하면 build 폴더 사라짐

### 스프링 웹 개발기초
- [ ] 정적 컨텐츠
- [ ] MVC와 템플릿 엔진
- [ ] API
