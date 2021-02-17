# 파이썬 문법

1. 입/출력
2. 변수
3. 조건문
4. 반복문
5. 배열
6. 함수

## 입력
### 사용자로부터 키보드 입력받기. 결과물이 생긴다.

    name = input( '이름을 입력하세요' )

    age = int( input( '나이를 입력하세요' ))

    height = float( input('신장을 입력하세요'))


## 출력
### 콘솔 화면에 정보를 표시하기. 
#### print( ) <- 괄호 안에 들어가는 모든 정보를 화면에 출력.

    print(name)

    print('name: ' + name)

    print('age: ', age)

## 변수
### 숫자나 문자열 등을 저장하는 저장소

    num = 7
    num = int(input())

    name = 'leehg'
    name = input( )

**input( )** 함수를 통해 변수를 입력받을 때 위치
* 변수 = input('입력 해주세요')  --------( O )
* input(변수) -----------------------------( X )
* print(변수 = 7)	-------------------------( X )
* print(변수 = input( )) -------------------( X )
* 변수 = print(input('입력해 주세요.') ---( X )

## 조건문
if  ______  :
&nbsp;&nbsp;    실행코드

밑줄에는 부울대수가 들어간다.
부울대수는 True 또는 False 를 뜻한다.
True 또는 False를 만들기위한 비교조건식을 사용한다.
비교 조건식은 >, >=, <, <=, ==, !=, and, or 를 활용해 만든다.

- 조건식의 형태
if
if ~ else
if ~ elif ~
if ~ elif ~ else

- 조건식을 사용할 수 있는 위치
가장 바깥쪽
if 조건식 내부
elif 조건식 내부
else 조건식 내부
반복문 내부

<!--stackedit_data:
eyJoaXN0b3J5IjpbOTcwNzMyMzQ1XX0=
-->