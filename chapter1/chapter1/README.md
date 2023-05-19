# chapter1

인터넷이란?
- 인터넷의 구성요소 또는 네트워킹 인프라 구조 관점에서 기술할 수 있다.

> 구성요소로 본 인터넷

랩톱, 스마트폰, 태블릿, tv 등 이러한 장치를 host 또는 end system(종단 시스템)이라 부른다. <br>
이 종단 시스템은 통신 링크(communication link)와 패킷 스위치(packet switch)의 네트워크로 연결된다. <br>

통신 링크는 동축 케이블, 구리선, 광케이블, 라디오 스펙트럼을 포함한 다양한 물리 매체로 구성된다. <br>
각각의 링크는 다양한 전송률(transmission rate)를 가진다. 이 전송률은 초당 비트수를 의미하는 bps(bit per second) 단위를 사용한다. <br>

한 종단 시스템이 다른 종단 시스템으로 데이터를 가지고 있을 때 이 데이터를 세그먼트(segment)로 나누고 각 세그먼트에 헤더(header)를 붙인다. <br>
이렇게 만들어진 정보 패키지를 컴퓨터 네트워크에서 패킷(packet = segment + header)이라 부릅니다. <br>

패킷 교환기(스위치)는 입력 통신 링크의 하나로 도착하는 패킷을 받아서 출력 통신 링크의 하나로 그 패킷을 전달한다. 이 패킷 스위치는 많은 형태와 특징을 가지는데 <br>
가장 널리 사용되는 두 가지는. 라우터(router)와 링크 계층 스위치(link-layer switch)입니다.<br>

패킷이 송신 종단 시스템에서 수신 종단 시스템에 도달하는 동안 거쳐 온 일련의 통신 링크와 패킷 스위치들을 <strong>경로 (route or path)</strong> 라고 합니다.<br>

종단 시스템은 ISP (Internet Service Provider = packet switch + communication link)를 통해 인터넷에 접속한다. <br>
ISP는 CP(Content Provider)에게 인터넷 접속을 제공한다. <br>

인터넷은 종단 시스템을 서로 연결하므로 종단 시스템에 접속을 제공하는 ISP도 서로 연결 되어야한다. <br>

> 서비스 측면에서 본 인터넷




