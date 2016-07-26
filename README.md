# AMGLogger
HTTP 프로토콜을 지원하는 모든 네트워크 환경에서 손쉽게 로그를 저장하고 어디서든 볼 수 있도록 하는 프로젝트입니다.

## 이 프로젝트는 다음과 같은 이유로 설계되었습니다.  
* 제작자의 포트폴리오
* HTTP 프로토콜을 통한 손쉬운 로깅
* Web, App 등 어디서든 로그를 확인할 수 있음
* Web, App 등에서 서버로 메시지를 보내 명령 수행 (예정)

## 사용예시
서버쪽에서 로그를 적으려면 amglogger.com/APIKEY(예시)로 category와 message를 담아서 POST Request를 한다.

반대로 Web, App 등에서 읽으려면 amglogger.com/APIKEY?category=user&include=hack(예시)로 GET Request를 하자.  
정렬 기준, 불러올 갯수, 포함된 문자열 등을 인자로 정할 수 있다.

(예정)Web, App에서 서버로 명령을 내리려면 amglogger.com/request/APIKEY(예시)로 command를 담아서 POST Requset를 한다.  
서버는 이를 받아와서 command에 해당하는 명령을 수행한다.
