---
title: "소설 악성코드를 읽고"
date: 2019-09-07 19:33:00 -0400
categories: Books
---

오늘은 악성코드: 소설로 배우는 해킹과 보안 이라는 책을 읽고 간단하게 느낀점과 배운점을 써보려고 한다.

소제목에 소설로 배우는 해킹과 보안이라는 문장을 보고 굉장히 끌려서 읽어 보게 되었다.

![bookcode1](http://dsol0115.github.io/dspage/assets/images/bookcode1.jpg){: width="300" height="450"}
![bookcode2](http://dsol0115.github.io/dspage/assets/images/bookcode2.jpg){: width="300" height="450"}

일단 책에 해킹과 관련된 용어들에 대한 기본적인 설명이 되어 있어서 확실히 해킹과 보안 분야에 관심이 생길 수 있도록 한다.

내용 면에서는 술술 익혀서 부담이 없다. 

몇가지 책에서 소개하는 용어들을 재밌어서 정리해보았다.

- 공용 무선인터넷 보안이 취약, 금융거래 하면 안됨
- 허니팟: 크래커가 들어올 수 있는 덫을 만드는 것. 해킹하기 쉬운 지점을 만들어 놓고 크래커가 다시 침투하길 기다리는 것 (공용 와이파이 이름을 다른 것으로 바꾸고 가짜 AP를 공용 와이파이인것처럼 위장. 크래커가 가짜API를 통해 무선 네트워크 접속 시도시 크래커의 컴퓨터에 악성코드 실행되도록)
- AP: Access Point 접근지점. 무선 네트워크를 연결하는 장치. AP 마다 이름과 암호화 설정 가능
- 제로데이 공격: 아직 공격을 막을 수 있는 패치가 나오지 않은 보안 취약점을 활용한 공격. 해당 취약점이 알려지기 전에 공격이 이뤄지기 때문에 막을 수 있는 방법이 없다.
- MAC 주소: 랜카드(NIC카드)에 부여되는 컴퓨터 고유의 주소. 물리적 주소.
- 백도어: 시스템 설계자나 관리자가 다른 PC에 대한 접근을 편하게 하기 위해서 시스템 설계할 때부터 만들어 놓은 빈틈이었는데, 보안 허점을 이용해서 시스템에 지속적으로 출입할 수 있는 통로를 만들어 놓는 프로그램. 프로그램이 설치되는 형태로 백도어가 유포되기도 하고, 기존 프로그램 또는 하드웨어를 변형시키는 방법으로 백도어를 이용할 수도 있다.
- 키로깅(KEY LOGGING):상대방이 키보드 치는 내용을 기록하여 빼내는 행위
- 버그 바운티(Bug Bounty): 버그+바운티(포상금)
- APT(Advanced Persistent Threat)공격: 특정한 대상을 계획적이고 지능적으로 공격하는 것을 말한다. 보통 "지능형 지속 공격"이라 해석
- 테더링:테더링으로 통신을 시작하다
- 사전 공격(dictionary attack): 비밀번호 크래킹 방법의 하나. 패스워드로 쓸 단어들을 사전 파일로 만들어서 그 안에 있는 단어들을 순차적으로 대입하여 비밀번호를 알아낸다. 비밀번호로 자주 사용되는 단어, 기호 조합 뿐만 아니라 사용자의 개인정보도 사전파일에 추가하여 공격하면 손쉽게 비밀번호를 획득할 수 있다. 단어 단위로 대입해서 비밀번호를 찾아서 속도가 빠르다.
- Active X 설치하라는 공격: 악성코드 설치됨
- 패스워드 알고리즘 알아내서 프로그램에 로그인
- 버퍼 오버플로우 공격: 버퍼(메모리의 저장공간) 오버플로우(넘친다). 버퍼를 넘치게 해서 공격자의 코드가 실행되게 만드는 공격. 버퍼 영역 다음에 오는 복귀주소를 조작해서 악성코드가 실행하게 만들수 있음.
- 방화벽: 외부 네트워크로부터 내부망을 안전하게 보호하는 역할
- 칼리 리눅스: 모의 해킹을 위해 개발된 리눅스 기반 운영체제로 안에 수많은 해킹 도구들과 설명서 들어있음. 
- 휴대폰 mac 주소를 무선 공유기 mac 주소로 속이는 arp 스푸핑을 통해 다른 사람 핸드폰을 해킹
- arp 스푸핑: 스푸핑(속이다) 스푸핑의 대상은 mac주소, ip주소, 포트 등 네트워크 통신과 관련된 모든 것이 될 수 있고 스푸핑을 속임을 이용한 공격을 총칭한다. 그 중 arp 스푸핑은 ip주소를 통해 mac주소를 찾는 프로토콜인 arp를 이용한 스푸핑 공격이다.
- 배쉬버그: 리눅스 및 유닉스 운영체제 시스템 인터페이스 중 하나로 이 기반의 시스템들이 비상 걸림.
- VMWARE: 로컬PC(HOST PC) 안에 또 다른 PC(GUES PC)를 가상으로 만드는 소프트웨어이다. GUES PC에서 악성코드를 실행하면 HOST PC 는 보호되기 때문에 악성코드를 분석하는 용도로도 많이 사용된다. 물론 VMWARE 에도 취약점이 존재하기 때문에 완벽하지는 않지만 위험성이 낮아짐.
- 크로스사이트스크립팅 공격(XSS): 간접적인 매체를 사용하여 사용자가 악성코드를 실행하게 만든다. 게시판 등에 스크립트로 작성된 악성 코드를 삽입하고 이를 사용자가 실행하게 유도하는 것.
- 좀비PC: 해커가 원격으로 제어할 수 있는 BOT 프로그램을 설치하여 해커의 명령대로 움직이는 PC
- SQL-injection: 로그인 폼에 논리적으로 항상 참이 되는 sql을 삽입하면 서버에서 인증값을 참으로 인식하여 인증을 우회할 수 있다.
- 덤프(dump): 저장 장치의 내용을 그대로 화면이나 프린터나 파일로 출력하는 것을 말한다. 디지털 포렌식 전문가들은 저장 장치를 덤프하여 이전 데이터를 복구한다.
- PGP(Prety Good Privacy): 암호화 기법을 이용한 보안 프로그램. 주로 이메일을 보낼 때 사용
- HTTPS는 HTTP over SSL의 약어로 암호화하여 HTTP 통신을 하는 것
- SSL 은 암호화 터널을 만들어서 데이터(패킷)을 터널로 주고받는 방식이다. 
- 루팅(Rooting): 최고 관리자 권한을 획득하는 것
- 대칭키 암호화 방식: 암호화 하고자 하는 단어를 대칭키 a로 암호화하면 abc가 나오는 방식. 다시 abc를 대칭키a로 복호화하면 원문이 나온다. 하지만 다른 사람에게 이 대칭키를 전달할 때 해커가 가로챌 수 있다는 문제점이 있다.
- 비대칭키 암호화 방식: 각각의 개인이 개인키가 있고 공개키가 있음. 공개키는 자물쇠, 개인키는 키라고 생각. 데이터 교환시에 서로의 자물쇠(공개키)만 교환 한 후 암호화 시켜서 다시 전송. 본인은 자신이 가지고 있는 개인키로 공캐기 열고 사용가능.
-ssl 통신방식: 대칭키와 비대칭키 암호화 방식의 장점을 결합한 것. 메시지 대신 대칭키를 자물쇠로 잠궈서 전송. 속도도 빠름. 대칭키를 안전하게 통신하면 그 다음에는 서로 대칭키로 암호화, 복화하면 됨.
(1. 공개키 교환, 2. 공개키로 암호화한 대칭키 교환 3. 대칭키로 암호화한 메시지 교환)
- heart bleed 공격: 1kbyte의 메시지를 64kbyte라고 속여서 전송하면, 서버가 63kbyte의 정보를 추가로 회신하는 취약점 활용
- 파일 업로드 취약점: 게시판 등에서 첨부 파일을 업로드해서 서버 내에서 명령을 실행할 수 있는 취약점.
- 웹쉘: 업로드 취약점을 이용해서 시스템에 명령을 내릴 수 있는 악성코드. 서버 쪽에서 구동할 수 있는 php, asp, jsp, cgi 등(서버 사이드 스크립트 언어)의 확장자를 지닌 파일이 업로드시 취약점있을 가능성.
- footprinting: 해킹의 사전 작업으로 타겟의 정보를 수집하는 것을 말함. 도메인 이름, ip주소, 운영체제 종류, dbms 종류 등
- IPS:Intrusion Prevention System) 침입 방지 시스템. 외부 네트워크로부터 내부 네트워크를 보호하는 기능을 가진 sw 혹은 hw. 
- IDS(Intrusion Detectino System) 침입 탐지 시스템. 침입에 대한 탐지 기능을 가진 sw 또는 hw를 말한다. 공격의 사후 탐지용으로 개발, 예방이나 차단은 불가능.
- 와이어샤크(wireshark): 네트워크를 통해 전송되는 데이터 단위를 패킷이라 하는데, 와이어샤크는 패킷을 분석하는 오픈소스 프로그램. 패킷에는 통신하기 위한 다양한 정보들이 포함되어 있음.
- ddos공격: 분산 서비스 거부 공격. 여러 개의 커뮾터를 이용해서 특정 시스템에 대량의 패킷을 동시에 보냄으로써 네트워크 성능 저하나 시스템 마비를 가져오게 하는 방법. 
- 웜(worm): 바이러스와 달리 독자적으로 실행되며 다른 실행 프로그램이 필요하지 않은 악성코드이다. 네트워크를 이용해 복사본이 전염되는 특징을 가지고 있다.
- 루트킷(rootkit): 해킹 대상자가 해킹 사실을 알아차리지 못하도록 하는 기술이 포함된 해킹 도구 모음


[책에 나온 용어 정리](http://dsol0115.github.io/dspage/assets/악성코드를_읽고.txt)

