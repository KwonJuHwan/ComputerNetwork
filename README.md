# ComputerNetwork
Using C++

주제: node간의 통신을 나타내는 프로젝트

배경: Network 환경에서의 Layer들에 대한 간략한 설명, protocol에 대한 개념(동기화, handshake, PDU, Flow control, Error Control, ARQ, FEC, CRC)
Internet Protocol(IP), Transport Layer(TCP, UDP), Application Layer(HTTP, STMP, DNS), Routing(Link State, RIP), LAN, WAN에 대한 개념을 학습하였다.
일상생활에서도 접할 수 있는 IP, TCP, UDP에 대한 개념을 배워서 흥미로웠고, 현재 구축되어있는 network가 어떻게 되어있는지를 대략적으로 알게되어서 매우 유익한 수업이었다.
Computer Network수업을 마치고 나서 느낀점은 취업을 하고, 프로그래머로써 직업을 갖고 작업을 하더라도, Network와 같은 실무에 직접적인 연관은 없지만, 이러한 개념들을 알고있으면 간접적으로
도움이 될 거 같다는 생각을 하게 되었다.

자세한 설명: sourcode1은 State변화와 flag를 이용한 두 node간의 message를 주고받을 수 있는 source코드이다.
sourcecode2는 sourcode1을 base로 하며 ACK state를 추가한 것이다. (ACK: 통신이 원활하게 이루어졌다는 것을 알리기 위한 장치)
(*word 문서 참고)
