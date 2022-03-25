# 스프링부트 이메일 보내기

### 1. 의존성
```gradle
implementation 'org.springframework.boot:spring-boot-starter-mail'
```

### 2. EmailUtils.java 만들기
### 3. EmailController.java 만들기
### 4. application.properties 생성
```properties
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=아이디
spring.mail.password=비번
spring.mail.properties.mail.smtp.starttls.enable=true
spring.mail.properties.mail.smtp.starttls.required=true
spring.mail.properties.mail.smtp.auth=true
```
### 5. 구글 보안 수준이 낮은 앱의 엑세스
 - 주의할점은 2단계 인증이 되어있으면 안됨
 - Google계정관리 - 보안 - 보안 수준이 낮은 앱의 엑세스 - 사용설정하기

### 6. 실행하기
http://localhost:8080/sendmail
