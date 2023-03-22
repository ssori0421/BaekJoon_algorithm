# AxB

## **📝문제 설명**
두 정수 A와 B를 입력받은 다음, A×B를 출력하는 프로그램을 작성하시오.

### **입출력 예**
![](https://velog.velcdn.com/images/ssori0421/post/0f2f01d8-9213-4739-b818-d4f620d22c4d/image.png)

## **🧐CODE REVIEW**
### **🧾나의 풀이**

```js
const input = require('fs').readFileSync('dev/stdin').toString().split(' ');

console.log(parseInt(input[0]) * parseInt(input[1]));

```

## 📚참고 사이트

- **🔗문제 링크**<br/>
https://school.programmers.co.kr/learn/courses/30/lessons/12903


### **⚠제한사항**
• s는 길이가 1 이상, 100이하인 스트링입니다.
### **입출력 예**
![](https://velog.velcdn.com/images/ssori0421/post/08f61ad3-bc98-49ed-ad2f-a207762b1135/image.png)
## **🧐CODE REVIEW**
### **🧾나의 풀이**

```js
const input = require('fs').readFileSync('dev/stdin').toString().split(' ');

console.log(parseInt(input[0]) * parseInt(input[1]));
```

#### **📝해설**
1) 문자열.length를 이용해 문자열의 길이를 구함.
2) 문자열[숫자] 

   문자 선택 연산자를 이용해 문자열 내부의 문자 하나를 선택.
3) 문자열 연결 연산자 +를 이용해 새로운 
    문자열을 만듦. 

## 📚참고 사이트

- **🔗문제 링크**<br/>
https://www.acmicpc.net/problem/10998
