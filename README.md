# tech-interview
preparation for technical interviews

## OS
프로그램
- 동작을 하지 않는 정적/수동적 개체

프로세스 
- 실행 중인 프로그램
- 동작을 하는 능동적 개체

스레드
- 하나의 프로세스 내에는 하나의 스레드가 존재
- 자원 소유의 단위 및 디스패칭의 단위

## WEB

### OSI 7계층
- 네트워크에서 통신이 일어나는 과정을 7단계로 나누어 표준화 한 것
- 통신이 일어나는 과정을 단계별로 파악할 수 있음
  - 1계층 - 물리 계층 : 하드웨어 장치를 통해 데이터 전송
  - 2계층 - 데이터링크 계층 : 물리계층을 통해 송수신되는 정보의 오류와 흐름을 관리
  - 3계층 - 네트워크 계층: 데이터를 목적지까지 가장 안전하고 빠르게 전달
  - 4계층 - 전송 계층 : 종단 간 신뢰성있고 정확한 데이터 전송 담당
  - 5계층 - 세션 계층 : 통신 장치 간 상호작용 및 동기화 제공
  - 6계층 - 표현 계층 : 데이터를 어떻게 표현할 것인지 정하는 역할
  - 7계층 - 응용 계층 : 사용자와 가장 밀접한 계층으로 인터페이스를 담당

### HTTP vs HTTPS
- HTTPS는 HTTP에 데이터 암호화가 추가된 프로토콜
  - HTTPS는 SSL(보안 소켓 계층) 인증서를 사용함으로써 서버와 브라우저 사이에 안전하게 암호화된 연결을 만들어줌

### RESTful API
- Representational State Transfer
- 자원의 이름으로 구분하여 자원의 상태를 주고받는 소프트웨어 개발 아키텍처 방식
- HTTP URI를 통해 자원을 명시하고, HTTP 메소드를 통해 자원에 대한 CRUD 동작을 적용함
- 클라이언트 플랫폼에 제약을 받지 않고 사용할 수 있음
