Day_1 : 2022-12-28

교육원에서 USE CASE 다이어그램을 배우고 실습했다.
그간 RFP를 보면서 사용자 요구사항이 명확했던 문서만 보다가 관계되어있는 HIDDEN INFO를 찾고 그들의 관계를 설정하는게 쉽지는 않았다.
그리고 스터디 프로젝트를 위해 GIT HUB APP을 다운받아 TEST 해보았다.
SETTING과 경로설정이 아직까지 익숙하지 않지만 계속 하다보면 익숙해 지지 않을까 싶다.
Java 객체지향 프로그래밍 "객체지향 언어~메서드간의 호출과 참조"까지의 개념과 예제를 풀이했다.
참조형 반환타입이 조금 이해되지 않아서 반복해야 할 것 같다.
현재 2번째 반복하는 중이라 이전보다는 이해도가 좀 더 높아진 것 같지만 여러 예제를 풀다보면 모르는게 아직도 많다. 꾸준히 하는 게 답

Day_2 : 2022-12-29

데이터베이스의 분석 설계 과정에 대해서 배웠다.
요구사항 분석을 기반으로 "요구사항 정의서", "요구사항 명세서"라는 산출물이 나오고, 요구사항 분석을 기반으로 개념적 모델링을 실시하여 "ERD"라는 산출물이 나오게된다.
개념적 모델링은 어떠한것이 정답이라는 것은 아니지만 어떤 기능을 중점으로 두느냐에 따라 해석이 달라질 수 있고, 중요한 기능 같은 경우에는 독립적으로도 작성가능하다.
개념적 모델링은 변경될 수 있기 때문에 모든 내용을 종합하여 담아내기는 어렵다.
텍스트로 되어있는 요구사항 분석을 시각화하여 간단하게 표현한다.
이렇게 작성된 "ERD"를 기반으로 논리적 모델링을 진행 -> 테이블 명세서 작성 -> 물리적 모델링으로 데이터베이스의 분석 설계 과정을 거친다.
물리적 모델링에서는 실제 테이블의 이름 PK, UK, FK, 자료형 등 명확하게 작성하여 각각 맡은 테이블 개발을 진행하게 된다.
스터디에서 오늘 자바공부를 시작하게 되었고, 예제를 풀지 못해서 너무 당황스러웠다..
객체지향프로그래밍 관련 예제를 미친듯이 풀어봐야겠다.
주말동안 JS파일을 통합하여 계속해서 개념을 추가해야 겠다.
오늘을 기준으로 22년도가 2일밖에 남지 않았는데 사실 별 감흥이 없다.. 알고리즘 공부도 해야하는데.. 암튼 꾸준함이 답이니까 게속해보자 화이팅!

Day_3 : 2022-12-30

22년도 마지막 교육원 수업날이다. 오늘은 요구사항분석 단위평가를 보는 날이고 올해 마지막 평일이다. 만 나이로 시범운영 기간을 거쳐 반영된다고 하지만 그냥 나는 29이 되는 것 같다.
어젯밤 백두산이 25년도에 폭발할 거라는 것을 기사를 통해 접하게 되었고 너무 무섭고, 두렵고, 나에게 남은 시간이 3년이라는 생각이 들고..많은 생각이 들었다. 제발 무사하게 지나갈 수 있게 모든 신에게 빌어본다. 종교는 없지만 제발.. 인생을 더 보람차고 값지게 보낼 수 있는 시간을 주면 너무 좋을 것 같다. 

int 필요 시 parseInt(), Integer wrapper 객체 필요 시 valueOf()

논리적모델링 관계설정 및 해석

Day_6 : 2023-01-02

Notion으로 정리했던 JS 문서 통합작업 완료

Day_7 : 2023-01-03

요구사항확인 시험 확인하면서 연관, 포함, 확장관계에 대한 정의를 다시 한번 정리하게 되었다.
비기능적요구사항과 액터 구분을 다시 한번 정리해봐야겠다.
캠핑카 대여 관리 시스템 DB모델링 개념적 모데링과 논리적 모델링, 테이블 명세서, 물리적 모델링 작업 완료
JSP, SERVLET, JSP METHOD, JSP는 java파일을 생성

Day_8 : 2023-01-04

JSP 실행파일 생성 및 이클립스 구동과 관련되어 정리가 필요하다.

Day_9 : 2023-01-04

JSP문서에서 Java를 작성하는 방법 
jQUERY attr() & prop() 차이점, replace(), 공백확인, radio와 check box 체크 시 is 활용(여부확인)

취미 선택한 값을 출력할 때 취미는 여러개 값을 가질 수 있으므로, each와 this를 활용하여 값을 받아올 수 있다.
회원가입 페이지 유효성 체크 확인하기 #강사님 코드 확인
AJAX(비동기식 데이터 처리), XML, HTML & XML 차이점
JS 요소 접근방법 중  eq(n) : 요소의 n번쨰 index 요소를 반환
HTML요소를 동적으로 생성하는 방법 
HTML jQuery 동적 요소를 추가하고 마지막 합치는 작업을 위한 코드 복습

Day_10 : 2023-01-06

XML문서 작성 시 조건

1. 전체를 감싸는 루트가 필요 [ HTML문서 전체태그가 <HTML> ]
2. XML이라고 시작하는 문서는 공백이 들어갈 수 없음
3. 대소문자 구분

XML은 요소를 찾아야 함, JSON은 계층구조 접근
조합을 한 후 Body태그에 출력해야 함..? 동적 데이터
Ajax와 다른 점은 get 뒤에 이름을 명시해야함 (get json, get XML)
                                                 ㄴ JSON객체 내장함수..?
                                                
화면에 동적데이터 출력을 위한 구문 복습!
댓글구현화면 다시 만들어보기!
parents() : 찾고자 하는 요소를 매개변수로 작성 가능!
find() : 하위요소를 찾을 때  / 매개변수 작성 가능

동적인 데이터에 이벤트를 추가할 때 .on("이벤트", "대상", 함수) 작성

Day_13 : 2023-01-09

jQuery가 지원하는 속성 data- : 반복되는 data를 처리하기 위한 속성
- 뒤는 고정값이 아닌 식별하기 위한 값을 개발자가 직접 명시해야함
중복된 코드를 함수화처리

순서도의 마름모는 판단기호
JSP문서 실행 시 객체가 없는 거라면 "최초실행"
운영체제마다 확장자는 상이하지만 사용중인 WINDOW에서는 캡쳐참고
항상 브라우저의 주소 확인하는 습관 들이기!(URL)

Web.xml의 가장 중요한 건 웹 어플리케이션 서비스 시작 시 웹 서버가 읽어서 사용하는 파일

Web.xml의 위치는 src > main > webapp > WEB-INF > Web.xml : 브라우저로 직접 
ㄴ 요청이 불가능한 경로

실제 운영될 때는 WEB-INF에서 class파일이 생성되어 실행되어짐 : 클라이언트가 요청했을 떄 실행되는 서비스 경로 
D:\JSPCoding\.metadata\.plugins\org.eclipse.wst.server.core\tmp0\wtpwebapps\firstExample\WEB-INF\classes\example

경로변경 시 Java Build Path > Source 하단에 경로변경

서비스되는 문서는 결국 src/main/webapp/WEB-INF에 .class로 확장자 파일이 생성되기 때문에

MVC 패턴 : 유지보수에 용이하게 하기위함
Model : Java
View : JSP ()
Controller : Servlet : 궁극적인 목표는 controller 역할을 하기 위함

Java파일러 서블릿 class로 만들려면 extends HttpServlet class
단, 콘솔이 아닌 웹에서 실행하기 위함으로 main method는 작성하지 않아도 됨

==== 객체 단위의 입출력 ====

직렬화 : 객체단위의 입출력 시 객체가 갖고 있는 필드를 바이트 단위로 파일 형태로 변환
Object의 inputStream과 outputStream으로 바이트 단위로 변환 가능

단지, 직렬화를 위한 interface가 Serialiazble이다. 해당 인터페이스는 메서드가 없어 오버라이딩 할 게 없음

web.xml은 프로젝트 생성에 영향을 주기 때문에 꼭 확인해야함!

프로젝트 생성 시 context root가 프로젝트명과 동일할 뿐 실제 url에서 작성 시 context 명은 실제 저장 디렉토리명 src/main/webapp임을 잊지 말것

web.xml은 import가 불가능하므로 full name으로 작성해야함
servlet 주소를 줄 때 servlet과 servlet-mapping 두개가 필요함
                                          ㄴ 브라우저로 요청할 주소 작성(url-pattern))

servlet에서 객체생성을 하지 않아도 실행이 되어짐 왜냐면 default 생성자가 호출
servlet 컨테이너가 생성함

IoC라는 개념 (Stringframework 시 매우중요)
Inversion of Control
인스턴스를 생성하는 주최가 개발자가 아닌 다른 제3자가 생성

콜벡메서드

직접적으로 주소값을 명시하는 방법 : get
mapping하는 방법 : 1) annotation 2) xml파일 명시

servlet은 반드시 default 생성자를 반드시 명시해줘야함!

web.xml 설정하는 방법 중요중요!!
mapping은 하나의 프로젝트에 중복될 수 없음!
보통은 /로 시작함
Servlet 2.5까지 사용했지만 대형 프로젝트에서는 어노테이션이 아닌 web.xml 방식사용

servlet은 반드시 주솟값 설정해야함 이것을 mapping이라 하는데 방법은 2가지이다.
1) 어노테이션
2) web.xml파일

오류번호 404 : 파일이 없거나(경로 잘못 주었을 때), mapping주소가 잘못 되었을 때

Sevlet mapping하는 방법에 대해서 배웠다.

doGet() & doPost()

요청라인
요청헤더
요청바디

URL에 전달하고자 하는 정보를 포함해서 정보를 전달하는 방법
URL에서 ?를 만나면 method 방식 "get"
form 내에 name을 작성해야 DB에서 데이터 전송

GET으로 작성하면 URL에 포함해서 전송하겠다는 의미 (form태그, a태그, 브라우저에 직접 입력[url에 직접 입력])

POST 방식은 하단에 데이터 영역이 따로 되어 있음
post는 방식으로는 전송버튼을 만들 수 있음

서버가 요청을 받을 때의 메서드 : Request.getParameter("name");
String userName = request.getParameter("name");

HttpServletRequest class의 주요 메서드
1) getParameter(name) => 반환타입 : String
2) getParameterValues(name) => 반환타입 : 배열
3) getMethod()
4) 

HttpServletResponse

Day_14 : 2023-01-10
ajax는 개발자도구(Network)를 통해서 데이터 입력을 확인
jsp와 servlet은 이클립스의 콘솔에서 오류확인해야함

Ajax. Servlet, JSON, QueryString, XML, jQuery, mapping주소, 서블릿 하나에 mapping 여러개 가능(get, post)

Servlet 포워드
1) redirect 방법

Servlet이 2개 일 때 first servlet에서 바로  second servlet으로 가는 프로세스가 아닌 내부적으로 first servlet이 클라이언트에게 재 요청 후 클라이언트가 seceond servlet으로 요청하는 프로세스임을 기억

웹 브라우저에 재요청하는 방식이므로 값 전달 시 주의해야함(값을 직접적으로 보내지 못함)
[김정희] [오후 2:53]  $("input[type='button']")
[김정희] [오후 2:53] 이렇게 줄 수도 있는건가..?
[김정희] [오후 3:07] 제이쿼리 작성방법, form의 method와 action을 제이쿼리로 작성하는방법
