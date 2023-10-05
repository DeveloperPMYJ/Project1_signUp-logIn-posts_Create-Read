# project1


A. 초기 세팅 

1) pull_request_template.md 상세하게 작성
2) .gitignore 에 다음의자동생성 사이트를 이용하여 vim, macOS, node, linux, visualStudioCode, dotenv 등 포함
3) .gitignore 에 dbmate(schema.sql) 파일과 추후 생성하고 관리할 csv 파일 확장자명/디렉토리 포함.
4) 필요한 package 설치
5) package.json ”script” 상 세부내역 수정
6)  .env 실제 런서버 구동이 올바르게 이루어지는 환경변수 작성
7)  상기 .env 파일에 기반한 .env.sample 파일 작성
8)  app.js 파일 생성 및 내부에 필요 코드(패키지 require 문, Health Check 문 등) 작성

B. dbmate 
ERD에 기반한 전체 table을 생성하는 migrations 파일 생성
dbmate up 명령어를 이용한 mysql database 내 파일 생성 확인
schema(database) 파일이 Github 상에 공유가 되지 않았는지 확인

C. 서버 구동 Test
1) npm start 했을 때, console 패널에 error 메시지 없는지 잘 실행 되는지 확인 (에러가 있다면 해결 할 것)**
2)  health-check 시 Ping-Pong의 request → response를 반환해주는 기본적인 http 통신 성공 확인
3)  프로젝트 Root Directory가 GitHub상에 반영되었는지 확인 → 최상위 경로가 depth 없이 노출되어야 성공

D. 회원가입 
- 데이터베이스에 저장 시, 비밀번호 해쉬(추가사항) 

E. 로그인 
- jwt 토큰 발급(추가사항) 

  
 
