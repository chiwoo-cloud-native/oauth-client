# O-Auth 
O-Auth 는 외부서비스의 인증 및 권한부여를 관리하는 범용적인 프로토콜입니다.

[O-Auth 참고](https://www.oauth.com/)


## O-Auth 주요 컴포넌트 

### Resource Owner
User, 즉 일반 사용자를 칭합니다. 
 
### Client
일반 사용자가 사용하는 애플리케이션

### Authorization Server
사용자가 앱을 통해 요청한 인증을 처리 하고 Access Token 을 발급 하거나, 
Token 만료 시점에 Refresh Token 을 재발급 해주는 역할을 합니다.

### Resource Server
RESTFul 을 예로 하자면, Client 가 헤더에 Access Token 을 포함하여 특정 자원에 대해 POST, GET, UPDATE, DELETE 요청을 하면 Resource Server 는 관련 처리를 제공 합니다.
 

## O-Auth Client 인증 프로세스
