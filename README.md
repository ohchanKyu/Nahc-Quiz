<h1 align="center">$\bf{\large{\color{#0aba16}  Nahc \ Quiz }}$</h1>
<h3 align="center">
    랜덤 퀴즈 프로그램
</h3>
<p align="center">
  2023년 한신대학교 소프트웨어 공모전 우수상 작품
</p>

<br>

<blockquote>
  <p dir="auto">
     <strong> 2022년 한신대학교 소프트웨어 공모전 우수상 작품 </strong> <br>
     <strong> 개발 기간 : 2023.06.20 ~ 2023.07.29 </strong> <br>
     <strong> 단국대학교 컴퓨터공학과 오규찬 / okc0202@naver.com </strong> <br>
     <strong> 한신대학교 컴퓨터공학과 김승룡 / douglas@naver.com </strong>
  </p>
</blockquote>

<br>

### 프로젝트 소개
해당 프로젝트는 랜덤 퀴즈 프로그램으로, <br>
외부 API를 통해 여러 종류의 퀴즈에 대한 질문과 답변을 받아오고 <br>
단계별로 점수를 차등부여하여 사용자에게 퀴즈를 풀게하는 서비스이다. <br>
퀴즈 카테고리, 난이도, 문제 수를 직접 조정가능하며, <br>
랭킹 및 퀴즈에 대한 게시판 서비스 기능도 갖추고 있다.

<br> 

### 개발 환경
<p>$\bf{\large{\color{#0aba16} FrontEnd \ : HTML / CSS / JavaScript}}$</p>
<p>$\bf{\large{\color{#0aba16} BackEnd \ : Java / MySQL }}$</p>
<p>$\bf{\large{\color{#0aba16} Framework \ : Spring boot}}$</p>
<p>$\bf{\large{\color{#0aba16} Framework \ Main \  Dependency}}$</p>

- [x] MyBatis
- [x] Thymeleaf
- [x] Gradle

<br>

### 데이터 및 API
- <p>$\bf{\large{\color{#0aba16} Open \ Trivia \ DataBase }}$</p>
  
  - Open Trivia API를 통해 퀴즈 데이터 획득
  - 파라미터를 통해 문제 수, 난이도, 카테고리 설정


<br>

### 서비스 기능

- <p>$\bf{\large{\color{#0aba16} 퀴즈 \ 카테고리 \ 설정 \ 및 \ 문제풀이 \ 화면 }}$</p>


   #### 기능
     * 퀴즈에 대한 난이도, 문제 수, 카테고리에 대한 설정 제공
     * 난이도에 따라 차등 점수 부여
     * 사용자 친화적인 인터페이스로 손쉬운 설정 및 문제 풀이 제공
   #### 핵심 기술
     * Trivia API
     * 사용자 랭킹 시스템 데이터 (DBMS)
     * Trivia Data 필터 기능
   #### 사용자 인터페이스
     * 퀴즈 카테고리 설정 메인 화면 UI
       <p align="left">
         <img src="https://github.com/user-attachments/assets/abf6cb1c-2fa7-440e-8b5d-af44111856b1"/>
       </p>
     * 퀴즈 카테고리 설졍 UI
       <p align="left">
         <img src="https://github.com/user-attachments/assets/8d126ac0-de46-4fa6-a289-85ec8175e8f2"/>
       </p>
     * 퀴즈 풀이 진행 UI
       <p align="left">
         <img width="45%" height="250px" src="https://github.com/user-attachments/assets/8f4187bb-3d76-4daa-92a4-01bff2ba69be"/>
         <img width="50%" height="250px" src="https://github.com/user-attachments/assets/1008df46-3567-43ac-9d02-6bbf1dcb7e3e"/>
       </p>

<br>

- <p>$\bf{\large{\color{#0aba16} 완료 \ 문제 \ 및 \ 랭킹 \ 확인 }}$</p>

   #### 기능
     * 문제 풀이 완료 후 카테고리 및 총점수, 정답률 확인
     * 자신의 점수를 다른 사용자의 점수와 비교할 수 있는 랭킹 시스템 제공
     * 자신이 틀린 문제 혹은 맞은 문제를 각 문제 번호 별로 확인
   #### 핵심 기술
     * Trivia API
     * 사용자 랭킹 시스템 데이터 (DBMS)
     * 사용자의 문제 정답 여부 추적 알고리즘
   #### 사용자 UI
     * 카테고리 및 통계 요약 UI <br>
       <p align="left">
         <img src="https://github.com/user-attachments/assets/5c53df10-49bc-42f1-accf-fd5a8154f232"/>
       </p>

     * 문제 요약 및 정답 UI
       <p align="left">
         <img src="https://github.com/user-attachments/assets/5373d711-ab85-4137-b396-0e4612661e0a"/>
       </p>
     * 서비스 사용자 랭킹 시스템 UI
       <p align="left">
         <img src="https://github.com/user-attachments/assets/58e640da-904a-4e9f-912e-75c39c9b911d"/>
       </p>
       <p align="left">
         <img src="https://github.com/user-attachments/assets/938d1960-e1c8-4acb-9ebb-863054bdab12"/>
       </p>

<br>

- <p>$\bf{\large{\color{#0aba16} 게시판  \ 및 \ 댓글 \ 기능 }}$</p>

   #### 기능
     * 퀴즈에 대한 여러 답을 주고받을 수 있는 커뮤니티 제공
     * 사용자 간 댓글을 통한 소통
     * 퀴즈에 대한 사진 업로드 기능
   #### 핵심 기술
     * 커뮤니티 플랫폼 구축 및 댓글 시스템
     * 파일 업로드 기능
     * 사용자 포스트 및 댓글 데이터 (DBMS)
   #### 사용자 UI
     * 게시판 메인화면 UI <br>
       <p align="left">
         <img src="https://github.com/user-attachments/assets/a5327085-504b-44a7-b13e-823bbed2322b"/>
       </p>
     * 게시판 글 및 댓글 UI
       <p align="left">
         <img src="https://github.com/user-attachments/assets/1a5eb8a6-3d51-4a00-94f4-45f00f96cc04"/>
       </p>
       <p align="left">
         <img src="https://github.com/user-attachments/assets/41efcad5-d33c-46fe-8a01-1a86de2768f3"/>
       </p>

### 아키텍쳐
#### 디렉터리 구조
```
📦java
 ┗ 📂com
 ┃ ┗ 📂example
 ┃ ┃ ┗ 📂koskQuizProgram
 ┃ ┃ ┃ ┣ 📂api
 ┃ ┃ ┃ ┃ ┗ 📜ApiMemberController.java
 ┃ ┃ ┃ ┣ 📂board
 ┃ ┃ ┃ ┃ ┣ 📜BoardController.java
 ┃ ┃ ┃ ┃ ┗ 📜BoardRestController.java
 ┃ ┃ ┃ ┣ 📂config
 ┃ ┃ ┃ ┃ ┣ 📜InterceptorConfig.java
 ┃ ┃ ┃ ┃ ┣ 📜LoginInterceptor.java
 ┃ ┃ ┃ ┃ ┗ 📜WebConfig.java
 ┃ ┃ ┃ ┣ 📂controller
 ┃ ┃ ┃ ┃ ┗ 📜ApiController.java
 ┃ ┃ ┃ ┣ 📂exception
 ┃ ┃ ┃ ┃ ┣ 📜BadRequestException.java
 ┃ ┃ ┃ ┃ ┣ 📜InsertFailException.java
 ┃ ┃ ┃ ┃ ┣ 📜ResourceAlreadyInUseException.java
 ┃ ┃ ┃ ┃ ┗ 📜UserNotFoundException.java
 ┃ ┃ ┃ ┣ 📂mail
 ┃ ┃ ┃ ┃ ┗ 📜MailController.java
 ┃ ┃ ┃ ┣ 📂mainPage
 ┃ ┃ ┃ ┃ ┗ 📜MainpageController.java
 ┃ ┃ ┃ ┣ 📂mapper
 ┃ ┃ ┃ ┃ ┣ 📜BoardMapper.java
 ┃ ┃ ┃ ┃ ┣ 📜CommentMapper.java
 ┃ ┃ ┃ ┃ ┗ 📜MemberMapper.java
 ┃ ┃ ┃ ┣ 📂member
 ┃ ┃ ┃ ┃ ┗ 📜MemberController.java
 ┃ ┃ ┃ ┣ 📂model
 ┃ ┃ ┃ ┃ ┣ 📜ApiVO.java
 ┃ ┃ ┃ ┃ ┣ 📜BoardVO.java
 ┃ ┃ ┃ ┃ ┣ 📜CommentVO.java
 ┃ ┃ ┃ ┃ ┣ 📜MailVO.java
 ┃ ┃ ┃ ┃ ┣ 📜MemberVO.java
 ┃ ┃ ┃ ┃ ┗ 📜Message.java
 ┃ ┃ ┃ ┣ 📂payload
 ┃ ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┗ 📂response
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ApiResponse.java
 ┃ ┃ ┃ ┣ 📂service
 ┃ ┃ ┃ ┃ ┣ 📜BoardService.java
 ┃ ┃ ┃ ┃ ┣ 📜CommentService.java
 ┃ ┃ ┃ ┃ ┗ 📜MemberService.java
 ┃ ┃ ┃ ┣ 📂serviceImpl
 ┃ ┃ ┃ ┃ ┣ 📜BoardServiceImpl.java
 ┃ ┃ ┃ ┃ ┣ 📜CommentServiceImpl.java
 ┃ ┃ ┃ ┃ ┣ 📜MailServiceImpl.java
 ┃ ┃ ┃ ┃ ┗ 📜MemberServiceImpl.java
 ┃ ┃ ┃ ┣ 📂Util
 ┃ ┃ ┃ ┃ ┣ 📜ExceptionMessage.java
 ┃ ┃ ┃ ┃ ┗ 📜Util.java
 ┃ ┃ ┃ ┗ 📜KoskQuizProgramApplication.java
📦resources
 ┣ 📂mappers
 ┃ ┣ 📜boardMapper.xml
 ┃ ┣ 📜commentMapper.xml
 ┃ ┗ 📜memberMapper.xml
 ┣ 📂schema
 ┃ ┗ 📜DML.sql
 ┣ 📂static
 ┃ ┣ 📂css
 ┃ ┃ ┣ 📜editId.css
 ┃ ┃ ┣ 📜editPass.css
 ┃ ┃ ┣ 📜editPerson.css
 ┃ ┃ ┣ 📜find_id.css
 ┃ ┃ ┣ 📜find_pw.css
 ┃ ┃ ┣ 📜join.css
 ┃ ┃ ┣ 📜list.css
 ┃ ┃ ┣ 📜login.css
 ┃ ┃ ┣ 📜loginRequired.css
 ┃ ┃ ┣ 📜main.css
 ┃ ┃ ┣ 📜myPost.css
 ┃ ┃ ┣ 📜quizMenu.css
 ┃ ┃ ┣ 📜quizTemplate.css
 ┃ ┃ ┣ 📜rankList.css
 ┃ ┃ ┣ 📜resultPage.css
 ┃ ┃ ┣ 📜UserPage.css
 ┃ ┃ ┣ 📜view.css
 ┃ ┃ ┗ 📜write.css
 ┃ ┣ 📂font
 ┃ ┃ ┗ 📜Naver-Icons.woff
 ┃ ┣ 📂images
 ┃ ┃ ┣ 📜leaderboard.png
 ┃ ┃ ┣ 📜note.png
 ┃ ┃ ┣ 📜quiz.png
 ┃ ┃ ┣ 📜score.png
 ┃ ┃ ┣ 📜spr_book.png
 ┃ ┃ ┗ 📜user.png
 ┃ ┗ 📂uploadImage
 ┃ ┃ ┣ 📜063aacd3-d05c-4290-addc-3baa4cb3c526.png
            ...
 ┃ ┃ ┗ 📜fc68ae7e-00e5-46a2-8350-ba67772613d4.png
 ┣ 📂templates
 ┃ ┣ 📂board
 ┃ ┃ ┣ 📜list.html
 ┃ ┃ ┣ 📜myPost.html
 ┃ ┃ ┣ 📜rankList.html
 ┃ ┃ ┣ 📜view.html
 ┃ ┃ ┗ 📜write.html
 ┃ ┣ 📂main
 ┃ ┃ ┣ 📜loginRequired.html
 ┃ ┃ ┗ 📜main.html
 ┃ ┣ 📂member
 ┃ ┃ ┣ 📜find_id.html
 ┃ ┃ ┣ 📜find_pw.html
 ┃ ┃ ┣ 📜join.html
 ┃ ┃ ┗ 📜login.html
 ┃ ┣ 📂message
 ┃ ┃ ┗ 📜message.html
 ┃ ┣ 📂quiz
 ┃ ┃ ┣ 📜quizMenu.html
 ┃ ┃ ┣ 📜quizTemplate.html
 ┃ ┃ ┗ 📜resultPage.html
 ┃ ┗ 📂user
 ┃ ┃ ┣ 📜editId.html
 ┃ ┃ ┣ 📜editPass.html
 ┃ ┃ ┣ 📜editPerson.html
 ┃ ┃ ┗ 📜userPage.html
 ┣ 📜log4jdbc.log4j2.properties
 ┗ 📜logback-spring.xml
```
