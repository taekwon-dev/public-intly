<p align="center">
    <img src="https://user-images.githubusercontent.com/70354365/189514759-c353be52-22ce-4910-99e1-421c0b0e2f5a.jpg" alt="intly-logo" width="900" height="380">
</p>
<div align="center">

### A Community for International Students All Around the World<br>

</div>
<br/>

<div align="center">

[![Application](http://img.shields.io/badge/Application-fc3465?style=flat&logo=github&logoColor=white&link=https://int-ly.com/)](https://int-ly.com/)
</div>
<br/>

## Int'ly

|로그인|프로필 및 활동 로그 조회||
|:-:|:-:|:-:|
|<img src=https://user-images.githubusercontent.com/70354365/189709972-17cc7a62-7e41-40cc-862f-996170513ad1.gif>|<img src=https://user-images.githubusercontent.com/70354365/189709970-8f4fa27e-2a8f-4d76-9c7e-405d77cfc5c7.gif>|
|<b>게시물 작성</b>|<b>게시물 검색</b>|<b>댓글 및 답글 작성</b>|
|<img src=https://user-images.githubusercontent.com/70354365/189709963-36f1d6a2-e0a5-4dea-8f85-ff80ca56775d.gif>|<img src=https://user-images.githubusercontent.com/70354365/189709955-850c827c-0b46-4284-96bb-57784b50bfdb.gif>|<img src=https://user-images.githubusercontent.com/70354365/189709934-8fa20fee-17ab-46f0-b686-8c826764666a.gif>|
|<b>인터뷰 템플릿 작성</b>|<b>인터뷰 템플릿 조회</b>|
|<img src=https://user-images.githubusercontent.com/70354365/190865993-8ae26afb-33bc-4695-ab26-ec58fd0b91f9.gif>|<img src=https://user-images.githubusercontent.com/70354365/190865986-61dcdd30-1781-4df9-bfa5-06d1d0ab84ae.gif>|

<p align="center">
    <b>Int'ly</b>는 전세계 유학생 <b>을 위한 해외생활 소셜 플랫폼 서비스</b>입니다.<br><br>  
</p>
<br/>

## Backend Tech Stacks

<p align="center">
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=JUnit5&logoColor=white">  <img src="https://img.shields.io/badge/MySQL-003545?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white"> 
  </p>
<p align="center">
<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=Amazon AWS&logoColor=white"> 
<img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white"> 
<img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white"> 
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white"> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> 
</p>


## Infrastructures


![image](https://user-images.githubusercontent.com/70354365/189530314-8240861c-f31b-4dbe-9e10-944610876a82.png)


![image](https://user-images.githubusercontent.com/70354365/189530262-1e8e9e29-2763-4960-87a2-5b60af130f20.png)

> <b>Int'ly</b>의 <b>초기 인프라</b>에 대해 더 자세하게 알고싶다면, [Int'ly Infrasturcture](https://medium.com/taekwon-v/devops-zext-infrastructure-ci-cd-5b4106dde554/) 글을 참고해주세요.

<br/>

##  Members

### Frontend

|Jade|Aiden|
|:-:|:--:|
|<img src="https://avatars.githubusercontent.com/u/72514247?v=4" alt="Jade" width="100" height="100">|<img src="https://avatars.githubusercontent.com/u/59464537?v=4" alt="Aiden" width="100" height="100">|
|[morethanmin](https://github.com/morethanmin)|[Mulgyeol](https://github.com/Mulgyeol)|

### Backend

|Yun|
|:-:|
|<img src="https://avatars.githubusercontent.com/u/70354365?v=4" alt="Yun" width="100" height="100">|
|[taekwon-dev](https://github.com/taekwon-dev)|

## What I Did in this Project

<details>
<summary style="font-size: medium">[Spring MVC] Handler Interceptor with Java Annotation, Reflection, and Proxy Pattern</summary>
<br/>

# [pick-git](https://github.com/woowacourse-teams/2021-pick-git) 팀 Handler Interceptor 분석

### | 분석 배경

![image](https://user-images.githubusercontent.com/70354365/192001431-9da4ce39-3212-4244-8dd4-e6ae7ae69c4f.png)
[ 그림 1 ]

[ 그림 1 ] 과 같이 **같은 URL 주소**를 갖지만 **HTTP 메소드**에 따라 서로 다른 핸들러 인터셉터를 통과하도록 설정해야 하는 경우

HTTP 메소드 분기 로직을 전개하기 위해 각 핸들러 인터셉터에서 허용하는 HTTP 메소드를 명시적으로 선언해야 하는 문제가 있다.

![image](https://user-images.githubusercontent.com/70354365/192002100-c029171a-9a09-4ee5-a285-ee91c9a7844b.png)
[ 그림 2 ]

이러한 문제 배경에는 핸들러 인터셉터를 통과할 API를 지정하는 방식이 [ 그림 2 ] 처럼 문자열 기반으로 API URL을 지정하는 것 외에 다른 방법이 없다는 점이 있었다.

결과적으로 원하는 문제 해결 방향은 **API URL + HTTP 메소드 정보**를 기준으로 통과할 핸들러 인터셉터를 지정할 수 있도록 하는 것이었고,

[pick-git](https://github.com/woowacourse-teams/2021-pick-git) 팀 프로젝트가 위 방향으로 구현되어 있어 분석하게 됐다.


### | 핵심 아이디어

분석 과정에서 문제 해결을 위해 사용된 핵심 아이디어를 다음과 같이 선정했다.

● Java Annotation

● Java Reflection

● Design Pattern - Proxy Pattern

핵심 아이디어 및 분석 내용 관련 자세한 내용은 아래 블로그 글을 통해서 확인할 수 있다.

- [Spring MVC - 핸들러 인터셉터에서 유저 인증 여부 및 권한 검사하기 [1] - GET /api/post/{postId} vs POST /api/post/{postId}](https://medium.com/taekwon-v/spring-mvc-%ED%95%B8%EB%93%A4%EB%9F%AC-%EC%9D%B8%ED%84%B0%EC%85%89%ED%84%B0%EC%97%90%EC%84%9C-%EC%9C%A0%EC%A0%80-%EC%9D%B8%EC%A6%9D-%EC%97%AC%EB%B6%80-%EB%B0%8F-%EA%B6%8C%ED%95%9C-%EA%B2%80%EC%82%AC%ED%95%98%EA%B8%B0-1-2e736844d46b)
- [Spring MVC - 핸들러 인터셉터에서 유저 인증 여부 및 권한 검사하기 [2] - pick-git 팀 해결 아이디어 소개 (Java Annotation, Reflection, Proxy Pattern)](https://medium.com/taekwon-v/spring-mvc-%ED%95%B8%EB%93%A4%EB%9F%AC-%EC%9D%B8%ED%84%B0%EC%85%89%ED%84%B0%EC%97%90%EC%84%9C-%EC%9C%A0%EC%A0%80-%EC%9D%B8%EC%A6%9D-%EC%97%AC%EB%B6%80-%EA%B2%80%EC%82%AC%ED%95%98%EA%B8%B0-2-pick-git-%ED%8C%80-%ED%95%B4%EA%B2%B0-%EC%95%84%EC%9D%B4%EB%94%94%EC%96%B4-%EC%86%8C%EA%B0%9C-java-annotation-reflection-85d02cc20b32)
- [Spring MVC - 핸들러 인터셉터에서 유저 인증 여부 및 권한 검사하기 [3] - pick-git 팀 소스 코드 분석하기](https://medium.com/taekwon-v/spring-mvc-%ED%95%B8%EB%93%A4%EB%9F%AC-%EC%9D%B8%ED%84%B0%EC%85%89%ED%84%B0%EC%97%90%EC%84%9C-%EC%9C%A0%EC%A0%80-%EC%9D%B8%EC%A6%9D-%EC%97%AC%EB%B6%80-%EA%B2%80%EC%82%AC%ED%95%98%EA%B8%B0-3-pick-git-%ED%8C%80-%EC%86%8C%EC%8A%A4-%EC%BD%94%EB%93%9C-%EB%B6%84%EC%84%9D%ED%95%98%EA%B8%B0-7aad4ffc8297)
</details>
<br/>