# 마크다운(Markdown) 알아보기

## Table of Contents

- [들어가기 전에](##1. 들어가기 전에)
- [마크다운 소개](##2. 마크다운 소개)
- [마크다운의 장·단점](#마크다운의 장·단점)
	+ [마크다운의 장점](#마크다운의 장점)
	+ [마크다운의 단점](#마크다운의 단점)
- [Syntax](## 4.Syntax)
- [관련문서](#관련문서)

## 1. 들어가기 전에
필자가 마크다운을 배운 이유는 기록하기를 좋아하는 1인으로서 좀 더 컴퓨터 친화적인 양식으로 글을 작성하고 싶어서임.


## 2. 마크다운 소개
마크다운(Markdown)은 일종의 마크업 언어로 존 그루버(John Gruber)와 아론 스워츠(Aaron Swartz)가 만들었다. 텍스트에 태그를 이용하여 글자를 변형, 이미지 삽입 등의 일을 가능하게 해준다. 마크다운을 지원하는 환경이라면 어디서든 쓸 수 있으며, 복사해서 옮겨도 서식이 깨지지 않는다. 

마크다운은 여러 곳에서 사용되고 있다. 워드프레스, Tumblr 등의 블로그 플랫폼에서도 마크다운 언어를 기본적으로 지원하고 있다. 

마크다운의 파일의 확장자는 `.md`이다.

## 3. 마크다운의 장·단점
### 3.1 마크다운의 장점

- **높은 가독성**
	
	마크다운 언어의 문법(Syntax)는 상당히 간단명료하여 HTML과는 달리 글 작성 중 실제 브라우저에 어떻게 보여질지 상상하는 것이 조금 더 쉽다. 

- **습득의 편의성** 
	
	존 (John Gruber)가 처음에 마크다운을 만들 때 살마들이 가장 많이 사용하는 기능만 마크다운으로 쓰고, 복잡한 것은 HTML을 사용하도록 디자인했다. 

### 3.2 마크다운의 단점
- **문법의 단순성** 


	문법이 너무 단순해서 지정된 기능 외에 작업을 요할 시 HTML을 써야하는 경우가 생김. 태그에 클래스 지정이 불가능하기 때문에, 클래스나 id 지정을 위해서도 HTML을 사용해야한다. 

- **다수의 확장문법**


	문법이 너무 단순해서 불편함을 해결하기 위해 개인 취향에 맞춘 여러가지 보완책들이 많아졌다. 그 결과 한 곳에서 잘 작동하던 마크다운 문서가 다른 곳에서 잘 작동하지 않는 호환성 문제가 야기되었다. 

## 4.Syntax

마크다운 문법의 종류는 사용되는 플랫폼마다 조금씩 다른 경우가 있고, 그 문법에 관한 설명은 플랫폼 공식사이트에서 확인할 수 있으며, 이 문단에서는 gitHub에서 자주 사용하는 마크다운 문법에 관해서 정리해보려고 한다. 

필자가 마크다운 언어를 배우기 위해 웹상의 글들을 읽어본 결과, Syntax 문법을 작성하고 그 밑에 예시를 보여주는 방법이 따라하기 제일 쉽게 다가와서 그 방법을 따라 작성하기로 한다. 

### Basic Writing and Formatting Syntax

Headings
Styling text
Quoting text
Quoting code
Links
Lists
Task lists
Mentioning users and teams
Referencing issues and pull request
Using emoji
Paragraphs and line breaking
Ignoring Markdown formatting


### Advanced formatting

 -**제목 (Header)**-

	`#` H1 텍스트

	`##` H2 텍스트

	텍스트
	==================

 -**인용(Blockquotes)**-
	
	`>`
	'>>'

 -**문단**-
 
| hey | ho |
|-----|----|
| hi  | hi |
| hi  | hi |
| hi  | hi |
| hi  | hi |
| hi  | hi |
| hi  | hi |
| hi  |    |


 -**리스트**-
**불렛 포인트 (Bullet Point : 점)**
: 점으로 구성된 리스트
: 별(*), 플러스기호(+), 마이너스기호(-) 중 아무거나 사용가능합니다.

예) 
* 자전거
* 자동차
* 지하철

출력)
* 자전거
* 자동차
* 지하철


**숫자 정렬**
: 순서대로 숫자가 매겨지는 리스트
: 숫자와 점을 찍어서 사용 
: 숫자 리스트는 숫자를 순서대로 쓰지 않아도 자동으로 오름차순을 정렬

예)
1. 자전거
3. 자동차
7. 지하철

출력)
1. 자전거
2. 자동차
3. 지하철


 -**코드블락(CodeBlocks)**-

`<table><tr><td></td></tr></table>`

 -##가로선(Horizontal Rules)**-

*** 별표 세개로 가로선 삽입 가능하다.

 -**링크(Link)**-

[링크 이름](http://주소)

예) [구글](http://google.com)


# 관련문서
1. [깃업 공식 Markdown 설명 자료 페이지](https://guides.github.com/features/mastering-markdown/)
2. [깃업 헬프 Writing on Github 페이지](https://help.github.com/categories/writing-on-github/)
2. [마크다운(markdown)으로 글을 써보자](http://blog.kalkin7.com/2014/02/10/lets-write-using-markdown/)
