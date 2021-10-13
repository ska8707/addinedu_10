# HTML

## HTML Introduction

https://www.w3schools.com/html/html_intro.asp

- HTML : Hyper Text Markup Language
- 웹 페이지의 내용을 표시하는 언어
  - 웹 페이지의 콘텐츠 표시
    - 텍스트 콘텐츠
    - 미디어 콘텐츠
  - 웹 페이지의 구조 표시

## HTML Element

https://www.w3schools.com/html/html_elements.asp

```
<tagname>Contents</tagname>
=> tagname : Contents 종류, 특성 표시 / 구조 표시

<tagname> : 시작태그만 존재
=> Empty Element

빈 요소는 시작태그로만 종료된다는 의미로 self-closing 기호를 사용할 수 있음
<tagname />

- 기본 문법 : 사용하지 않음
- reactjs 라이브러리 : 반드시 사용


포함관계(Nested)
<tag1>
  <tag2>
    <tag3>Contents</tag3>
  </tag2>
</tag1>
<tag4></tag4>

tag1과 tag2의 관계
  - tag1은 tag2의 부모요소(Parent)
  - tag2는 tag1의 자식요소(Children)

tag1과 tag3의 관계
  - tag1은 tag3의 조상요소(Ancestor)
  - tag3는 tag1의 자손요소(Descendant)

tag1과 tag4의 관계
  - tag1(4)은 tag4(1)의 형제요소(Ancestor)

대소문자 구분 안함, 소문자로 쓰는 것이 원칙
```

## HTML Attribute

https://www.w3schools.com/html/html_attributes.asp

- Attribute : 속성
- 추가정보를 제공

```
Ex)

<img src="이미지경로/파일이름">

<a href="이동경로주소">링크이름</a>

속성이름="정보"
```

## HTML Basic

```
<!DOCTYPE html>
<html>
	<head>
    웹사이트(앱)와 관련된 정보
	</head>
	<body>
    웹사이트의 콘텐츠
	</body>
</html>
```

- html 태그의 자식요소 : head, body
- head와 body는 형제요소

## HTML TEXT Contents

### HTML Heading

https://www.w3schools.com/html/html_headings.asp

- h : heading - 제목 표시
- h1 ~ h6

### HTML Paragraph

https://www.w3schools.com/html/html_paragraphs.asp

- p : paragraph - 단락 표시

- hr : horizontal rules - 수평선 표시(단락 구분의미 포함) / 빈 요소

```
<p>단락</p>
<hr />
</p>단락</p>
```

- HTML paragraph display
  - 한 단락안에서 강제 줄바꿈, space 강제 공백은 적용이 안됨

```
<br/ > : line break / 강제 줄바꿈, 빈 요소

&nbsp; : non-break space-Entity code / 강제 공백 한 칸
```

### HTML Links

https://www.w3schools.com/html/html_links.asp

- a : anchor
- attribute(속성) : href - hypertext reference / 링크 연결 주소 정보

```
<a herf="https://www.naver.com/">네이버</a>
```

- 다른 페이지로 링크 연결
- 같은 페이지에서 상하 이동 - 북마크 기능

## HTML MULTIMEDIA Contents

# CSS
