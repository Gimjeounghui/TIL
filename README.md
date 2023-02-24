공부를 시작하기 전

요즘 개발의 postion이 Front-end 와 Back-end로 나뉘어지는데 이전에는 Full Stack (CSS를 제외한 Front 단 [ js/jQuery ] 부터 Back단 [ Java Business Logic & DB ]) 이였다.
최근에는 view.js, react, Angular로 알 수 있듯이 Front와 Back이 명확하게 갈리는 추세

js(javascript) = jquery : javascript를 간결하게 쓸 수 있는 언어

“프론트언어”

js를 기반으로 만들어진 언어

react 
view
angular

프로젝트 환경설정 하는 Framework

- Spring
- Springboot
- 스트럿츠

SpringFramework 경량화 -> Springboot

#사용하는 Framework가 다름
#전체적인 프로젝트 구조
#어떤방식으로 환경세팅
#Java & Javascript 어떻게 구조화 시킬건지

유니코드

MyBatis/ibatis vs jpa 
sql을 연결하는 프레임워크


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

22년도 마지막 교육원 수업날이다. 오늘은 요구사항분석 단위평가를 보는 날이고 올해 마지막 평일이다.
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
JS 요소 접근방법 중  eq(n) : 요소의 n번쨰 index 요소를 반환
HTML요소를 동적으로 생성하는 방법 
HTML jQuery 동적 요소를 추가하고 마지막 합치는 작업을 위한 코드 복습


Day_10 : 2023-01-06

WEB.XML은 웹 어플리케이션 서비스 시작 시 웹 서버가 읽어서 사용하는 파일

WEB.XML의 위치는 src > main > webapp > WEB-INF > WEB.XML : 브라우저로 직접 요청이 불가능한 경로

실제 운영될 때는 WEB-INF에서 class파일이 생성되어 실행되어짐 : 클라이언트가 요청했을 떄 실행되는 서비스 경로 
D:\JSPCoding\.metadata\.plugins\org.eclipse.wst.server.core\tmp0\wtpwebapps\firstExample\WEB-INF\classes\example

경로변경 시 Java Build Path > Source 하단에 경로변경

서비스되는 문서는 결국 src/main/webapp/WEB-INF에 .class로 확장자 파일이 생성되기 때문에

XML문서 작성 시 조건

1. 전체를 감싸는 루트가 필요 [ HTML문서 전체태그가 <HTML> ]
2. XML이라고 시작하는 문서는 공백이 들어갈 수 없음
3. 대소문자 구분

XML은 요소를 찾아야 함, JSON은 계층구조 접근
조합을 한 후 Body태그에 출력해야 함..? 동적 데이터
Ajax와 다른 점은 get 뒤에 이름을 명시해야함 (get json, get XML)
                                                 ㄴ JSON객체 내장함수..?

parents() : 찾고자 하는 요소를 매개변수로 작성 가능!
find() : 하위요소를 찾을 때  / 매개변수 작성 가능

동적인 데이터에 이벤트를 추가할 때 .on("이벤트", "대상", 함수) 작성


Day_13 : 2023-01-09

data- : jQuery가 반복되는 data를 처리하기 위해 지원하는 속성이며, - 뒤는 고정값이 아닌 식별하기 위한 값을 개발자가 직접 명시
중복되는 코드를 함수화처리
순서도의 마름모는 판단기호
JSP문서 실행 시 객체가 없는 거라면 "최초실행"
항상 URL 확인하는 습관 들이기!

Java파일로 Servlet 생성 시 HttpServlet 상속받아야 하고, console이 아닌 Web에서 실행하기 위한 것이므로 main method는 작성하지 않아도 됨 

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


Day_20 : 2023-01-16

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


Day_21 : 2023-01-17

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
<Framework>
    <name>Spring</name>
    <version>3.0</version>
</Framework>

JSON 예제
{
    "name" : "spring",
    "version" : 3.0
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


Day_22 : 2023-01-18 

*** <%= %> 표현식을 대신해서 사용하는 표현언어 ***
표현언어 : JSP 페이지에서 이용되는 여러 외부 데이터 객체를 쉽고 간편하게 참조하기 위한 언어. 표현식을 대신함
<%= %>인 표현식 대신에 사용하거나 내장객체 또는 액션태그 저장된 자료를 쉽게 참조

표현언어가 갖는 내장객체 : request.getParameter

** param **

${} => 공백허용하지 않음

${ param userid }
${ param ['userid'] }
${ param ["userid"] }

jsp 내장객체 속성설정(범위) 가능 객체 3개 생각해내!!!!!!!!!!!!!!!!

1) application (ServletContext)
2) session (HttpSession)
3) request (HttpServletRequest)
4) page (Context Page) -- JSP 내에서만 사용할 수 있는 Scope

표현언어는 스크립트 요소(스크립트릿, 표현식, 선언부)에는 작성불가능
                        <% %>    <%= %>   <%! %>

표현언어는 JSTL과 사용할 떄 효율적!

표현언어는 속성에 접근해서 출력할 떄 용이!

표현언어의 연산자 중 가장많이 활용하는 연산자 : empty! (값이 있는지 없는지 확안)
만약, 값이 null이라면 logic 처리를 통해 값을 가져와야함 (default return value = true)

속성 : 공유되는 데이터

표현언어는 속성들을 출력하기 위한 구문

표현언어 내장 객체

표현언어는 Version up이 되면서 생성자도 설정할 수 있지만 원래는 출력용도 !!

표현언어는 Null에 대해서는 브라우저에 나오지 않음

***********중요중요***********

EL에서 객체 접근
${<표현1>.<표현2>} 형식 사용

<표현1>은 <값1>로 변환한다.

<값1> 자리에 Map, List & 배열, 객체가 오면
<값2> : Map 타입의 <값2>는 key값에 해당하는 value값을 찾아 출력
        List & 배열 : 원소를 찾아 출력
        객체(VO) : field명을 주면 getter(접근자)를 찾아와서 출력


Day_24 : 2023-01-20

getParameter() retrun 타입 : String
getAttribute() return 타입 : Object

executeQuery : select 쿼리문 / 수행결과로 resultSet 객체의 값 반환 / resultSet 객체에 결과값을 담을 수 있음


Day_29 : 2023-01-25

forward : url 값이 변경되지 않음
sendRedirect : url 값이 변겯되어짐

Java > dao class : 데이터베이스 연동을 위해 만든 class

form 태그에 read only 작성 시 값 입력은 불가능 하지만 DB전송은 가능

request.getContextPath() -> WEB.XML에 작성한 코드를 근거로 시작페이지를 찾음 / WEB.XML에 명시된 시작페이지가 없다면 오류발생
시작페이지 이름은 index, default, main이름을 사용

java Timestamp : 현재시간을 구할 수 있는 class (import)

Date와의 차이점 : Date는 Millisecond까지 구할 수 있지만 Timestamp는 Milliseconddp Nanosecond까지 구할 수 있다.

사용방법 
- Timestamp timestamp명 = new Timestamp(System.currentTimeMillis());
- Timestamp timestamp명 = new Timestamp(System.nanoTime());

Timestamp 역시 Date처럼 SimpleDateFormat을 적용할 수 있는데 Format을 설정한 뒤에 적용해 주면 동일하게 적용되는 것이 보인다.

참고 : https://wakestand.tistory.com/396

JDBC > ResultSet은 3개의 Section
bof & date & eof

session은 브라우저당 한 사용자로 봄

getAttribute() : return type Object;
getParameter() : return type String;


Day_30 : 2023-01-26

Http 프로토콜의 특징 : 비연결성 & 무상태성

클라이언트와 서버의 통신 정보가 유지되지 않고, 서버가 계속해서 정보를 갖고 있지 않기 때문에 페이지에서 페이지 사이의 상태정보를 유지하기 위한 방법

상태정보를 유지하기 위한 방법 4가지

- hidden 속성 : 실제 사용자한테 값을 받지는 않지만 서버측에 전달, 메서드 방식이 post일 때 사용
- method > get  : Query String 작성( name = value )
- Cookie : 사용자측에 정보를 남기는 기술 
- Session : 서버측 메모리에 정보를 남기는 기술


Cookie

- 사용자 측에 저장되기 때문에 사용자가 삭제할 수 있음
- JS & Server 에서도 쿠키 사용 가능
- 사용자가 응답(response)할 때 같이 응답객체와 같이 보냄
- 유효기간 미 설정 시 브라우저 종료까지로 유효시간 설정
- cookie 생성방법 [ 파일로 생성 & 브라우저 메모리에 생성 ]

Session

- session 객체를 얻기 위한 방법 2가지 [ getSession() / getSession(true) ]
- session의 id값으로 사용자를 식별할 수 있음
- logic 처리완료된 servlet 정보를 JSP에 전송할 때 요청객체에 속성을 담은 후 "request.dispatcher"
- insert 후 List 화면으로 이동 시 "sendRedirect"

-- Servlet 포워드 방법 -- 

- sendRedirect ***
- Refresh
- location
- Dispatcher ***

JSP 태그 

- 스크립트 태그
- 액션태그 (JSP 컨테이너 제공)
- 커스텀태그 (JSTL & 개발자가 만든 커스텀 태그)

JSTL

- Core (c) ***
- XML
- Internationalization **
- Database
- Functions (fn) *** [ Functions만 ${}안에 작성 ]
- if는 단일한 문장이라서 else가 없음 (else 필요 시 choose)

URL 패턴의 종류는 3가지

- 정확한 이름까지 일치하는지
- 디렉토리까지만 일치하는지
- 확장자만 일치하는지
  ㄴ 모든 파일에 동일한 servlet을 실행하고 싶을 떄 파일의 확장자를 일치시킴

WhiteSpace : 공백에 관련된 오류!
속성과 속성 사이의 공백이 하지 않았을 때 대부분 발생


Day_34 : 2023-01-30

데이터베이스에서 Connection 객체를 얻는 작업이 소요시간이 가장 오래 걸림

설정파일 작성 시 
- 이클립스 > Server > context.xml 파일에 작성 X
- File > Open File > conf > context.xml 작성 O 
- 두 파일은 자동 동기화가 되지 않고, java단에서 서버를 삭제 후 재설치 할 수 있기 때문에 작성해둔 내용이 사라질 수 있음 

Connection Pool

- 클라이언트의 요청이 있을 때 연결되는 것이 아닌 미리 연동해두고 작업이 완료되면 해지하는 것이 아닌 다시 Connection Pool에 반환
- 성능을 향상 시킬 수 있음
- 이러한 기능을 수행하기 위해서 필요한 jar파일을 Tomcat 7이상 부터는 lib에 파일이 존재

DataSource

- Connection Pool을 관리하는 목적으로 사용하는 객체 / DataSource 객체를 통해서 Connection을 획득
- 기본정보를 서버의 설정파일(Context.xml) 작성 후 DataSource 객체로 얻어옴 
- java 단에 데이터베이스정보를 작성한 것이 아니기 때문에 lookup() 메서드 사용

싱글톤패턴! 

- 다른 클래스에서 인스턴스를 생성할 수 없어야 하기 떄문에 생성자 접근제한자를 private
- 자신의 타입으로 정적 필드와 메서드가 필요
- 하나의 인스턴스를 만드는 것

contextPath().. 다시공부..
루트는 하나의 프로젝트 안에 한개만 존재해야함

Filter

-

== 부트스트랩 ==

== jsp & 표현언어 & jstl 공부 ==


Day_35 : 2023-01-31

어떤 서브 컨트롤로 가야할 정보가 없으니 핸들러로 이동 후 서브컨트롤러에서 서비스 dao
dao는 결과값을 service subcontroller(class로 만들었음)subcontroller의 반환은 온전한 반환값이 아닌 물리적인 경로가 아님 따라서 뷰리솔브에 가서 온전한 경로를 만든 후에 포워드해야함

요청한 종류에 따라 처리할 내용은 HandlerMapping에 작성예정

Day_36 : 2023-02-01

trimDirectiveWhitespaces : html 문서로 보여줄 떄 page 디렉티브 영역이 빈줄로 보여지는걸 없애기 위한 코드

Day_38 : 2023-02-03

사용자와 관리자 페이지가 따로 구현되어야함
추후 구축에는 사용자 테이블에서 관리자 매핑 정보가 들어가면 안됨
사용자는 list, Detail 페이지가 필요함
따라서, 사용자는 관리페이지에 접속할 수 없고, 관리자는 사용자페이지로 접근할 수 없다

Spring Framework, Spring Boot FrameWork

Spring Framework : 디스패처, 핸들러매핑, 인코딩, 필터, 뷰 만들지 않고 로직에만 집중할 수 있는 프레임워크

현재 공부하는 DispatcherServlet -> HandlerMapping -> 


delete method 
request.getSession();
request.getSession(true);
request.getSession(false); --> session 객체가 존재한다면 기존의 담아둔 session객체에서
getId()해서 가져옴

re.next 하지않고 바로 vo에 담아서 return

id과 pw가 일치하지 않으면 null값 제어
아이디랑 비밀번호를 확인하는 메서드에서 반환하는 타입을 vo로 설정해도 됨

jsp는 session이 내장되어 있기 때문에 기본값을 true에서 false로 변경

session객체는 java단에서 필요할 때 생성

jsp문서에 session객체를 따로 생성할 필요는 없음
이유는 jsp 문서는 session 객체를 내장하고 있기 때문에 default 값으로 true를 가지고 있음
따라서, jsp문서에서 session 객체 가져오지 않으려면 false값을 지정해야함

회원관리 테이블 설정 시 칼럼으로 수정날짜를 추가할 수 있음
ex> 가입 후 x개월 후 비밀번호 변경 alert
비밀번호를 변경 후 수정날짜가 업데이트 되면서 등록일이 수정일자로 변경되어짐

id가 email 주소가 될 수도 있는 부분 염두해두기

디스패처는 요청에 대한 처리를 할 수 있는 클래스 정보가 없기 때문에 HandlerMapping으로 감

관리자페이지에서 중요한 기능은 검색할 수 있는 기능 구현(날짜, 원하는 정보에 대한 검색, 사용자 검색)

1. 회원정보는 쿼리에서 마스킹 처리 후 가져감
2. java단에서 마스킹 처리를 함

db 마스킹 처리


Day_40 : 2023-02-05

절대적 경로 설정, 상대적 경로 설정(지향)

Node.js

MyBatis : 서버 설정을 위한 xml파일을 따로 작성해놓은 것 (SpringBoot)

AJAX ( Asynchronous JavaScript and XML ) 비동기 통신 처리

- JavaScript로 원격지로부터 데이터를 읽어오는데 필요한 처리 기술들의 집합체
- XMLHttpRequest 객체는 서버측 JavaScript와 통신하기 위한 Ajax 핵심 기술로 AJAX의 특징인 비동기성을 가능하게 한다.
- XMLHttpRequest 객체로 서버측으로 부터 받아온 데이터로 client 요청 페이지를 Update
- 서버로부터 받아온 데이터를 페이지에 반영해 주기 위해 HTML 태그 요소를 제어하는 DOM 객체에 대한 처리 및 CSS 처리의 병행을 보여줌
- 전체 페이지 로딩 없이 문서 내 특정부분만 업데이트 하는 다이나믹 웹 페이지 기술
- client가 요청한 정보를 변경하려면 서버에 페이지 업데이트 요청을 하는데, 이때 서버는 요청받은 정보를 처리하고 모든 페이지 영역을 HTML로 재구성 하여 완성된 페이지 형태로 응답하는 해당 방식은 페이지의 일부분만 변경되더라도 서버가 불필요한 나머지 부분까지 전부 업데이트 처리해야 하기 때문에 페이지 갱신의 퍼포먼스가 떨어질 수밖에 없고, 서버에서 응답이 돌아올 때 까지 웹 브라우저는 아무 작업도 하지 못하고 기다려야 하기 때문에 이러한 문제를 개선하기 위해 고안된 방식이 "AJAX"

AJAX로 하는 일

- TEXT, HTML, XML, JSON 형식으로 작성된 문서 데이터를 HTTP 프로토콜을 통해 서버에 요청
- 웹 페이지의 특정 영역에만 필요 내용을 갱신
- 일반적으로 프로그램의 프로세스는 동기화 처리를 진행하지만, A와 B작업을 동시에 진행하는 것을 비동기적인 처리라 하며, JavaScript에서는 콜백함수로 처리

jQuery를 이용한 AJAX

- jQuery 라이브러리로 AJAX를 사용하면 JavaScript만 처리하는 것보다 간결해지고 크로스 브라우징 문제도 해결가능

* 크로스 브라우징?
   ㄴ 웹 페이지의 상호 호환성, 서로 다른 브라우저들끼리 서로 호환이 가능하도록 하는 것을 의미
   -- 크로스 브라우징 / 웹 접근성 -- 더 알아보기!

- $.ajax({

      url : "접속할 페이지 주소",
      type : "get / post",
      data : "파라미터 문자열 (ex> key=lanuage&value=java)", 
      data Type : "text/xml/json",
      timeout: 밀리세컨드단위 제한시간,
      cache : 이전요청에 대한 캐쉬 저장 여부(true : 사용함 / false : 사용안함),

      파일 읽기에 성공한 경우
      success : function(data) {

         통신이 성공했을 때 실행되는 함수
      }, 

      파일 읽기에 실패한 경우(주소 오타, 웹 서버 중지 등)
      erroe : function(xhr, textStatus, errorThrown) {

         통신이 실패했을 때 실행되는 함수
      }
});

- $.ajax()함수는 웹 서버와의 통신결과에 따라 success(), error()함수 호출
- 웹 서버에서 전달하는 결과값을 정상적으로 읽어올 경우 success()함수의 파라미터로 서버에서 읽은 결과가 전달되고, date Type에 text, xml, json 따라 처리방법 상이 (date Type에 따른 처리방법 알아보기)
- 웹 서버에서 전달하는 결과값을 정상적으로 읽어오지 못할 경우 3개의 파라미터 전달
   
   ㄴ xhr: javascirpt에서 ajax처리를 위해 사용되는 XMLHttpRequest 객체원본. 이 객체가 포함하는 status 속성에 HTTP ERROR CODE(404:Page Not Found, 500:Server Error)값 포함
   ㄴ textStatus : "error"라는 고정값을 갖는 문자열 전달
   ㄴ errorThrown : 에러의 원인을 의미하는 문자열 전달 (404:Not Found / 500:Server Error)

   데이터 포맷 변환하기

   - 자료의 포맷 또한 중요. TEXT 및 EXEL 등의 자료를 애플리케이션에서 사용하려면 필요한 형식으로 변환 
   - https://www.utilities-online.info/

JSP ( Java Server Pages ) 

- Tag를 이용하여 고유한 문법을 기술하는 서버 프로그래밍 방식

Tag 방식

- Script Tag 
- Action Tag
- Custom Tag

Script Tag

JSP태그로 지정하지 않은 것은 모두 HTML 태그로 인식하고, HTML 태그 역시 _jspService() 메서드 내에 out.print("<h1>") 이런식으로 변경

- 지시어(directive) <%@  %> : JSP 페이지 속성 지정
- 선언문(declaration) <%!  %> : 전역변수 및 메서드 선언
- 표현식(expression) <%=  %> : 변수, 계산식, 함수 호출 결과를 문자열 형태로 출력
- 스크립트릿(scriptlet) <%  %> : Java 코드 기술
- 주석(comments) <%-- --%> : JSP 페이지 설명 추가

Action Tag

- <jsp:include page="test.jsp" /> : 다른 페이지의 실행 결과를 현재 페이지에 포함 시킬 때 사용
- <jsp:forward page="test.jsp" /> : 현재 JSP 페이지의 제어를 다른 페이지에 이동 시킬 때 사용 (제어 시킬 때?) 
- <jsp:useBean id="빈 이름" class="자바빈 클래스명" /> : 자바빈 사용
* 자바빈?
   ㄴ JSP에서 객체를 가져오기 위한 기법. DTO(Data Transfer Object)라고도 함
   ㄴ JSP 프로그래밍에서 DTO, DAO 클래스의 객체를 JSP페이지에서 사용하기 위해 사용

- <jsp:setProperty name="빈 이름" property="속성명" /> : 자바빈의 속성을 지정하는 메서드 호출
- <jsp:getProperty name="빈 이름" property="속성명" /> : 자바빈의 속성을 반환하는 메서드 호출

Custom Tag

- 새로운 Tag를 정의 후 사용하는 방법
- <tag:printData /> : 사용자가 직접 정의한 태그 사용

JSP 소스의 Servlet 변환

- 변환단계(Translation Step) : 컨테이너는 JSP 파일을 Java 파일로 변환
- 컴파일단계(Compile Step)   : 컨테이너는 변환된 Java파일을 class파일로 컴파일
- 실행단계(Interpret Step)   : 컨테이너는 class 파일을 실행하여 그 결과(HTML, CSS, JS)를 브라우저로 출력

JSP 라이프 Cycle ( JSP가 Servlet으로 변환 시 주요 method )

- _jspInit() : 요구되는 자원의 연결 등 초기화 작업 수행
- _jspSercie() : 실제 클라이언트의 요청에 대한 작업 처리 수행으로 클라이언트 요청 때마다 반복 수행
- _jspDestroy() : 웹서버 또는 애플리케이션이 종료되는 경우 Servlet을 메모리에서 언로드하는 경우, JSP Servlet 종료를 위한 작업 수행

JSP 지시자 종류

- page : <%@ page property="속성값"%> -> JSP페이지에 대한 속성지정
- include : <%@ include file="속성값%> -> Tag 부분에 지정된 페이지를 정적으로 삽입
- taglib : <%@ taglib prefix="속성값% uri="경로"%> -> 새로운 태그를 정의하여 이용


Day_41 : 2023-02-06

page 지시자

- JSP 페이지에서 필요한 설정 정보를 지정

page 지시자 속성

- language : JSP페이지의 표현식, 선언, 스크립트릿에서 사용할 스크립트 언어의 종류를 지정하는 속성
  <%@ page language="java"%>

- contentType : JSP페이지가 생성할 문서의 타입 지정
  ** 미지정시 text/html Default **
   <%@ page contentType="text/html; chatset=utf-8"%>
   <%@ page contentType="application/json"%>

  - pageEncoding : JSP 페이지의 문자 인코딩 방식을 기술하는 속성
  ** 미지정시 ISO-8859-1 Default **
   <%@ page pageEncoding="UTF-8"%>

  ** 한글 지원을 위해서는 [EUC-KR] 지정 **
   <%@ page pageEncoding="EUC-KR"%>

 - info : JSP페이지 전체에 대한 설명이나 버전, 작성자, 작성일자와 같은 정보를 문자열로 기술하는 부분
   <%@ page info="JSP페이지에 대한 설명 및 정보"%>

 - import : 사용할 클래스의 패키지를 지정하는 방법
   <%@ page import="java.util.*"%>
   ** JSP 페이지에서 자동 import **
   [java.lang.*] / [javax.servlet.*] / [javax.servlet.http.*] / [javax.servlet.jsp.*]

   - isErrorPage : JSP페이지가 오류를 처리하는 페이지인지 true, false(default)로 지정하는 속성
   <%@ page isErrorPage="true"%>
   ** isErrorPage를 true로 지정하면 내장객체라 부르는 exception 변수를 사용하여 에러 처리 **


Day_42 : 2023-02-07

Java 소스 외부로 배포

== .jar는 class 파일을 압축해놓은 것 ==

- .jar : class 파일을 압축해놓은 것 (java를 외부로 배포할 때)
- .war : 웹에 관련된 프로젝트는.war로 압축(ex> dynamic Web Project) 어디로 내보내는지? 톰캣 폴더 > webapps(경로변경 하지 않으면 기본으로 webapps에 소스파일이 위치할 폴더) > 


이클립스에서 톰캣으로 export하고 war파일로 webapps 폴더에 저장
그리고 이클립스내 서버를 종료하고
외부에 있는 서버를 구동
war파일을 외부 서버 구동 시 압출파일이 풀림(따로 푸는 작업을 하지 않아도 됨)
이렇게 외부에서 운영해야함

우리가 설정했던 path에 대한 저장정보를 server.xml이 기억함
이클립스 내 server.xml 파일에 대한 <Context docBase>를 복사한 다음
외부에 있는 톰캣서버의 conf > server.xml 파일에서 </host> 종료태그

위에 삽입 후 서버 종료 후 재 구동 시
브라우저내 localhost:8080 입력 시 게시판 시작 페이지 구동되는 부분 확인!
실제 구현 시 이클립스 내에서 구동할 수 없으니!

왜 링크에다가 index.html을 작성하지 않아도 되는 이유는 web.xml > welcome에 index.html이 명시되어 있기 때문에!

기본 환경설정에 설정되어 있는 JDK17을 참조함

legacy 프로젝트는 .jar 파일을 추가할 때 원격지로부터 파일을 직접 받아와야 하는데 받아온 파일은 Maven에서 확인할 수 있고, 파일탐색기 경로는 C:\Users\ealiy\.m2\repository  

Dynamic Project & Legacy Project 차이점 

Dynamic Project

- 외부로 배포할 때 .war 확장자
- .jar 파일을 외부로부터 직접 추가

Legacy Project

- .jar 파일을 내부 pom.xml 파일에서 관리
- 의존성에 대한 내용은 직접 코딩하지 않고 https://mvnrepository.com 에서 검색 후 붙여넣기 작업을 권장

** 의존성에 대한 내용은 마지막에 저장하지 않고, 수정한 코딩에 대해서 저장 후 Maven에 저장된 파일 버전이 맞게 변경되었는지 확인하기 **

pom.xml

- 의존성을 관리하는 파일
- 추가하는 API에 대해서 주석으로 설명을 다는 습관(알아볼 수 있게)
- 단위테스트 할 때 사용하는 프레임워크 "junit"
   ㄴ junit 프레임워크는 항상 버전을 4.10 이상으로 설정
- maven 버전 변경 시 해야하는 작업 : 프로젝트 > 우클릭 > maven > update Project

Lombok 라이브러리

- 개발자는 필요한 필드작성
- Java단에서 개발하는 DTO, VO 클래스에서 생성자, 접근자, 설정자, toString 자동 생성해

src > main > java
자바소스작성

src > main > resources
자바파일이 구현되기 위해서 필요한 설정파일들 예를 들어 MyBatis

servlet-context : 웹에 대한 내용 작성
root-context : DB연동에 대한 내용 작성

log4j.xml은 DTD라는 문서가 필요함 따라서 log4j.xml 파일을 수정해야함

Servlet IOC : 제어의 역전, 
Servlet Container 가 인스턴스를 만듦
스프링도 서브 컨트롤, 서비스도 인스턴스 생성을 하지않음 추후에 XML 문서를 작성할거고, 이전에 카페(인터페이스를 사용함으로서 얻을 수 있는 장점 확인) 결합도가 높은 프로그램 작성


Day_43 : 2023-02-08

Spring Framework

- SpringFramework는 구동되기 전 인터넷 연결이 된 상태에서 접근
- JDK 버전설정 ( 1.8이상으로 설정해야 現어플리케이션 개발에 문제X )
- JDK를 여러개 설치할 수 있으므로 기본으로 사용할 JDK 파일은 환경변수로 설정
- 기본 버전이 아닌 다른 JDK는 압축파일로 저장 후 사용

   ㄴ환경변수로 설정하는 이유 ?
      운영체제 어디서든 Java를 인식할 수 있도록 하기 위한 목적

   ㄴ Path 설정하는 이유 ?
       ++++++++++++++++++++++++++++++++
- Tomcat Server 설치 및 연동       
   ㄴ 최소 설치버전은 8이상 권장(現개발 웹에서 사용 가능)
   ㄴ Tomcat Server 버전에 따라 jstl, jsp, servlet 지원버전이 다름
      jstl : maven > jstl 
      jsp : maven > jsp.api
      servlet : maven > servlet.api

- STS(Spring Tool Suite) 설치
   ㄴ 이클립스 > Help > Eclipes Marketplace
   ㄴ JDK버전이 17, 19부터는 Spring Tools3을 설치 시 오류가 발생할 수 있으니 제일 안정적인 버전인 JDK11을 설치 후 진행
   ㄴ 현재 Spring Framework는 더 이상 버전 UP이 되지 않고있기 때문에 JDK17, 19 이상부터는 SpringBoot Framework 설치 권장
   ㄴ JDK 저장경로 : D Driver > webdeveloper > util > JDK
   ㄴ D Driver > webdeveloper > eclipse > eclipse.ini : vm 경로 및 버전 설정 후 이클립스 재구동
   ㄴ eclipse.ini 코드 中
                              -vm
                              D:\webdeveloper\Java\jdk-11\bin

   ㄴ package 설정 시 기본설정된 JDK버전과 다르기 때문에 오류발생
   ㄴ Spring Legacy Project 생성 시 Spring 버전은 3.x이고, JDK 1.6이기 때문에 pom.xml

pom.xml ( Project Object Model )

- maven의 빌드파일 ( 프로젝트의 다양한 정보를 처리하기 위한 객체 모델 정보를 담고 있는 파일 )
- 프로젝트 설정을 xml태그로 기술
   maven ?
      pom.xml이라는 빌드파일을 사용하여 빌드 정보 기술
      maven은 커멘드를 사용하여 간단히 프로젝트를 만들거나 빌드 가능
      maven의 강점은 다양한 라이브러리와 프레임워크 등 이용하는 경우 maven이 관리. 이러한 프로젝트 관리를 하기 위해서 maven 명령을 실행하는 것으로 끝나지 않고, 프로젝트를 관리하고 있는 빌드파일에 대한 이해필요

      



SpringBoot Framework

- Tomcat Server 내장有

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

IOC : 결합도와 관련
AOP : 응집도와 관련

하나의 프로젝트가 만들어질 때 가장 중요한 것은 결합도와 응집도를 집중

ibatis의 후속버전 MyBatis

JPA

IOC(제어의 역전, 역행)
<!-- 인스턴스 생성을 컨테이너가 직접해주기 때문 -->
Servlet(HttpServletRequest, HttpServletResponse extends)은 생명주기라는 틀에서 init(최초), service(doGet, doPost), distory(종료)

POJO : 순수한 자바 객체
POJO가 아닌 것은 Servlet

Servlet처럼 컨테이터가 인스턴스를 생성할 때 내가 만약 필요한 시점에 불러오고자 할때 어떻게 해야하는가
DI(의존성 주입)

하나의 객체가 다른 객체의 영향을 받는 것을 "의존성"

스프링은 참조변수 지정할 때 class명에서 첫글자만 소문자로 변경 후 참조변수명으로 설정

*** 의존성에 대한 정리 필요 ***

IOC(제어의 역향)이라는 것은 인스턴스 생성에 대해서 소스코드로 처리하지 않고 컨테이너로 처리하는 것

디자인 패턴 중 "Factory"

String은 xml이라는 설정파일 사용
bean이라는 설정파일을 정의하는 곳이 xml

전체에서 사용할 파일이라면 spring > xml 파일에 설정해겠지만

xml문서는 최상위의 root가 필요함 (최상위문서에 반복되는 요소가 들어감)

bean => 스프링에서 관리하는 객체

설정파일을 통해 인스턴스를 얻고자 할 때

- bean
- 만약 설정파일을 통해 인스턴스를 얻고 싶다면  bean이라는 요소에 직접 명시

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

Spring 컨테이너의 종류

BeanFactory ( 지연로딩방식 )

- Spring의 설정파일에 등록된 <bean>이라는 속성에 객체생성
- 컨테이너가 구동 시 <bean>객체를 생성하는 것이 아닌 클라이언트의 요청에 의해서<bena> 객체생성 

ApplicationContext ( 즉시로딩방식 )

- BeanFactory가 제공하는 <bean>객체 관리 기능 외에도 트랜잭션 관리포함
- 컨테이너가 구동되는 시점에 <bean>등록된 클래스들을 객체 생성

스프링 XML 설정

<beans>

 - <bean>**** --> <bean> 내부에 작성한 객체들을 컨테이너가 실행되었을 때 즉시 인스턴스 생성

   ㄴ id[유일값] 속성은 생략할 수 있지만, class 속성은 필수
   ㄴ id는 Java의 식별자 규칙을 Following
   ㄴ name은 Java의 식별자 규칙을 따라가지 않고, 문자열 허용
   ㄴ <bean> 태그내 init() method 작성가능 (해당class에 메서드 작성해야함)
   ㄴ <bean> 태그내 destory() method 작성가능 (해당class에 메서드 작성해야함)

 - <import>

   ㄴ 하나의 설정파일에 전부 정의할 수 없으니 여러개 설정 파일을 나누었을 떄 작성


bean의 scope 속성을 singleton으로 작성 시 인스턴스 생성을 1번만 생성
만약, singleton이 아닌 prototype 작성 시 요청할 때 마다 객체가 생성되어야함

scope의 기본값이 singleton이기 때문에 prototype으로 작성하지 않으면 객체를 한번만 생성함

인스턴스가 만들어지면 default 생성자 호출

싱글톤은 한번 만들어진 주소를 공유해서 사용

<bean> scope 속성의 기본 값은 singleton

스프링의 가장 큰 특징은 ioc

a class가 b class에 의존적이면 a class에 인스턴스를 외부에서 주입해줄 수 있다.

ioc 의 형태 2가지

- Dependency Lookup
- Dependency lnjection *** (DI) 의존성 주입 중요!!!!!!

DI!!!!!!!!!!!!!

Day_44 : 2023-02-09

Java 코드 변경 없이 설정파일로 인스턴스 생성 가능

의존성을 주입하는 방법 

- 생성자(default, 매개변수 있는 생성자)
- 설정자(생정자는 default)

보통 메서드를 호출할 때 사용하는 속성은 <property>

<property>는 <bean> 태그 안에 작성해야 하는 이유 ?
   ㄴ property에서 메서드를 호출할 때 참조변수.method로 호출하기 때문에 <property>내에 작성된 참조변수 명이 없으므로 <bean>태그 안에 명시해야 한다.
   ㄴ setProperty로 설정할 대상이 참조형이라면 ref=" "
   ㄴ setProperty로 설정할 대상이 기본형이라면 valeu=" "

   Java 코드로 new 연산자로 인스턴스를 생성하지 않고, 설정파일을 통해 생성자, 설정자를 통해 인스턴스를 외부에서 넣는 것이 주입이다

   네임스페이스

   -

   컬렉션 객체 설정 
   
   - set
                                          <!-- default 생성자  -->
                               <!-- default 생성자를 통해 인스턴스 생성 -->
   <bean id="collectionBean" class="com.spring.injection.CollectionBean">
      <!--set property -->
      <property name="addressList">
                      <!-- 필드 -->
         <list>
            <!-- value = String형 -->
            <value>서울시 강남구 역삼동</value> 
            <value>서울시 영등포구 당산6가</value>
         </list>
      </property>
   </bean>

   ==> 외부로부터 주입할 준비완료! 이제 실행(Java 코드 이동)에 가서 코드 변경

list는 값에 접근할 때 index로 접근하고, set은 집합적 구조 자료형이기 떄문에 

lterator

- Java Collection에 존재하는 값으 읽어오기 위한 방법
- lterator class : 해당 Collection의 주솟값을 기반으로 하나씩 값을 조회하는 클래스
- 대표적으로 hashNext(), next()
- hashNext() : 다음 값을 갖고 있는지 true / false 반환
- next() : 다음 값으로 이동 및 변환 
- Java에서 각 Collection 별로 Iterator를 반환하는 함수를 갖고 있음
- Iterator은 Collection의 1번째 주소값을 반환하는 형식
- Iterator를 이용해 Collection을 추출하는 방법 : '1번째 주소를 답은 Iterator 생성'-> 반복문을 통해 하나씩 이동하며 저장된 값 반환

Iterator<String> setter = hSet.iterator(); // 만든hSet의 iterator 정보를 담은 setter 변수 생성(hSet 자료형과 동일하게 생성)
   while(setter.hashNext()) { // 값이 존재할 때 까지 반복

      String str1 = setIter.next(); // hSet의 다음 값 가져오기
      Systems.out.println(str + "");

}

SpringFramework 객체 생성 방법


- XML 파일 <bean> 속성 작성
- annotation 명시

** 둘다 인스턴스 생성 시 default 생성자 호출 **

XML 파일 <bean> 속성 작성

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
실행할 클래스의 패키지의 인스턴스 생성을 위한 설정파일을 항상 패키지 마다 만들어야 하는지?
기존의 pom.xml에 작성하면 안되는건지?
pom.xml <project> 태그 내에 작성하면 안되는건지?
해당 패키지 및 클래스 내에서만 사용할 인스턴스 이기 때문에 새롬 만든 xml에 작성해야 하는지?
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

annotation 명시

- annotation 설정추가 시 <beans>에 context 관련 네임스페이스와 스키마 문서위치 등록
   ㄴ Namespaces 탭 선택 후 context 항목 체크

- @Component("ID명")
- <context:component-scan /> 요소의 base-package 속성
   ㄴ <context:component-scan base-package="추가할 패키지명" />

- 설정파일(Java 단) 클래스들을 <bean> 등록

직접 만든 클래스들을 어노테이션으로 객체를 생성할 수 있지만, 외부에서 가져온 라이브러리는 XML 사용 
( <bean>으로 설정 ) 

@Component를 상속받아 확장한 annotaion

- @Controller
- @Service
- @Repository
   ㄴ 요즘은 dao 구현 클래스가 자동으로 생성되는 추세라서 해당 annotaion은 잘 사용하지 않음

Spring 프로젝트 신규생성(springPractice)


Day_45 : 2023-02-10

- 이전 코딩(Spring을 사용하지 않았을 때)

@RequestMapping("/test/basic")
public String basic(HttpServletRequest request) {

   String word = request.getParameter("word");

}

- Spring을 사용할 때(annotation 지원)
public String basic(@RequestParam("word") String word)

- method의 괄호안에 작성한 매개변수는 인스턴스가 만들어졌다는 의미
ex) public void test (HttpServletRequest request) {

   참조변수 a에 저장할 name값을 request 객체를 사용해서 얻어옴 == 메서드 괄호 안에서 인스턴스 생성이 완료되었다는 의미

   String a = request.getParameter("name");
}

annotation 중 @ResponseBody

@ResponseBody

- 메서드를 통해 return 할 값이 view(사용자한테 보여줄 jsp)가 아닌 실제 data 값일 때 사용

@RequestBody 

- 클라이언트가 요청한 타입이 JSON일 경우 반환하는 타입이 VO, MAP 타입일 때 사용


Day_48 : 2023-02-13

MyBatis Framework ( 연속성 프레임워크 )

- Java의 관계형 데이터베이스(RDBMS) 프로그래밍을 좀 더 쉽게 할 수 있도록 도와주는 개발 프레임워크
- XML 구문과 annotation을 사용한 SQL문이나 저장된 프로시저를 데이터베이스와 자바 등 연결시켜주는 역할


Spring과 MyBatis-Spring을 연동한 데이터에 대한 흐름

                                  [            MyBatis          ]
- Controller -> Service(Logic) -> Mapper(=DAO) -> Mapper XML 구문 -> DataBase
- Controller : Spring 구성요소로 Service Logic으로부터 데이터를 전달받음
- Service(Logic) : JavaBean 구성, 데이터베이스 검색 및 관리
- Mapper : Interface로 선언 후 구현 class에서 SQL문 실행
- Mapper XML : Mapper XML요소와 SQL문으로 작성

SQL Mapper XML 파일

- DB연동에 필요한 SQL Query문 작성
- 데이터베이스를 다루는 SQL문은 MyBatis가 제공하는 기능의 XML, annotation 통한 Mapper 기법으로 작성

MyBatis Mapper XML 요소

- mapper : 루트 엘리먼트
- select : Mapping된 select문
- insert : Mapping된 insert문
- update : Mapping된 update문
- delete : Mapping된 delete문

select, insert, update, delete 공통 사용 속성

- id : 필수속성. 전체 Mapper 파일들 내 유일한 값 설정
- parameterType : SQL 실행에 필요한 데이터를 외부로부터 받아야 할 때 사용. 일반적으로 기본형이나 VO 형태의 클래스로 지정
- parametMap : 외부 parameterMap을 찾기 위한 접근 방법 !! 비권장 !!
- statementType : Statement, Prepared, Callable 중 선택. default = Prepared

select 

- 데이터를 검색하는 select 구문을 작성할 때 사용

<select id="구분자" resultType="반환타입">
   select 컬럼명1, 컬럼명2,...from 테이블명
</select>


Day_49 : 2023-02-14

SQL 구문 내 '<>'기호를 사용하면 에러발생
CDATA Section으로 SQL 구문을 감싸주면 에러가 발생하지 않음
select는 resultType이 반드시 있어야함

CDATA Section은 XML 고유 문법으로 CDATA 영역에 작성된 데이터는 단순한 문자 데이터
<![CDATA[ where num <= #{num} ]]>
--> MtBatis는 <>을 문자로 인식 후 연산자로 인식

동적 SQL

- 하나의 SQL문을 다양한 형태로 실행하는 기능

if (단일 조건문)

- <if>요소는 test의 조건문이 참일 때 연결문자열을 SQL문에 연결하고, 거짓일 때는 실행되지 않는다. SQL문의 WHERE절의 포함 여부를 작성할 수 있다.

-- 검색 시 사용하기에 용이 --

표기법 : <if test="조건문">연결문자열</if>

choose, when, otherwise (복수 조건문)

trim, where, set(update 문에서 사용)

where

SQL문 내에서 기술한 <where>---</where>내의 조건의 모두 참이 되지 않을 경우 <where>---</where>의 모든 문자열을 제거

if문 안에 where절을 작성할 수도 있지만 코드의 중복으로 인해 바깥에 작성

조건이 1개 일때는 where만 있으면 되는데 조건이 2개 이상일 때는 and, or 명시

trim

<trim prefix="WHERE" prefixOverrides="AND | OR">---</trim>

- and, or 연산자가 제거될 수 있도록 사용
 
 trim 엘리먼트 속성

 - prefix
 - prefixOverrides
 - suffix
 - suffixOverrides

 foreach

 MyBatis의 XML 파일은 최상위 루트 <mapper>

<if test="title != null">
   AND TITLE LIKE #{TITLE}
   AND TITLE LIKE '%' || #{TITLE} || '%' --> 해당구문이 좀 더 정확함

</if>

Spring에서 Ioc를 지원하는 방법 

1) Dependency Lookup
2) Depenndenct Injection

Dependency Injection 

1) Setter Injection
2) Constructor Injection

생성자 인젝션을 위해서는 <bean> 등록 설정에서 시작태그와 종료태그 사이에 <constructor-arg> 엘리먼트를 추가, 그리고 생성자 인자로 전달할 객체의 id를 <constructor-arg> 엘리먼트에 ref속성으로 참조

xml파일추가를 위한 Eclipes Marketplaces에서 MyBatis 추가
 
클래스간 결합도를 낮추기 위한 방법 

- 다형성 (인터페이스)
- 디자인패턴 (Factory 패턴)


Day_50 : 2023-02-15

Spring을 기반으로 한 mvc 패턴 프로젝트를 진행 중 JUit 실행 시 DB로부터 정보를 가져오지 못해서 오류를 해결하던 중 root-context.xml 파일에 log4j 작성을 logi4j로 작성하여 DB정보를 불러오지 못했던 것이다. 시퀀스 생성 여부가 오류 원인인 줄 알았는데 해결해서 너무 뿌듯하다! 

이클립스내 소스코드에 오류가 없을 때 프로젝트가 오류표시등이 생긴다면 Maven을 업데이트 하면 된다!


Day_51 : 2023-02-16

rootContext의 thin:@인데 thin@이렇게 작성했었다..

* 최초실행이라면 eclipes marketplace에서 sts 다운로드
! 지원하는 버전이 다른 부분 확인 !
Spring 프로젝트 생성(legacy project) -> 프로젝트명 & MVC 패턴 -> Package (최소)3 depth 결정 -> JDK 버전변경 -> POM.XML(의존성 관리) -> WEB.XML -> LOG4J == 설정파일 완료 후 ==
DB(TABLE 생성) -> VO 생성 -> DAO(interface)[interface를 만들면 xml을 만들 수 있음(MyBatis xml Mapper)] -> XML파일에서 작성할 parameterType과 resultType은 Full Name을 작성해야 하기 떄문에 MyBatis-config-xml 별칭작업 -> XML(interface에서 사용할 Query문 작성 파일) // 기본적으로 DB사용할 세팅 완료 -> src/test/java 해당 경로에서 xml에 작성한 Query문 test 진행. 단, class명은 상이해도 되지만 Test하고자 하는 메서드가 작성된 interface와의 패키지 경로가 동일해야함. 패키지명이 다르면 오류발생 -> Service & ServiceImpl. ServiceImpl 클래스에서 가장먼저 @Service 어노테이션 명시 후 Dao가 필요하기 때문에 Dao를 필드로 가짐(생성자 Injection을 통해 자동주입) -> Controller // 브라우저로 요청할 수 있음. Controller 단에서 Model을 매개변수로 가지고 jsp로 이동 -> jsp(Controller단에서 Model 속성값으로 전달한 값을 JSP에 Core로 뿌려줌)


jsp 페이지가 아닌 Mapping 요청 시에는 request

Controller단에서 return 값과 tiles xml파일의 name 값이 동일해야 한다!
jsp에서 taglib 속성은 include를 제외한 다른 방법에서는 적용되지 않는다. 예를 들면 tiles.xml의 value 값으로 전달한 페이지에 작성한 속성처럼!
결론, taglib 속성은 실행하는 jsp파일 혹은 include하는 파일에서만 적용되는 점을 확인한다.

url 요청-> Controller -> service -> dao -> DB
DB -> Service -> dao -> Controller(return) -> tiles(value) -> 해당 jsp 페이지를 컴퓨터가 읽으면서 화면에 그림! 


Day_52 : 2023-02-17

Java 예외처리 자동 리소스 닫기
try-with-resources (파일해지, 네트워크 연결 종료, 데이터베이스 연결 종료)

예외발생 여부와 상관 없음
try-catch-resources 문장은 문장의 끝에서 리소스들이 자동으로 닫혀 지게 한다.
즉, 사용했던 리소스 객체의 close()메서드를 호출해 리소스를 닫는다.

springProject에서 localhost:8080 요청 시 home.jsp가 나오는데 직접 만든 index.html페이지를 보여주려면 어떻게 해야하는지

boardList화면에서 글쓰기 버튼 눌렀을 때 writeForm으로 이동하는 jQuery 작성에 오류가 없었는데 개발자도구로 확인하면 network에서 아무 기능이 적용되지 않아서 boardList.jsp에 include 되어진 common.jspf를 확인하던 중 하단 script 태그에 jquery-3.6.2.min.js 중 .js가 작성되지 않아서 적용되지 않았었다. 확장자까지 명시 후 재실행 하니 제대로 작동되었다!

반복문은 id말고 class 설정 권장


Day_54 : 2023-02-19


Day_55 : 2023-02-20

Spring에서 자동주입을 할 수 있는 방법은 필드, 생성자, 설정자 총 3가지에 주는 방법이 있지만, Spring에서 권장하는 방법은 생성자로 생성하는 방법 

SqlSession 객체는 Dao의 구현클래스에 작성해야하지만 MyBatis는 자동으로 만들어주기 떄문에 개발자가 직접 작성하지 않음

MyBatis 환경설정파일에 데이터베이스 연동 작업을 작성할 수 있음

oracle 연결 시 2가지로 나뉠 수 있음

- 서비스이름 : 12c 이상 URL작성 시 -> /서비스이름
- SID       : 11g 이상 URL작성 시 -> :sid

現기준 oracle version : 21 > 18(사용중인 버전) > 12c

INSERT, UPDATE, DELETE는 resultType 속성을 사용할 수 없음
이유는 반환타입이 적용된 행의 갯수 즉, int타입으로 정해져있기 때문

MyBatis의 동적 SQL 처리문

- if
- choose(when, otherwise)
   ㄴ where문 내 작성한 if문이 하나도 만족하지 않을 때는 쿼리문이 where로 종료되기 때문에 에러 발생하므로 where을 <where> 요소로 작성 -> if문이 만족할 땐 where, if문이 만족하지 않을 땐 <where>
- trim (where, set)
- foreach

Null제어, 별칭, 데이터베이스 연동

MyBatis 내 "<" 기호를 사용 시 종료태그로 인식하므로 CDATA Section 사용

* 참고 : RedirectAttributes 객체는 리다이렉트 시점(return "redirect:/경로")에 
	 * 한번만 사용되는 데이터를 전송할 수 있는 addFlashAttribute()라는 기능을 지원한다. 
	 * addFlashAttribute() 메서드는 브라우저까지 전송되기는 하지만, URI상에는 보이지 않는 숨겨진 데이터의 형태로 전달된다.

    Dao -> xml(method == id) -> 단위테스트(정상처리 여부확인)
    xml select -> parameterType : 있을 수도 있고, 없을 수도 있고
                  resultType : 생략 불가능(결과를 받아올 타입이 있어야만 정상처리 가능)

         insert
         update -> parameterType : 생략 불가능
         delete    resultType : 이미 정수형으로 지정되어 있음     

         service interface는 있을 수도 있고, 없을 수도 있다. 이유는 dao와 거진 비슷하기 때문에 재사용할 가능성도 있음

DB로부터 받아온 값을 전달할 때는 VO

Requst.getParameter 
@ModelAttribute

==> SampleController 확인

xml 설정파일 Query문의 요소 resultType, parameterType의 전체 name에 대한 별칭을 줄 때는 MyBatis 설정파일에서 변경


Day_56 : 2023-02-21

형상관리 (svn, git)

프로젝트 설정(프로젝트명, 패키지, 경로, path, 각 분담파트) 후 index.html 파일 확인ㅏ더 -> git, svn upload -> 접속 id, pw 부여할 수 있음 -> 개발자 url 접근 시 해당 id, pw 입력 -> source code 다운 -> 타인 update, 본인 commit(comment) -> 싱크로나이즈(동기화)

Form 안에 input이 1개면 enter값이 submit 기능을 수행하기 떄문에 enter값 제어를 해주어야함!
javascript는 java처럼 타입에 대해 엄격하지 않기 때문에 === 3개 일때는 값과 타입(자료형)을 모두 비교할 수 있는 연산자

MyBatis는 sqlsession 객체 필요 -> sqlsession객체를 얻으려면 sqlsessionFactory 필요

- query > update 형식 확인 -

UPDATE [테이블명]
SET 컬럼1 = '값1', 컬럼2 = '값2'
WHERE 조건 = 조건값


jQuery each구문 하위 요소들을 반복하는 함수

Uncaught TypeError: item.val is not a function
   ㄴ 함수를 찾을 수 없는 경우
   ㄴ 함수명이 태그id, name와 동일하거나 함수 내 오류가 발생하는 코드
   ㄴ 함수명을 겹치지 않게 사용


Day_57 : 2023-02-22

오라클 데이터베이스 페이징 처리

인덱스

서브쿼리는 3가지로 나뉘어질 수 있음

- single row subquery
- scalar subquery
- inline view 
   ㄴ 데이터를 조회하기 위한 작업, 데이터 가공 쿼리 작성 시 오류발생(EX.FORMAT)

서브쿼리는 괄호로 묶어지는데 우선순위를 가짐

rownum -> 내부적인 칼럼 레코드가 insert 될때 마다 count
rowid -> 식별자로 만들어진 인덱스

full scan / index
order by는 데이터가 많을 때 성능의 문제가 생김 따라서, index 활용

inner, outjoin 한번 더 확인

ORACLE에서 PLSQL을 사용하면 반복문을 사용할 수 있음 

PAGING 처리 시 ROWNUM이 필요!

정렬된 데이터 카운트를 하기위해 INLINE VIEW 필요

페이징처리는 Logic이기 때문에 개발자가 고민해야 하는 부분


Day_58 : 2023-02-23

Spring 설정 시 패캐지는 최소 3depth로 설정

중복되는 클래스는 util이란 이름으로 오버로딩 혹은 구현해서 만들도록 로직구현

thumb_nail 파일은 파일명과 확장자를 추출해야함

lastIndexOf(.) +1

list에서 작은 이미지를 보여주고, 상세페이지에서 원본 크기를 보여줌

수정한 js파일이 적용되지 않을 때는 개발자 도구 띄운 후 ctrl+ f5 혹은 이클립스내 run onServer로 구동 시 새로고침

개발자도구 network로 수정한 js가 적용되는지 확인

서버 외부 모듈 추가(이미지 업로드)

db저장확인여부, 저장경로에 저장된 파일 저장여부(thumbnail, 원본 2가지 버전 다 들어가야함), 화면단 확인 여부!

의존성 주입 방법 3가지 (DI)

- 필드객체에 의존성 주입

   @Autowired
   private Speaker speaker

- 생성자로 의존성 주입

   private Speaker speaker;
   
   @Autowired
   public LgTV(Speaker speaker) {

      this.speaker = speaker;
    }

- 설정자로 의존성 주입
    
    private Speaker speaker;

    @Autowired
    public void setSpeaker(Speaker speaker) {

      this.speaker = speaker;
    
    }

   Controller 단 기본구조
   @Controller
   public class 컨트롤러명 {

      @RequestMapping("요청url패턴")
      public 반환타입 메서드명 (Modle 파라미터명---) {

         비즈니스 로직;

         return 뷰명;
      
      }
   }

   resultSet & resultMap


   Day_59 : 2023-02-24

   jsp는 디버깅 방법은 위에서 아래로 이동하면서 확인
   spring은 만든 문서를 가장 마지막에 부르기 때문에 가장 먼저 CONTROLLER단에서부터 발생 따라서, 실제 오류는 하단에 존재하는 경우多 

   RestController -> 메서드 위에 추가되어 있는 작업
   사용자한테 보여줄 문서가 아니라 응답할 문서가 json
   반환받아올 떄 json이라면 vo에 담다

   클라이언트가 서버로 보낼 떄 어떻게 보내야 하나요?
   @RestController에 많이 사용
   
   {

      "필드명"
      "name" : "value",
      "name" : value(문자일 떄 따옴표 생략)


   }

   클라이언트가 작성한 데이터를 json 방식으로 담아 vo에 저장 (name 값이 필드명과 동일해야함 )

   댓글처리기능! 어떤 게시글에 대한 댓글인지 알기 위한 외래키(b_num)이 필요함