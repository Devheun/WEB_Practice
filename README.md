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

- 하나의 박스는 네 개의 영역으로 구성 (content,padding,border,margin)

- 인라인 요소는 content 영역의 height, width 지정이 안되므로 지정하려면 display 속성 변경해야함!

- 여백은 상하좌우 네 면에 존재하는 영역으로 상하좌우 두께를 개별적으로 정할 수도 있고, 함께 정의할 수도 있다.
(padding, margin)

- box-sizing 속성은 너비와 높이가 포함할 영역을 변경함으로써 너비와 높이의 계산 방법 결정할 수 있다.

- box-sizing 속성의 기본값은 content-box이다, border-box로 지정하면 테두리까지 너비와 높이에 포함된다.

- background는 콘텐츠의 배경을 정의하며 단축 속성으로써 다양한 하위 속성을 포함한다.

**Tip** : 정의 시 여러 경우의 수가 존재하는 속성을 학습할 때, 외우기보단 경험을 통해!

- float 속성은 요소가 자신을 포함하고 있는 컨테이너의 왼쪽이나 오른쪽에 배치
(요소는 문서의 흐름에선 제외되지만, 필요한 만큼의 공간은 차지)

- clear 속성은 float 요소 이후에 표시되는 요소가 float 요소의 아래로 내려가게(left,right,both,, 그냥 both 쓰자)

- position : relative; (일반적인 문서 흐름에 따라 배치하되, 자기 위치 기준으로 상하좌우 위치 값에 따라 오프셋 적용)

- position : absolute; (일반적인 문서 흐름에서 제거하고, 상위 요소 중 가까운 position 지정 요소에 대해 상대적으로 오프셋 적용 !)
(상위 요소 중 position 지정요소 없으면 브라우저 기준)

- position : fixed; (일반적인 문서 흐름에서 제거하고, 지정된 위치에 고정)

- position : sticky; (일반적인 문서 흐름에 따라 배치하고, 스크롤 되는 가장 가까운 상위 요소에 오프셋 적용)

- flexbox란 박스 내 요소 간의 공간 배분과 정렬 기능을 제공하기 위한 1차원(행,열) 레이아웃 모델
(행 또는 열이 주축이 되어 정렬 방향 결정한다. flex-direction 속성은 요소 배치할 때 사용할 주축 및 방향 지정)

- justify-content는 flexbox 주축에서의 요소 배치 방법 정의

- align-items는 flexbox 교차축에서의 요소 배치 방법 정의

- align-self는 flexbox 내 개별 요소의 교차축 배치 방법 정의

- flex-wrap은 개별 요소들의 도합 크기가 컨테이너 주축 길이보다 커졌을 때 처리 방법 및 방향을 정의

- 특성 선택자는 주어진 특성의 존재 여부나 그 값에 따라 요소 선택한다.
(값의 포함여부: *=, 값의 포함위치 처음 : ^=, 값의 포함위치 끝 : $=)

- 결합 선택자는 여러 선택자를 결합하여 요소 선택
(자손 또는 형제 중에서 특정 조건 만족하는 요소 선택가능)

- 의사클래스(수도클래스)는 선택자에 추가하는 키워드 (hover,active,focus,disabled,nth-child() 등등)

```
선택자:의사클래스{
속성명: 속성값;
}
```

- 의사요소는 선택자에 추가하는 키워드 (first-line, marker, placeholder, before,after 등등)

- 의사요소는 요소의 특정 부분에만 스타일을 적용하고자 할 때 사용

- 상속은 하위 요소가 상위 요소의 스타일 속성값을 물려받는 것 (상속 가능 여부는 속성마다 다르니 찾아보기)

- 모든 속성에 대해 사용가능한 키워드 값 : inherit(상위 요소로부터 값 물려받겠다),
initial(기본값을 사용하겠다), unset(상위 요소로부터 물려받을 수 있으면 받고, 안되면 기본값 사용하겠다)

- z-index는 요소가 쌓이는 순서를 결정할 수 있다. (기본값은 auto이며 정수값으로 정의한다. position이 정의되어 있을 때!)

- z-index의 정수값은 쌓임 맥락에서의 레벨을 의미하며, 값이 클수록 전면에 표시된다.