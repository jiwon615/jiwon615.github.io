# 'I LOVE PET' 프로젝트

##### 프로젝트 바로가기 : <http://15.164.246.27:8080/>

##### 프로젝트에 대한 상세 설명 <https://jiwon615.github.io/>

##### 프로젝트 실제소스 : https://bitbucket.org/jiwonjung/ilovepet_project1/src/master/

```
일반사용자 ID : test1
일반사용자 PW : 1234

관리자 ID : admin
관리자 PW : 1234
```
---

### ==1. 프로젝트 요약==

```
• 프로젝트명: ILOVEPET 반려동물 쇼핑몰 구축 
• 개발기간 : 2019.11.11 ~ 2020.01.01
• 투입인원 : 1명 (개인)
• 프로젝트 소개 : 
• 개발목표 : 스프링 MVC 기반의 온전히 동작하는 웹서비스 구축 및 AWS 서버 배포

```

### 2. 개발환경
```
• 사용(개발) 언어 : JAVA8
• O/S
	- 개발환경 : Windows10
	- 운영환경 : Linux, ubuntu 18.04
• 웹서버 : Apache Tomcat 8.5
• 서버배포 : AWS EC2
• 사용(개발) 툴 : Spring STS, HeidiSQL, Visual Studio Code
• 프레임워크 : Spring Framework, MyBatis
• DBMS : MariaDB
• 웹 표준 기술  
	- JSP
	- HTML5 
	- CSS3 
	- Bootstrap4
	- JavaScript 
	- jQuery 
	- AJAX
	- EL & JSTL
• 참고: Udemy의 Spring Framework 제대로 활용하기 by ITGO
```

### 3. 서비스 내용
```
1. 로그인 및 회원가입
	• 유효성 검사
	• Bcrypt 비밀번호 암호화
    
2. 자유게시판, 무료분양
	• 조회수와 댓글 수 (트랜잭션 사용) 
	• Rest 방식의 댓글 (댓글 페이징)
	• 사진 업로드 및 사진 미리보기 
	• 페이징 처리 
	• 검색 기능 
    
3. 펫쇼핑몰
	• 카테고리에별 상품 리스트 
	•상품 재고 있을 시 장바구니  이용
	• 페이징  처리 및 검색기능
	• Rest 방식의 상품후기 및 별점 

4. 예외처리
	• AOP 사용 권환 확인

5. 마이페이지
	• 마이정보 변경
	• 장바구니 내역
	• 주문내역 및 주문 상세

6. 관리자
	• 상품과 관련된 CRUD
	• 전체 주문내역 확인(페이징)
	• 주문 내역의 배송상태 변경
	• 전체 회원 목록
```


### 4. 프로젝트 후기

**부족했던 점**
```
• 개발 경험 부족 
	• 프로젝트 기획부터 전반적인 개발 프로세스가 체계적이지 못했던 점
	• 버그 발견의 어려움 
• 멘토의 부재 & 1인 개발로 인한 시야의 협소합
• Daum 주소 API 연동한 것 이외에 다른 외부 API 연동 경험 부족

```

**배운 점**
```
• 프로젝트 완성 경험
	-혼자 많은 고민, 검색, 공부를 통해 단지 기술 습득 뿐 아니라 문제를 해결하는 방법, 접근법에 대한 내성 & 성숙도 증가
	- 웹개발에 대한 전반적인 흐름과 동작원리에 대한 이해를 하게 됨
• AWS EC2를 통한 서버 배포
• Spring Framework 사용법
```

**추후 발전해나가고 싶은 방향**
```
• Spring Security 적용
• 소셜 로그인 API 연동 시도
• 웹 보안 측면에 대한 공부
```
