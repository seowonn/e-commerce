## 개요
간단한 커머스 프로젝트

### Use

Java 17

Datebase :
  RDB : Mysql
  Non-Relation DBMS : Redis
  
Test : Junit5

Build : Gradle

Login Token : JWT

Test UI : Swagger

Spring, Jpa, Mysql, Redis, Docker, AWS


Goal : 셀러와 구매자 사이를 중계해 주는 커머스 서버를 구축한다.

## 회원 서버

### 공통
- [ ] 이메일을 통해서 인증 번호 수령 후 회원 가입

### 고객
- [ ] 회원가입
- [ ] 인증 ( 이메일 )
- [ ] 로그인 토큰 발행
- [ ] 로그인 토큰을 통한 제어 확인 ( JWT, Filter를 사용해서 간략하게 )
- [ ] 결제를 위한 수단
- [ ] 예치금 관리

### 셀러
- [ ] 회원가입


## 주문 서버

### 셀러
- [ ] 상품 CRUD

### 구매자
- [ ] 장바구니를 위한 Redis 연동
- [ ] 상품 검색 & 상세 페이지
- [ ] 장바구니에 물건 추가
- [ ] 장바구니 확인
- [ ] 주문하기
- [ ] 주문 내역 이메일로 발송하기
