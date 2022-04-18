# Study_Solidity

#### msg.sender : 현재 함수를 호출한 사람 (or 스마트 컨트랙트)의 주소를 가리킨다. -> 전역변수

#### mapping : 매핑은 기본적으로 키-값 (key-value) 저장소로, 데이터를 저장하고 검색하는 데 이용된다.
     ex) mapping (key => value) public/private 변수명;
#### require : 특정 조건이 참이 아닐 때 함수가 에러 메세지를 발생하고 함수의 실행을 멈추게 된다.
     ex) require(조건);
#### Contract Inheritance : 자식의 계약이 부모의 계약안의 함수에 접근가능하다.
         ex) contract 자식 in 부모 { };
