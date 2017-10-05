# 깃허브 늅늅이를 위한 가이드

## 2.1. 헤더
* 큰제목: 문서 제목
    ```
    First Header
    =============
    ```
    First Header
    =============

* 작은제목: 문서 부제목
    ```
    Second Header 
    -------------
    ```
    Second Header
    -------------

* 글머리: 1~6까지만 지원
```
# 첫 글머리
## 두번째 글머리
### 세번째 글머리
#### 네번째 글머리
##### 다섯번째 글머리
###### 여섯번째 글머리
```
# 첫 글머리
## 두번째 글머리
### 세번째 글머리
#### 네번째 글머리
##### 다섯번째 글머리
###### 여섯번째 글머리
####### T일곱번째 글머리 (지원 안 함)

## 2.2. 인용문
 ```>``` 블럭인용문자를 이용한다. 뒤에 더 포함할 수 있다.
```
> 이것은 인용문이다.
```
> 이것은 1번째 인용문이다.
>	> 이것은 2번째 인용문이다.	
>	>	> 이것은 3번째 인용문이다.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.
> ### 3번째 글머리
> * 목록
>	```
>	오피스
>	```

## 2.3. 목록
### ● 순서있는 목록(번호)
순서있는 목록은 숫자와 점을 사용한다.
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째

**현재까지는 어떤 번호를 입력해도 순서는 내림차순으로 정의된다.**
```
1. 첫번째
3. 세번째
2. 두번째
```
1. 첫번째
3. 세번째
2. 두번째


### ● 순서없는 목록(글머리 기호)
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

혼합해서 사용하는 것도 가능하다(내가 선호하는 방식)
* 1단계
	- 2단계
    	+ 3단계
			= 4단계


## 2.4. 수평선```<hr/>```
아래 줄은 모두 수평선을 만든다. 마크다운 문서를 미리보기로 출력할 때 *페이지 나누기* 용도로 많이 사용한다.
```
* * *

***

*****

- - -

---------------------------------------
```


## 2.5. 링크

* 내부 링크
```
syntax: [Title](link)

syntax: [리드미] (README.md)

* 자동연결
```
<http://example.com/>
<address@example.com>
```

<http://example.com/>
<address@example.com>

## 2.6. 강조
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~

## 2.7. 이미지
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
![구글 로고](https://www.google.co.kr/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)
![구글 로고](https://www.google.co.kr/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "google logo")
