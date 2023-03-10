<h1> A brief summary</h1>

<h2>HTML</h2>

- p 태그는 문단 표시 태그

- h1~h6 태그는 헤드라인 표시 태그

- hr은 수평선 태그

- 스페이스는 한번씩만 허용됨 (공백은 &nbsp로)

- br은 줄바꿈 태그

- strong은 컨텐츠 굵게 표시하는 태그

- em은 이탤릭체로 표시하는 태그

- mark는 콘텐츠에 형광펜 표시하는 태그

- img는 이미지를 보여주는 태그 (<img src="표시할 이미지파일" alt="이미지 설명" />)

- img는 크기 조절이 가능함 (속성값으로 width, height 단위없이 정수값만! 픽셀단위로 적용)

- 블록 레벨 요소 : 자기가 속한 영역의 너비를 모두 차지하여 블록 형성

- 인라인 요소 : 자기에게 필요한 만큼의 공간만 차지

- 컨테이너 : 콘텐츠나 레이아웃에 아무런 영향 주지않고, 요소들을 묶어 관리하게 편하게 하는 것

- 전역 속성 : 모든 태그에 공통적으로 지정 가능한 속성 (id, class, title 등등)

- a태그 : 인라인 요소로 url로 연결할 수 있는 링크를 만든다. (href 속성을 통해), target 속성으로 "_self", "_blank"

- a태그는 href 속성을 이용해 웹사이트 뿐만 아니라 "tel:" , "mailto:" 등을 이용하여 전화걸기, 메일 보내기도 가능하다.

- 목록 태그는 ul 태그와 ol 태그로 나눠지며, 목록 안에 들어가는 항목을 표현할땐 li 태그 사용 (ol,ul,li 모두 블록 레벨)

- input 태그는 입력 요소 만드는 태그 (type 속성에 따라 유형이 결정되는데 type에 따라 추가 속성도 다르다.)

- input 태그 내에 name 속성으로 input 요소를 구별할 수 있다.

- select는 선택 메뉴 나타내는 태그, 각 선택지는 option 태그를 통해 표시 (value 지정가능)

- textarea는 여러 줄의 일반 텍스트 입력하는 요소

- form은 사용자가 입력 요소에 입력한 데이터를 서버에 전송해줌 (input, select 등을 감싸고 submit 한다)

- form의 action은 서버 측 주소를 지정하는 속성, method는 데이터 전송 방식 지정(GET,POST 등)

- meta 태그는 HTML 문서의 메타데이터를 표시하는 태그 (검색 엔진 최적화에 기여하며, 검색 결과에도 영향을 끼침)

- meta태그의 charset은 문자 인코딩에 대한 요약 정보 기입 속성, http-equiv는 콘텐츠 속성의 정보/값에 대한 http 헤더 제공

- meta 태그의 name속성은 문서의 다양한 정보를 제공할 수 있는 메타데이터 이름, content는 메타데이터의 구체적인 내용 기입 속성

- 뷰포트는 현재 화면에 보여지고 있는 영역으로, 메타 태그를 사용하여 뷰포트 관련 설정을 추가할 수 있다.

<h2>CSS</h2>

- CSS 코드 주석 (/* */)

- css 코드를 html 문서에 적용하려면 인라인 스타일, 스타일 태그, 외부 문서 연결(추천) 을 이용해야함

- 선택자가 겹치는 경우, 나중에 작성된 스타일이 적용됨. 그러나 선택자가 다르지만 요소 겹치면
 선택자 우선순위에 의해 결정됨 (아이디 선택자 > 클래스 선택자 > 태그 선택자)

- font-family는 글꼴 지정 속성, 여러 글꼴을 연달아 기입하여 우선순위 지정가능

- font-size는 글자 크기 지정 속성, px(절대적),rem(html문서),em(부모태그) 등의 단위 사용

- text-align은 블록 내에서 텍스트 정렬 방식 정의 (left, right, center, justify 등등)

- color는 red, #FF0000, rgb(100%,0%,0%) 처럼 다양하게 이용가능

- display 속성은 요소의 블록, 인라인 레벨 여부 변경 처리 가능.

- boder 속성은 여러가지 속성을 함께 정의할 수 있는 '단축속성' (border-style, border-width,border-color)
