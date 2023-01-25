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
[김정희] 
    $("input[type='button']") -> 이렇게 줄 수도 있는건가..?
    제이쿼리 작성방법, form의 method와 action을 제이쿼리로 작성하는방법

Servlet 포워드하는 방법

1) redirect ***
2) refresh
3) location [JS]

1~3번의 방법은 내부적으로 Fisrt-Servlet이 Client에게 Second-Servlet으로 재요청

4) dispatcher ***

내부적으로 First-Servlet이 Second-Servlet에게 바로 요청
따라서, First-Sevlet이 사용하던 request, response 객체를 그대로 사용가

Day_ : 2023-01-11

@WebServlet을 통한 초기값 설정하는 방법

Day_17 : 2023-01-13 

replace(/\s/g, "")=="")     =====> 해당코드 복습

2023-01-16

바인딩 ServletContext는 프로젝트당 1개이기 떄문에 참조변수명을 application으로 설정
해당 객체는 3개이고, 각 3개는 범위가 상이함
foward 후 set, get attribute로 속성을 받아옴

단순히 정보를 전달할 목적이라면 sendRedirect 속성을 보낸 후 출력하려면 request.dispatcher

단순이동인지, 아니면 다른 페이지에서 정보공유까지 해야하는지 고민해야함 /// forward와 Binding

서블릿은 JSP를 어떤 방식으로 받아올건지가 중요함!!!!

500번 에러는 서버측 오류이므로 이클립스 콘솔창 확인해야함(디버깅 할 때)

input type=hidden은 사용자로부터 값을 받지 않아도 서버측으로 값을 전달하고자 할 떄 사용하는 속성 "hidden" // 상세페이지 이동, 데이터 삭제 등

JSP지시자 종류

- page : JSP 페이지에 대한 속성 지정

contextType / pageEncoding
contextType로 응답할 문서가 JSON이면 무엇일까?
info 속성
import 속성
isErrorPage 속성 : error 발생 시 에러를 보여줄 수 있지만 errorPage는 에러발생시 해당 페이지로 이동 후 JSP 페이지를 기술하는 방법
isErrorPage 속성
기본값이 false 값이 true이면 내장객체라 부르는 exceptoin 변수를 사용하여 에러를 처리

- include : 태그 부분에 지정된 페이지를 정적으로 삽입
공통으로 사용할 JSP
정적데이터

- taglib

JSP의 내징객체 이지만 자료를 저장할 수 있는 객체가 out, session, application

pageContext는 JSP만 갖는 속성

JSP는 서비스된 내용이 서버에 계속해서 저장될 수 없으므로 다른 JSP에 정보를 전달해야함!!!!!!(GET, POST)

로그인 정보 및 게시판 > 상세페이지 등 페이지 이동 시 매번 페이지마다 값을 전달하기 용이하지 않기 때문에 session 을 이용하여 GetSession해서 속성값 읽어오면 됨

개발자도구 > Network > 해당페이지를 로딩하기 위해서 필요한 정보들을 확인할 수 있음

jsp와 jsp는 js객체를 활용 어차피 jsp는 화면에 보여주기 위한 것으로 버튼으로 이동함 (ex.location)
jsp에서 servlet은 response, request 객체 활용
servlet에서 다른 servlet으로 sendreDireict는 내부적으로 클라이언트에게 재요청을 진행함 따라서, sendreDireict setAttribute를 사용하지 못함

2023-01-17

@Controller / @RestController
Spring에서 컨트롤러를 지정해주기 위한 어노테이션은 @Controller와 @RestController
전통적인 Spring MVC 컨트롤러인 @Controller와 RESTful웹 서비스의 컨트롤러인 @RestController의 

차이점은 HTTP Response Body의 생성방식

@Controller의 역할은 Model 객체를 만들어 데이터를 담고 View 반환
@RestController는 단순히 객체를 반환하고 객체 데이터는 JSON 또는 XML 형식으로 HTTP 응답에 담아 전송

attr : 값이 정확한 대상들에 대해서 해당 함수로 대체
prop : 값이 정확하지 않는 대상들에 대해서 해당 함수로 대체 (selected, checked 등)

유효성 체크 시 select나 checkbox는 기본값이 있기 때문에 전체 빈칸일 경우라는 유효성 체크 시 제외

is : 여부를 확인하는 함수

JSON & XML

**공통점**
1. 데이터를 저장 및 전달하기 위해 고안
2. 계층적인 데이터 구조를 가짐
3. XMLHttpRequest 객체를 이용하여 서버로부터 데이터를 전송받음

**차이점**
1. XML은 배열을 사용할 수 없지만, JSON은 배열 사용가능
2. XML은 XML parse(), JSON은 JS의 표준함수인 eval()함수로 parsing

XML 예제
<dog>
    <name>별이</name>
    <family>웰시코기</family>
    <age>3</age>
    <weight>3.6</weight>
</dog>

JSON 예제
{
    "name" : "별이",
    "family" : "웰시코기",
    "age" : 3,
    "weight" : 3.6

}

JSON의 사용 범위
XML 문서는 XML DOM(Document Object Model)을 이용하여 해당 문서 접근
JSON은 문자열을 전송받은 후 해당 문자열을 바로 parsing하여 빠른 처리 속도를 가짐

XMLHttpRequest 객체를 활용 : Ajax, JSON, XML
 ㄴ 브라우저에서 제공하는 Web API 객체 HTTP 요청 전송과 응답수신을 위한 메서드와 프로퍼티 제공

getParameter : 반환타입 String

======= JSP 내장객체 =======

web.xml : 서버 구동 시 가장먼저 실행하는 파일이므로 전체 웹에 대한 제어가 필요할 때 사용 많이함


오류발생 시 명시할 페이지가 필요한 경우라면 
전체 JSP문서를 제어할 수 있음 작성하면 JSP문서마다 에러페이지 명시하지 않아도 됨
상태코드값 정의 (ex. 404, 500 등) *****
예외에 대한 타입 정의 (ex. NullPointerException 등)

JS는 싱글 thread 이지만 어떻게 Ajax 비동기 통신처리를 할 수 있을까?

Ajax
 ㄴ JS와 XMLHttpRequest 객체를 사용해서 클라이언트와 서버가 비동기 방식으로 통신하는 것

 JS > 브라우저를 제어하기 위한 내장객체

 1) location
 2) navigation
 3) history
 4) screen
 5) document

success????????
hidden???????? : 페이지와 다음 페이지 정보를 유지하기 위해서 사용함 input type="hidden"
상단 방법이 아니라면 

오류발생 시 delective 속성으로 isPageError로 이동할 페이지를 명시해도 되지만
만약, 전체 페이지에 대한 속성으로 제어하고자 할 땐 web.xml에 작성하여 상태코드값으로 이동할 페이지를 생성하여 작성하는 것이 좋다.

에러페이지 우선 순위
1. page 디렉티브의 errorPage 속성
2. JSP 페이지에서 발생한 예외 타입이 WEB.XML파일의 <EXCEPTION-TYPE>
3. JSP 페이지에서 발생한 예외 타입이 WEB.XML파일의 <ERROR-CODE>
4. 웹 브라우저가 제공

servletContext : 하나의 프로젝트에 1개 생성
servletConfig(interface) : 하나의 servlet에 1개 생성
ㄴ servlet의 기본속성을 얻을 수 있음

[ JSP 내장객체 ] 
pageContext : JSP 페이지당 1개씩 자동으로 생성되는 객체

JSP 페이지에 대한 정보를 저장하고 있는 객체

다른 내장 객체 구하기   ==> method (내장객체 주소를 얻을 수 있는 메서드)
속성처리(바인딩)        ==> method [page < request < session < application]
페이지의 흐름 제어하기   ==> method
에러 데이터 구하기


내장객체를 사용하고 싶을 때 pageContext를 전달
pageContext의 mehtod : include & forward

==============================================================================

servletConfig -> JSP : config
servlet 1개당 만들어짐

==============================================================================

상태 정보 유지 기술

비연결성과 무상태를 꼭 기억하기

사용자 측에 정보를 저장 : cookie
서버 측에 정보를 저장 : session

하단 3가지는 정보를 저장해두었다가 필요할 떄 접근해서 정보를 가져올 수 있는 객체(영역객체)

영역객체만이 속성을 설정 할 수 있고, 설정한 값을 반환받을 수 있음

1. ServletContext (jsp : application)
   ㄴ application(dynamic project) 내가만든 jsp, servlet 전체 접근 가능

2. HttpSession (jsp : session)
   ㄴ 

3. HttpServletRequest  (jsp : request)
   ㄴ 내가 요청/응답한 페이지까지이지만 forward하면 내가 forward한 페이지까지 유효

4. page (pageContext) ==> JSP만 갖는 속성
   ㄴ

scope : 유효범위 => 속성을 사용할 수 있는 범위가 어디까지 인지

scope의 기능 

1) MVC패턴 중 Model과 View의 데이터 정보 전달

2023-01-18

*** <%= %> 표현식을 대신해서 사용하는 표현언어 ***
표현언어 : JSP 페이지에서 이용되는 여러 외부 데이터 객체를 쉽고 간편하게 참조하기 위한 언어
 ㄴ 표현식을 대신함
<%= %>인 표현식 대신에 사용하거나 내장객체 또는 액션태그 저장된 자료를 쉽게 참조

표현언어가 갖는 내장객체 : request.getParameter

** param **

${} => 공백허용하지 않음

${ param userid }
${ param ['userid'] }
${ param ["userid"] }

jsp 내장객체 속성설정 가능 객체 3개 생각해내!!!!!!!!!!!!!!!!

1) application (ServletContext)
2) session (HttpSession)
3) request (HttpServletRequest)
4) page (Context Page)

표현언어는 스트립트 요소(스크립트릿, 표현식, 선언부)에는 작성불가능
                        <% %>    <%= %>   <%! %>

표현언어는 JSTL과 사용할 떄 효율적!

표현언어는 속성에 접근해서 출력할 떄 용이!

표현언어의 연산자 중 가장많이 활용하는 연산자 : empty! (값이 있는지 없는지 확안)
만약, 값이 null이라면 logic 처리를 통해 값을 가져와야함 (default return value = true)

2023-01-20

Java Calendar에 정의된 필드

-- 날짜 --
YEAR
MONTH
WEEK_OF_YEAR
WEEK_OF_MONTH
DATE
DAY_OF_MONTH
DAY_OF_YEAR
DAY_OF_WEEK
DAY_OF_WEEK_IN_MONTH

-- 시간 --
HOUR
HOUR_OF_DAY
MINUTE
SECOND
MILLISECOND
ZONE_OFFSET
AM_PM

JSP getParameter()와 getAttribute()의 차이점

getParameter() retrun 타입 : String
getAttribute() return 타입 : Object

executeQuery(String sql)
resultSet 객체를 반환하는 SQL문에 사용되고, SQL문을 실행한 다음 레코드셋을 반환하는 경우를 의미하며 SELECT문인 경우에 사용되어진다.
SQL문에 해당하는 레코드가 없는 경우에는 레코드 셋은 NULL값을 갖는다.

쿼리문 insert는 ResultSet이 불필요하다 왜일까?

executeQuery : 수행결과로 ResultSet 객체의 값을 반환
               select 구문을 수행할 때 사용되는 함수

executeQuery 함수를 사용하는 방법 -> resultSet 객체에 결과값을 담을 수 있음

pstmt = con.preparedStatemetn("SELECT ID, NAME, FROM SAMPLE_TABLE");
ResultSet re = pstmt.executeQuery();

while(rs.next()) {

   System.out.println("ID = " + rs.getInt(1) + ", NAME = " + rs.getString(2));
}

ID = 100, NAME = Jerry

Query문 실행 시 ExecuteQuery : select 구문 수행 시 사용되는 함수
               ExecuteUpdate : select 구문을 제외한 다른 구문 수행시    사용되는 함수 (return 타입 : int타입의 값을 반환)

2023-01-25

dao : 데이터베이스 연동을 위해서 만든 class(일반적으로 개발자들이 인지함)

수정과 삭제 메서드의 반환형이 int라면 틀이 비슷하게 감

public Board boardSelect(int dNum) -> 상세페이지 board의 번호를 매개변수로 가져감

form에다가 read only를 작성하면 값을 입력할 수 없지만 DB전송은 가능

request.getContextPath() -> WEB.XML에 작성한 코드를 근거로 시작페이지를 찾음
WEB.XML에 명시된 시작페이지가 없다면 오류발생

시작페이지 이름은 거진 index, default, main이름을 사용

forward : url 값이 변경되지 않음
sendRedirect : url 값이 변겯되어짐

입력화면에서 입력한 값을 가지고 servlet --> service --> DAO

수정작업은 기존의 글을 보여주어야 하기 때문에 해당하는 글 번호를 기준으로 DB에서 가져와야함

게시판 수정 LOGIC과 흐름 다시 공부하기!

TABLE이 변경되면 VO가 바뀌고, VO가 변경되면 DAO가 변경되고 DAO가 변경되면 입력화면이 변경되어진다.