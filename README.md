# updowngame
## Java Practice

### 논리연습 logical practice

### method 사용 연습

> return된 문자열을 비교하여 업다운 여부 확인
```java
public static String UDCheck(int usernum, int comnum) {
		String up = "Up";
		String down = "Down";
		String correct = "Correct!";

		if(usernum == comnum) return correct;
		if(usernum < comnum) return up;
		if(usernum > comnum) return down;
		return "Out Of Range";
	}
  ```
  #### 문자열 비교보다 조금 더 효율적인 방법이 있을 것 같다


