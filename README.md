# Stocking Backend

## π Link

 - [Stocking RS](http://52.78.111.36:8080/)


<br>

## π κ°μ

Stocking νλ‘μ νΈ Backend λ ν¬μ§ν λ¦¬

<br>

## π λ¬Έμ

 - __API μΈν°νμ΄μ€ μ μμ__ : [Stocking μΈν°νμ΄μ€.xml](https://docs.google.com/spreadsheets/d/182aLbTaK65A3b54N6PWPdKt8OSbjQdrZvL_DBAccawo/edit?usp=sharing)  

 - __ER λ€μ΄μ΄κ·Έλ¨__ : [Stocking ERD](https://www.erdcloud.com/d/ZQjY97KMQrEthMPyn)  

 - __μ€ν λ¦¬λ³΄λ__ : [μΉ΄μΉ΄μ€μ€λΈ](https://ovenapp.io/view/DOhZ6TnDKWFjINtQKjnj2RAulxojOZCb#3QyvB)

 - __API λ¬Έμ__ : [Swagger](http://52.78.111.36:8080/swagger-ui.html)

<br>

## β μκ΅¬μ¬ν­ λΆμ (Backend)  

- λ‘κ·ΈμΈ κΈ°λ₯ κ΅¬ν (JWT + Spring Security, redis)  

- μ£Όμ API κ°λ° (JPA + mysql)
  - μ£Όμ μμΈλ³΄κΈ°
  - λ³΄μ  μ£Όμ μ‘°ν
  - μ£Όμ λ§€μ
  - μ£Όμ λ§€λ  

- μμ° API κ°λ° (JPA + mysql)  
  - μμ(λλ μ§μΆ) μ‘°ν
  - μμ(λλ μ§μΆ) λ±λ‘
  - μμ(λλ μ§μΆ) μμ 
  - μμ(λλ μ§μΆ) μ­μ 
 
- μλ² κ΅¬μΆ (AWS EC2, Docker)  

<br>

## π¨ κ΅¬μ‘°

```
bis.stock.back
βββ domain
β   βββ user
β   β   βββ User.java
β   β   βββ UserController.java
β   β   βββ UserService.java
β   β   βββ UserRepository.java
β   βββ stock
β   β   βββ Stock.java
β   β   βββ StockController.java
β   β   βββ StockService.java
β   β   βββ StockRepository.java
β   βββ ...
β       βββ ...
βββ global
    βββ config
    β   βββ WebSecurityConfig.java
    β   βββ ...
    βββ exception
        βββ SomeCustomException.java
```

<br>

## π» λͺλ Ήμ΄

```bash
$ git pull https://github.com/Beauty-inside/stocking-backend.git

$ ./gradlew
```
