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
### 5. 실행하기
http://localhost:8080/sendmail