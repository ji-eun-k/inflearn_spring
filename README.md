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
- [x] 정적 컨텐츠 (12/22)
> 정적 컨텐츠 : 서버에서 파일을 **그대로** 웹 브라우저에 내려줌<br/>
내장 톰켓 서버가 받고 Spring에게 넘김 -> Spring은 Controller가 있는지 먼저 찾아봄 -> 없으므로 내부에서 파일 찾아 반환
- [x] MVC와 템플릿 엔진 (1/6)
> jsp, php와 같은 템플릿 엔진. html을 서버에서 **프로그래밍(변형)해서** 동적으로 바꿔 줌<br/>
model - view - controller <br/>

- [ ] API
> json이라는 data format으로 client에게 data를 전달<br/>
1. 화면은 client가 알아서 그리고 정리함<br/>
2. 서버끼리 data를 주고 받을 때 사용

### 회원 관리 예제 - 백엔드 개발
- [ ] 비즈니스 요구사항 정리
- [ ] 회원 도메인과 리포지토리 만들기
- [ ] 회원 리포지토리 테스트 케이스 작성
- [ ] 회원 서비스 개발
- [ ] 회원 서비스 테스트

### 스프링 빈과 의존관계
- [ ] 컴포넌트 스캔과 자동 의존관계 설정
- [ ] 자바 코드로 직접 스프링 빈 등록하기

### 회원 관리 예제 - 웹 MVC 개발
- [ ] 회원 웹 기능 - 홈 화면 추가
- [ ] 회원 웹 기능 - 등록
- [ ] 회원 웹 기능 - 조회
