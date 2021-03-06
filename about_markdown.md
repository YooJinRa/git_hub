# 마크다운(Markdown)
## 1. 마크다운(Markdown)이란?
마크다운(Markdown)은 일반 텍스트 기반의 경량 마크업 언어다. **일반 텍스트**로 서식이 있는 문서를 작성하는 데 사용되며, 일반 **마크업 언어**에 비해 문법이 쉽고 간단한 것이 특징이다.  HTML과 리치 텍스트(RTF) 등 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 **README 파일**이나 온라인 게시물 등에 많이 사용된다.

- *일반 텍스트(플레인 텍스트 Plain Text) : 그래픽 표현이나 그 밖의 오브젝트(그림 등)이 아닌, 읽을 수 있는 자료의 문자열만을 대표하는 데이터이다.*
- *마크업 언어(Markup Language) : 태그 등을 이용하여 문서나 데이터의 구조를 명기하는 언어의 한 가지이다.*
- *리드미(README, readme, read me) 파일 : 디렉터리나 압축 파일에 포함된 기타 파일에 대한 정보를 포함하고 있으며, 일반적으로 컴퓨터 소프트웨어와 함께 배포된다. 이러한 파일은 README.TXT, README.md, README.1ST, READ.ME, 또는 간단히 README라는 이름의 문서 파일이며, 일부 마이크로소프트 윈도우의 소프트웨어는 README.WRI, README.RTF, README.DOC를 포함하기도 한다.*

[출처 : wiki 백과](https://ko.wikipedia.org/wiki/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4) 

## 2. 마크다운(Markdown)의 장점과 단점
### 2-1. 장점
```
1. 간결하다.
2. 별도의 도구없이 작성가능하다.
3. 다양한 형태로 변환이 가능하다.
4. 텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.
5. 텍스트파일이기 때문에 버전관리시스템을 이용하여 변경이력을 관리할 수 있다.
6. 지원하는 프로그램과 플랫폼이 다양하다.
```

### 2-2. 단점
```
1. 표준이 없다.
2. 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물이 다르다.
3. 모든 HTML 마크업을 대신하지 못한다.
```

## 3. 마크다운(Markdown)의 문법(사용법)
### 3-1. 제목(Header)
# 제목1 ```# 제목1 ``` | ```<h1>제목1</h1>```
> ```
> 제목1
> =====
> ```
## 제목2 ```## 제목2 ``` | ```<h2>제목2</h2>```
> ```
> 제목2
> -----
> ```
### 제목3 ```### 제목3 ``` | ```<h3>제목3</h3>```
#### 제목4 ```#### 제목4 ``` | ```<h4>제목4</h4>```
##### 제목5 ```##### 제목5 ``` | ```<h5>제목5</h5>```
###### 제목6 ```###### 제목6 ``` | ```<h6>제목6</h6>```

---

### 3-2. 강조(Emphasis)
- *이텔릭체* : ```*별표*``` | ```_언더바_```
- **볼드체** : ```**별표**``` | ```__언더바__```
- **_이텔릭체_ & 볼드체** 함께 사용 : ```**_이텔릭체_ & 볼드체**```
- ~~취소선~~ : ```~~물결표시~~```
- `<u>밑줄</u>` : ```<u>밑줄 표현</u>```

---

### 3-3. 목록(List)
**순서있는 목록 : 숫자와 점 이용**
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째


**순서없는 목록 : 기호 `*`, `+`, `-` 지원**
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

* 1단계
  - 2단계
    + 3단계
      + 4단계

```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

* 1단계
  - 2단계
    + 3단계
      + 4단계
```

### 3-4. 들여쓰기
```
This is a normal paragraph:

    This is a code block.
    
end code block.
```
This is a normal paragraph:

 This is a code block.
    
end code block.

> 한 줄 띄어쓰기 안한 경우
> ```
> This is a normal paragraph:
>  This is a code block.
> end code block.
> ```
> This is a normal paragraph:
>  This is a code block.
> end code block.


### 3-5. 코드블럭
> - ```<pre><code>{code}</code></pre>``` 이용방식
> - 코드블럭코드 "빽틱```" 이용방법
> ```
> ```code```
> ```

### 3-6. 수평선
```
* * *

***

*****

- - -

---------------------------------------
```
* * *

***

*****

- - -

---------------------------------------


### 3-7. 링크
```
* 외부링크 : [Google](https://google.com, "google link")
* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>
```
* 외부링크 : [Google](https://google.com, "google link")
* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>


### 3-8. 이미지
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
<img src="/path/to/img.jpg" width="" height="" title="" alt=""></img>
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
<img src="/path/to/img.jpg" width="" height="" title="" alt=""></img>
