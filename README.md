# humanPython

# 파이썬

## 파이선 기초

print("Hello World")

## 파이선 기초문법
- 주석처리
- 여러 줄 주석처리 시,
  + 함수, 클래스 ㅅ작성할 때
  요긴하게 쓰임 (예: Docstring)

# 이 코드는 무슨무슨 코드임
# 주석 해제시 오류뜸 (Syntax error)

'''
여러줄 주석 처리
'''

"""
러아렁니ㅏ멀ㄴ
"""

print("Hello World")


## 변수의 종류 (Scala 자료형)
- 크게 4가지 존재 : int, float, bool, None
- 더 이상 나누어지지 않는 것

### int 형 예제

temp_int = 1
print(temp_int)
print(type(temp_int))

- 문자열

temp_int = '1'
print(temp_int)
print(type(temp_int))

### float형 예제
- 실수형

num_float = 0.2
print(num_float)
print(type(num_float))

### Bool 형
- 참 거짓

temp_bool = True
temp_bool = False
print(temp_bool)
print(type(temp_bool))

### None 자료형
- Null 을 나타내는 자료형
  + 데이터분석에서 가장 처리하기 까다로운 자료형

temp_none = None
print(type(temp_none))

## 사칙연산
- 정수형 사칙연산

a=6.0
b=2.0

print(a+b)
print(a-b)
print(a*b)
print(a/b) #나누기 할시 실수형으로 떨어짐,(딱맞아 떨어져도 .0이 표시되어 실수형)
print(a//b) #몫
print(a%b)  #나머지
print(a**b) #제곱

### 논리형 연산자
- AND 조건, OR 조건이 있음

print(True and True)
print(True and False)
print(False and True)
print(False and False)
print("----------")
print(True or True)
print(True or False)
print(False or True)
print(False or False)

### 비교 연산자
- 비교연산자는 부등호를 의미함
- 왼쪽이 기준 값

print(4>3)
print(3>4)
print(3>=4)
print(3<=4)

## input()
- print() : 출력
- input() : 입력

var = int(input("값을 입력해주세요!!"))
print(var)
print(type(var))

var = input("값을 입력해주세요!!")
print(var)
var = int(var)
print(type(var))

num1 = input("값을 입력해주세요!! ")
num2 = input("값을 입력해주세요!! ")

result = int(num1)+int(num2)
print(result)

num1 = int(input("값을 입력해주세요!! "))
num2 = int(input("값을 입력해주세요!! "))

result = num1 + num2
print(result)

## String
- 매우 중요함!!!!!!!!
- 

str1 = "Hello "
str2 = "World"
print(str1 + str2)

### String 연산자

str1 = "55"
str2 = "1000"

result = int(str1) + int(str2)
print(result)

- 곱셈 연산자 사용

greeting = "Hello World "
print(greeting*3)

### Indexing
- 중요!!
- 0번째부터 시작

greeting = "Hello World!"
print(greeting[-1])

### 슬라이싱
- 자름


greeting = "Hello World!"
print(greeting[0:5])
print(greeting[:])
print(greeting[6:])

greeting = "Hello World!"
print(greeting[11])

###판다스 문법
-ㅇㄹㅁㄴㅇㄴㄹㅁ