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

커널
- 하드웨어 자원을 관리하는 관리자
- 프로그램이 작동할 수 있도록 물리적 장치를 배분


쉘
- 사람이 실행하는 명령어를 프로그램이 실행할 수 있도록 만들어주는 인터페이스


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

### TCP vs UDP
- TCP
  - 연결지향형 프로토콜
  - 통신 신뢰성 보증
    - 송신한 패킷의 순서와 수신한 순서가 다르면 순서를 바꿈
    - 일부 패킷이 유실될 경우 재전송함 
- UDP
  - 비연결형 프로토콜 
    - 연결을 지속하지 않고 일방적으로 데이터 전송 
    - 수신자가 정보를 받았다고 응답하는 기능이 없음
  - 저품질 but 속도가 빠름

### 3-Way Handshake
- TCP 통신을 이용하여 데이터를 전송하기 위해 네트워크 연결을 설정하는 과정
- 정확한 전송을 보장하기 위해 상대 컴퓨터와 사전에 세션을 수립하는 과정
- SYN
  - 연결요청 => 세션을 설정하는데 사용되며 초기에 시퀀스 번호를 보냄
- ACK
  - 보낸 시퀀스 번호에 TCP 계층에서의 길이 또는 양을 더한 것과 같은 값을 ACK에 포함하여 전송    
