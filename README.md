# Study_Solidity

#### Solidity : 계약 지향 프로그래밍 언어, 블록체인의 스마트 계약을 작성할 때 사용된다.

#### EVM : Ethereum Virtual Machine, 솔리디티는 EVM 위에서 실행된다.

#### pragma solidity : 솔리디티 언어 버전을 명시해주어야 한다. 

#### contract 계약명 : 솔리디티 코드는 컨트랙트 안에서 실행되어야 한다. ( Java의 class선언과 유사하다.)

#### msg.sender : 현재 함수를 호출한 사람 (or 스마트 컨트랙트)의 주소를 가리킨다. -> 전역변수

#### mapping : 매핑은 기본적으로 키-값 (key-value) 저장소로, 데이터를 저장하고 검색하는 데 이용된다.
     ex) mapping (key => value) public/private 변수명;
#### require : 특정 조건이 참이 아닐 때 함수가 에러 메세지를 발생하고 함수의 실행을 멈추게 된다.
     ex) require(조건);
#### Contract Inheritance : 자식의 계약이 부모의 계약안의 함수에 접근가능하다.
     ex) contract 자식 in 부모 { 함수 }
#### import : 다수의 파일이 있고 어떤 파일을 다른 파일로 불러오고 싶을 때 사용한다.
     ex) import "불러올 파일";
#### now : 시간을 다룰 수 있는 단위계를 제공해준다. (1970년 1월 1일부터 지금까지의 초 단위 합)

#### ERC-20 : 대체가능한 토큰이며, 자체발행 및 유저에게 민팅해주는 부분을 수행하는데 사용하였다.

#### ERC- 721 : 대체 불가능한 토큰이며, 기부자에게 기부증서 NFT를 발급하여 주는데 사용하였다.



#### 0x7cC2a2C2a6f3287c426Dc0D813ac28dd9D947525 (0612 solidity contract address)
