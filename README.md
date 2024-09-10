# DiscordProject

## 프로젝트명
디스코드

## 프로젝트 개요
디스 코드 웹 페이지 구현

## 개발 인원
김동희 (BE)
김근형 (FE)

## 사용 기술
BE : Spring boot


FE : React


Build Tool : Maven


Database Framework : mybatis (mysql)


## [DB 설계](https://www.erdcloud.com/p/W4CEcQddyew6pw4Zu)


## 문제점
### 1. 스프링 부트와 리액트의 통신
HTML을 사용할 땐 Thymeleaf를 통해 값을 보여주거나 받아왔다. 하지만 리액트의 경우 빌드도 해야하고 요청을 보내면
내가 스프링에서 그 경로로 요청을 받아야한다. 이것에 대하여 어떻게 처리를 해야 하는지
일단 첫 번째 해결 방법으론 빌드된 리액트 프로젝트를 static 경로에 넣어 getmapping을 했더니 뷰는 띄워지는 것을 확인했다.
하지만 매번 이렇게 하니 번거로우니 서버를 사서 진행하고자 한다.
