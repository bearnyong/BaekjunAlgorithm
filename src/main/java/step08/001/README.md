# 중앙 이동 알고리즘 (백준 2745번)
<p>
백준 알고리즘 08단계 001번 문제
</p>

### 요구사항
B진법 수 N이 주어진다. 이 수를 10진법으로 바꿔 출력하는 프로그램을 작성하시오.

10진법을 넘어가는 진법은 숫자로 표시할 수 없는 자리가 있다. 이런 경우에는 다음과 같이 알파벳 대문자를 사용한다.

A: 10, B: 11, ..., F: 15, ..., Y: 34, Z: 35

### 입력
첫째 줄에 N과 B가 주어진다. (2 ≤ B ≤ 36)

B진법 수 N을 10진법으로 바꾸면, 항상 10억보다 작거나 같다.

### 출력
첫째 줄에 B진법 수 N을 10진법으로 출력한다.

#### 분석
1. N을 입력 받는다.
2. 진법 수 B를 입력 받는다.
3. 입력 받은 N의 개별 자릿수를 얻어 char[]값에 저장한다.
4. 저장된 값의 배열을 반대로 바꿔준다.
5. 바뀐 값의 순서대로 B의1승, 2승,...을 곱한 후
6. 모든 값을 더해준다.


#### 풀이과정


참고 : 숫자의 개별 자릿수 얻는 방법 : https://zrr.kr/yPoW
참고 : 제곱 함수 Math.pow(): https://zrr.kr/c8Su