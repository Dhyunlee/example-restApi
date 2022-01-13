## JSONPlaceholder에서 서버 생성후, json 형식의 api 사용하기

## [진행 순서]
## 1. 아래 주소로 들어간다.
## 주소: https://my-json-server.typicode.com/

<br><br>  

## 일단 api를 생성하려면 서버(my-json-server)를 생성해야한다.   
<br> 

## 2. my-json-server 생성하기 
##  1) 깃헙 레포지토리를 생성한다. 

##  2) 다음 json 파일에 더미데이터를 작성한 후 업로드(= git push)한다. 

<br>  

### json은 아래와 같이 작성

```json
   {
       "param1": [
           {"ex1": 1},
           {"ex2": 2},
           {"ex3": 3},
       ],
       "param2": [
           {"ex1": 1},
           {"ex2": 2},
           {"ex3": 3},
       ]
   } 

```
<br><br> 

## 3. 그리고 아래와 같이 서버에 접속한다. 

## 서버에 접속은 아래와 같은 형식의 url로 들어간다. 
## https://my-json-server.typicode.com/github-your-id/your-repo 

## 필자는 username: Dhyunlee, repo: example-restApi 이므로 아래와 같은 형식으로 들어가면 된다.
## ex) https://my-json-server.typicode.com/Dhyunlee/example-restApi


## 4. 실습 방법

### https://my-json-server.typicode.com/Dhyunlee/example-restApi 여기 주소에<br> 들어가서  
### Available resources 항목을 선택하면 json 페이지 형태로 출력된 결과물을<br> 
### 볼 수 있다.

- example json
  url: https://my-json-server.typicode.com/Dhyunlee/example-restApi/db
  <br>

```json
{
  "posts": [
    {
      "postId": 1,
      "id": 1,
      "name": "donghyun12",
      "email": "donghyun12@gmail.com",
      "body": "즐거운 코딩을 합시다."
    },
    {
      "postId": 2,
      "id": 2,
      "name": "angeli12",
      "email": "angeli12@example.com",
      "body": "오늘 하루도 즐겁게!"
    },
    {
      "postId": 3,
      "id": 3,
      "name": "q2wsky11",
      "email": "q2wsky11@example.com",
      "body": "해피 코딩 ~~"
    }
  ],
  "comments": [
    {
      "id": 1,
      "postId": 1,
      "body": "비가 내리는 날"
    },
    {
      "id": 2,
      "postId": 1,
      "body": "그날은 좀 아니야"
    }
  ],
  "profile": {
    "name": "Dhyunlee"
  }
}
```

<br>
 - posts
  - https://my-json-server.typicode.com/Dhyunlee/example-restApi/posts

```json
[
  {
    "postId": 1,
    "id": 1,
    "name": "donghyun12",
    "email": "donghyun12@gmail.com",
    "body": "즐거운 코딩을 합시다."
  },
  {
    "postId": 2,
    "id": 2,
    "name": "angeli12",
    "email": "angeli12@example.com",
    "body": "오늘 하루도 즐겁게!"
  },
  {
    "postId": 3,
    "id": 3,
    "name": "q2wsky11",
    "email": "q2wsky11@example.com",
    "body": "해피 코딩 ~~"
  }
]
```
<br>
 - https://my-json-server.typicode.com/Dhyunlee/example-restApi/posts/1
 {
  "postId": 1,
  "id": 1,
  "name": "donghyun12",
  "email": "donghyun12@gmail.com",
  "body": "즐거운 코딩을 합시다."
}
 
<br>
<br>

### 자세한 내용: https://my-json-server.typicode.com/

