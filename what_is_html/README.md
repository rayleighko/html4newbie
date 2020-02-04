# What is the HTML(HyperText Markup Language)

HTML은 하이퍼텍스트 마크업 언어(HyperText Markup Language)라는 의미의 웹 페이지를 위한 마크업 언어입니다. 제목, 단락, 목록 등과 같은 본문을 위한 구조적 의미를 나타내는 것뿐만 아니라 링크, 인용과 그 밖의 항목으로 문서를 만들 수 있는 방법을 제공합니다.

또한, 웹 페이지 콘텐츠 안의 꺾쇠 괄호에 둘러싸인 태그(tag)로 되어있는 HTML 요소 형태로 작성합니다. 웹 브라우저와 같은 HTML 처리 장치의 행동에 영향을 주는 자바스크립트와 본문과 그 밖의 항목의 외관과 배치를 정의하는 CSS 같은 스크립트를 포함하거나 불러올 수 있습니다.

HTML 요소의 가장 보편적인 형태는 세 가지 구성 요소를 가집니다.

- 시작 태그(Start Tag): 태그를 시작하는 의미로 <태그이름>과 같이쓰입니다.
- 종료 태그(End Tag): 태그를 종료하는 의미로 </태그이름>과 같이 쓰입니다.
- 요소 속성(Attribute): HTML 태그의 특성을 부여합니다.

주요 HTML 태그는 다음과 같습니다.

```text
<br>                        단순히 줄을 바꾸는 태그
<p>                         paragraph, 명사를 나타내며 한 단락을 표현하는 태그
<hr>                        horizontal, 가로줄
<ul><li>...<li>...</ul>     ...을 순서없는 목록으로 만듦(기본: 까만동그라미)
<ol><li>...<li>...</ol>     ...을 순서있는 목록으로 만듦(기본: 숫자)
<table></table>             표만들기
<tr></tr>                   행(<table>...</table>...에 넣는다)
<td></td>                   열(<tr>...</tr> ...에 넣는다)
<td colspan=숫자></td>       그 셀부터 숫자만큼의 오른쪽 셀을 병합한다
<td rowspan=숫자></td>       그셀부터 숫자만큼의 아래쪽 셀을 병합한다

* ul : unordered list, ol : ordered list, li : list item
```

더욱 자세한 태그는 [MDN HTML 태그 목록](https://developer.mozilla.org/ko/docs/Web/HTML)을 참고하세요. HTML 태그를 쓸 때 명심해야 할 것은 어떤 브라우저(버전 포함)를 지원하는지인데, 가령 main 태그는 Internet Explorer에서는 사용할 수 없습니다.

## HTML 페이지 구성

- HTML : 문서의 내용을 이루는 정보 및 문서의 구조 정의
- CSS : 디자인 요소를 내용 정보(HTML)와 분리한 문서
- Javascript : 문서에서 이벤트 기반 동작을 정의하는 프로그래밍 언어

## 직접 해보기

- HTML 문서(\*.html)를 만들어서 여러 테그를 붙여 하나의 문서를 만들어 봅시다.
- 정답은 `answer.html`를 참고하세요.
