# RESTful

## REST란?

**RE**presentational **S**tate **T**ransfer의 약자로, API 설계의 한 패턴이다.  
REST는 Resource를 중심으로 HTTP Method를 이용하여 클라이언트, 서버간의 통신을 설계한다.

## REST의 6가지 특징

1. Uniform
 - URI로 지정한 리소스에 대해 통일성 있게 작업을 수행
2. Stateless
 - Session이나 Cookie의 정보를 별도로 저장하지 않음
3. Cacheable
4. Self-descriptiveness (자체 표현)
 - 메시지를 보고도 쉽게 API를 이해할 수 있는 구조
5. Client - Server 구조
6. 계층형 구조

## RESTful한 API를 만드는 방법

1. URI는 Resource(자원)을 표현해야한다.

- 자원은 동사보다는 명사을 사용하며 URI에는 표현을 포함하지 않는다.
- 복수형으로 사용할 것

```
// Bad
GET /users/get/2

// Good
GET /users/2
```
