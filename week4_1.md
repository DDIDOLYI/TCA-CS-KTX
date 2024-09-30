# 📌 HW Week4 - GET 요청하기

## 1. 제목

requests 모듈을 활용하여 GET 요청하기

## 2. 이름

>김태훈(Theodore)


## 3. 제출일

> 24.09.30 (월)


## 4. 과제 목표

> request 모듈에 익숙해 지기 

## 5. 코드 실행 결과

> import requests
response = requests.get("https://jsonplaceholder.typicode.com/posts/1")
print("Status Code:", response.status_code)
print("Response Body:", response.text)

## 6. 문제 해결 과정 및 배운점

> import가 안되서 왔다가다를 좀 했습니다 ㅠ