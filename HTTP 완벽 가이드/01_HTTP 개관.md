### 1.1 HTTP: 인터넷의 멀티미디어 배달부
    HTTP는 웹서버로부터 받아온 대량의 정보를, 사용자 PC에 설치된 웹브라우저로 옮겨줌
    데이터 손상 없음을 보장
  
### 1.2 웹 클라이언트와 서버
    웹서버는 인터넷의 데이터를 저장하고, HTTP 클라이언트가 요청한 데이터를 제공
    클라이언트 -> 웹서버 : HTTP요청
    웹서버 -> 클라이언트 : HTTP응답
    HTTP요청 + HTTP응답 = HTTP트랜잭션
  
 ### 1.3 리소스
    웹서버는 웹 리소스를 관리하고 제공
    웹 리소스는 웹에 콘텐츠를 제공하는 모든 것
    어떤 종류의 콘텐츠 소스도 리소스가 될 수 있음
        - 1.3.1 미디어 타입
        : MIME타입(데이터 포맷 라벨)
        : 클라이언트의 HTTP요청에 웹 서버가 HTTP응답을 하기 전, 웹 서버는 모든 HTTP객체 데이터에 MIME타입을 붙임 
        -> 웹브라우저(클라이언트)는 MIME타입을 보고 자신이 다룰 수 있는 객체인지 확인할 수 있음
        : 주타입/부타입 (ex)image/jpeg, image/gif 등
        -1.3.2 UR*
        : 정보리소스를 고유하게 식별하고 위치를 지정
        : URL과 URN 두가지 종류
        -1.3.3 URL
        : 특정 서버의 한 리소스에 대한 구체적인 위치를 서술
        http://www.oreilly.com/index.html : 오라이리 출판사 홈페이지의 URL
        http://www.yahoo.com/images/logo.gif : 야후! 웹 사이트 로고의 URL
        http://www.joes-hardware.com/inventory-check.cgi?item=12731 : 물품 #12731의 재고가 있는지 확인하는 프로그램에 대한 URL
        ftp://joe:tools4u@ftp.joes-hardware.com/locking-pliers.gif : 비밀번호로 보호되는 FTP를 통해 locking-pliers.gif 이미지 파일에 접근하는 URL
        :스킴(프로토콜, 주로 http://) + 서버의 인터넷 주소(www.joes-hardware.com) + 웹 서버의 리소스(/specials/saw-blade.gif)
        -1.3.4 URN
        : 리소스의 위치에 영향 받지 않는 유일무이한 이름 역할
        : 위치 독립적, 리소스를 여기저기로 옮기더라도 문제없이 동작
    
### 1.4 트랜잭션

    
