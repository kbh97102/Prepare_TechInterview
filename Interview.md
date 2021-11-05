## 인터뷰 준비하기


### 자기소개
회사분석을 해야함 어떤 서비스를 하는지 알아야함


### 자주 나오는 질문 준비
1. url을 주소창에 입력하면 일어나는 일들 
2. OSI 7계층


### Java 공부
1. 스레드 동기화 문제
   1. 데이터 무결성 보장안됨
   2. 루틴 관련 문제
   3. 스레드를 일정 이상 많이 만들면 성능 떨어짐
2. == 과 Equals의 차이
   1. 




### 내 플젝 질의응답 준비
왜 썻는지와 어려웠던 점은 항상 나옴 준비해야됨 
1. FaceDecorator
   1. CameraX를 사용한 이유?
      1. 카메라에서 받아온 이미지를 바로 후처리를 할 수 있기 때문에 사용했습니다.
      2. 그때 당시 최신 라이브러리라 함수의 이름이 바뀌는 등 어려움이 있었다. 등 어필
   2. ArCore를 사용한 이유, 어떻게 사용했는지
2. FBEye
   1. SSLSocket, TLSv1.2
      1. tls의 경우 버전마다 조금씩 다름 준비할 것
         1. 1.3안쓴이유 개발 당시 자바에서 알고리즘 지원을 안했음


### 비교 관련
==는 레퍼런스 비교 데이터 위치 비교 <p>
equals는 내부 데이터 비교 <p>
자바는 내부적으로 String pool을 가지고있음 그래서 리터럴로 생성된 변수는 비교해도 같은 값이라고 판단됨
