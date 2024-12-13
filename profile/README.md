# 📖 55G 도서 쇼핑몰
![2024-11-26 17_21_21 895](https://github.com/user-attachments/assets/1e4933e0-1b56-43c7-983c-42fb3d172838)

## 프로젝트 소개
- 고객이 책을 검색하고 주문할 수 있는 인터넷 서점 개발

 ## 개발 기간
 - 2024-10-15 ~ 2024-12-16

## 팀원 구성
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/FlowerfulFort.png" width="100" height="100" alt="김준엽"/><br>
      <a href="https://github.com/FlowerfulFort"><b>김준엽</b></a>
    </td>
    <td align="center">
      <img src="https://github.com/Gyubin-Han.png" width="100" height="100" alt="한규빈"/><br>
      <a href="https://github.com/Gyubin-Han"><b>한규빈</b></a>
    </td>
    <td align="center">
      <img src="https://github.com/Minjeong63.png" width="100" height="100" alt="김민정"/><br>
      <a href="https://github.com/Minjeong63"><b>김민정</b></a>
    </td>
    <td align="center">
      <img src="https://github.com/desworld.png" width="100" height="100" alt="김민준"/><br>
      <a href="https://github.com/desworld"><b>김민준</b></a>
    </td>
    <td align="center">
      <img src="https://github.com/bobo1006.png" width="100" height="100" alt="천보성"/><br>
      <a href="https://github.com/bobo1006"><b>천보성</b></a>
    </td>
    <td align="center">
      <img src="https://github.com/Jung-won-seok.png" width="100" height="100" alt="정원석"/><br>
      <a href="https://github.com/Jung-won-seok"><b>정원석</b></a>
    </td>
    <td align="center">
      <img src="https://github.com/DooYoungHo.png" width="100" height="100" alt="두영호"/><br>
      <a href="https://github.com/DooYoungHo"><b>두영호</b></a>
    </td>
  </tr>
</table>

## 개발환경
- 개발도구 : Intellij IDEA - Ultimate
- 언어 : Java 21 LTS / Eclipse Temurin
- 빌드도구 : Maven
- 개발 :
  - Spring Framework(6.1.13)
  - Spring Boot(3.3.4)
  - Spring Cloud
    - Spring Cloud Netflix(eureka)
    - Spring Cloud Config
    - Spring Cloud OpenFeign
  - JPA : Query
- 테스트 환경 :
  - Junit5 / AssertJ / Mokito / SonarQube
  - SonarQube Test Coverage 60% 이상
- 데이터베이스 : MySQL(8.0.37) / Redis
- 검색엔진 : Elastic Search (8.6.2)
- 모델링(ERD) : ERD Cloud
- Message Queue : RabbitMQ
- 협업도구 : GitHub Project
- CI/CD :
  - Continuous Integration
  - Continuous (Delivery, Deployment)
   - Github Action
   - Docker
   - Github Package Registry
- UI : Bootstrap
- NHN Cloud :
  - Instance
  - Secure Key Manager
  - Image Manager    



# 아키텍쳐 구조
![아키텍쳐](https://github.com/user-attachments/assets/8394e60b-6742-4779-9e6b-bffe0d7f3be6)

## ERD
![Copy of 55G COM V8-2](https://github.com/user-attachments/assets/6c58811d-2808-4535-a054-560d70ce478b)


## 테스트 커버리지
- Backend 서버
<img width="873" alt="backend서버" src="https://private-user-images.githubusercontent.com/97074298/395464016-a9a56b87-6b66-420a-bf38-7ac1ea0302b0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzQwOTU3NDAsIm5iZiI6MTczNDA5NTQ0MCwicGF0aCI6Ii85NzA3NDI5OC8zOTU0NjQwMTYtYTlhNTZiODctNmI2Ni00MjBhLWJmMzgtN2FjMWVhMDMwMmIwLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjEzVDEzMTA0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWFmZjVjZTVkNzA0NjBhMDhkOGZlYjAwYmYxMjQzYWZkMjM1YzIwYTk1NzY0NWRmMzhjMmQyNjc1Mzc4ZGM5MzMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.2KSvtwtGWumZlAxj_JWoLVJkS0OqePk0TTr5GW0riSQ">

- Frontend 서버
<img width="868" alt="frontend서버" src="https://private-user-images.githubusercontent.com/97074298/395463856-017f534f-84bd-4e8e-bf9e-4937bc1d1efc.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzQwOTU3NDAsIm5iZiI6MTczNDA5NTQ0MCwicGF0aCI6Ii85NzA3NDI5OC8zOTU0NjM4NTYtMDE3ZjUzNGYtODRiZC00ZThlLWJmOWUtNDkzN2JjMWQxZWZjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjEzVDEzMTA0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWVkNzY5ZWRhMGI3YjBlZjc0NTJlNmQ3MTYyOTgwNTY2N2FlZjYxZTJhMGQ0MjdhMGM1ZDU2OGRiZDhjM2Q1ZmYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.Mns8seQdByC8v8KylmTc9-d5xvpncjo2VDdzDlBu80U">

- Auth 서버
<img width="852" alt="auth서버" src="https://github.com/user-attachments/assets/17100475-f3e7-4709-aa52-b142a71d9078">

- Gateway 서버
<img width="873" alt="gateway서버" src="https://private-user-images.githubusercontent.com/97074298/395463665-7753f71d-52a0-47cd-94b8-5b60ff75b04f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzQwOTU3NDAsIm5iZiI6MTczNDA5NTQ0MCwicGF0aCI6Ii85NzA3NDI5OC8zOTU0NjM2NjUtNzc1M2Y3MWQtNTJhMC00N2NkLTk0YjgtNWI2MGZmNzViMDRmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjEzVDEzMTA0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWZkYTEwOTE2MmM0OTRlNjE4NjFjZjgzZjkyYjA2MWE3NDVjYjRiNDg2MmM3NGNmNTliNTA0ZWZlZTBlZjUzNGUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.AGcjq3czcPTULDXl-SJQZJOOvAiL1gZAgK8BMli4NRQ">

- eureka 서버
<img width="873" alt="eureka서버" src="https://private-user-images.githubusercontent.com/97074298/395463465-6bc89867-155b-45f4-9c61-587821603967.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzQwOTU3NDAsIm5iZiI6MTczNDA5NTQ0MCwicGF0aCI6Ii85NzA3NDI5OC8zOTU0NjM0NjUtNmJjODk4NjctMTU1Yi00NWY0LTljNjEtNTg3ODIxNjAzOTY3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjEzVDEzMTA0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE4MDljOGMzNzI1NjA2OGFmNzYwYTEyMmIzNDBlNTQyYTU3OTVjZDdkYzM5ZTNjN2UyMGFhNjk2YWE1NWUyZjYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.sZ8Fk009T2Zsse62bppG838Gad41sv2pLb0U-LYm4us">

- config 서버
<img width="873" alt="config서버" src="https://private-user-images.githubusercontent.com/97074298/395463279-d31b3314-be54-4a8f-9015-b74023c5eb17.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzQwOTU3NDAsIm5iZiI6MTczNDA5NTQ0MCwicGF0aCI6Ii85NzA3NDI5OC8zOTU0NjMyNzktZDMxYjMzMTQtYmU1NC00YThmLTkwMTUtYjc0MDIzYzVlYjE3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjEzVDEzMTA0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWM3NGUxMzEzZWE4M2RlNWJlZGJhNjg4ZmE2ZWE4YjI2YmVhOTc3NjkwOGE4ZjE0M2EzNzljZWE2ZmU1MTI0ZTUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.N6DqG0Mjpb-bseZAuaM1rNGiE5RUgVW777MNgGS7p6U">



## Project Management

## 기능
### 김민정
#### 인프라
- Spring Cloud Gateway를 통한 로드 벨런싱으로 효율적인 요청 처리
- Eureka를 활용한 무중단 배포 구현
- Config Server를 이용한 서버별 설정 파일 자동 주입
#### 검색
- Logstash를 통해 데이터베이스의 변경 및 추가된 데이터를 Elasticsearch에 자동 반영
- Elasticsearch를 활용한 도서 검색 기능 구현
#### 리뷰
- 리뷰 조회, 등록 기능 구현
#### DBA
- 버전 별로 ERD와 DDL, DML script 관리

### 김민준
#### 장바구니
- 장바구니 담기, 조회, 삭제, 수정 구현
#### 포인트 정책
- 포인트 정책 조회, 수정 구현

### 김준엽
#### CI/CD
- NHN 클라우드 인스턴스 관리 및 L4 로드벨런싱으로 MSA 아키텍쳐 구조의 서버 환경 구성
- Github Actions를 이용하여 도커 이미지 자동 빌드 시스템 및 배포 환경 구성
- SonarQube 리포트 자동 생성
#### 주문
- 회원 주문 기능
- 비회원 주문 기능
- 주문 조회 기능
### 결제
- 토스페이먼츠 결제 시스템 연동

### 두영호
#### 쿠폰
- 쿠폰 정책 추가, 수정, 조회 기능 구현
- 쿠폰 템플릿 처가, 수정, 삭제, 조회 기능 구현
- 쿠폰 발급 기능 구현

### 정원석
#### 도서
- 도서api, 조회 기능 구현
#### 출판사
- 출판사 등록, 수정, 조회, 삭제 기능 구현
- 페이지네이션
#### 도서 상태
- 도서 상태 등록, 수정, 조회, 삭제 기능 구현
#### 카테고리
- 카테고리 상태 등록, 수정, 조회, 삭제 기능 구현
- 페이지네이션 구현

### 천보성
#### 회원
- 회원가입
- 주소지 관리
- 회원 관리
#### 인증
- 로그인 기능
- OAuth 2.0 적용(Payco)
#### 인가
- 권한에 따른 처리

### 한규빈
#### 도서
- 외부 api를 이용한 도서 정보 등록 기능 구현
- 도서 상세보기 기능 구현
- 도서 이미지 등록 기능 구현
- 관리자의 도서 등록, 수정 기능 구현




