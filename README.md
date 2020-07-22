# CODE BAKERY (코드베이커리)
💻 IT 개발자들의 정보 교류 커뮤니티

* * *
🔖 **프로젝트 설명**
  - 개발기간: 2020. 06. 11 ~ 2020. 07. 07
  - 팀 구성원: 6명
  - 역할: Project Engineer (스토리 보드 제작, DB 및 Class 설계 총괄)
  - 사용 기불 및 개발 환경
    - Language: Java, Javascript, HTML5, CSS3
    - Framework: Spring, Mybatis, jQuery, Bootstrap
    - DBMS: Oracle
    - Server: Apache Tomcat v9.0
    - IDE: Eclipse, Visual Studio Code
    
🔖 **담당 파트**
  - 질문 답변 게시판
  - 마이 페이지 (회원정보 수정)
  - 회원가입
  - 아이디, 비밀번호 찾기
* * *
✏️ _QnAController, Answer & Question & QComment (Biz, Dao, Dto)_
- qna.jsp & qna_write.jsp & qna_update.jsp : 질문 게시판 목록, 작성, 수정
  - 게시글 CRUD
  - 게시글 페이징
  - 해시태그별 조회
  - 
- qna_detail.jsp : 질문 답변 상세 페이지
  - 댓글 및 대댓글 CRUD
  - 답변 CRUD
  
- qna_addNonUser.jsp & qna_nonUserAnswer.jsp : 비회원 답변 달기
  
✏️ signup.jsp & mypage_chkPw.jsp & mypage_modify.jsp : 회원가입 및 회원정보 수정
  - 회원가입 유효성 검사 적용
  - cool SMS API를 이용항 문자 전송 서비스
  
✏️ find_Id.jsp & find_Pw.jsp : 아이디, 비밀번호 찾기

