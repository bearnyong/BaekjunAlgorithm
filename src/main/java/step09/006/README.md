# 중앙 이동 알고리즘 (백준 11653번)
<p>
백준 알고리즘 09단계 006번 문제
</p>

### 요구사항
정수 N이 주어졌을 때, 소인수분해하는 프로그램을 작성하시오.


### 입력
첫째 줄에 정수 N (1 ≤ N ≤ 10,000,000)이 주어진다.


### 출력
N의 소인수분해 결과를 한 줄에 하나씩 오름차순으로 출력한다. N이 1인 경우 아무것도 출력하지 않는다.


#### 분석
1. 정수 N을 입력 받는다.
2. for문을 사용하여 정수N이 나눠질 수 없을 까지 반복하는 구문을 만든다.
3. while문을 사용하여 가장 작은수(2)부터 더 이상 나눠질 수 없을 까지 반복하여 나눠준다.
* 몫을 나눌때마다 남은 값을 다시 num에 대입시킨다.


#### 풀이과정
가장 작은 수인(2)부터 나머지값이 0이 아닐 까지 나누어주며
나눈 값을 num에 대입한다.

나머지 값이 0이 아닐 경우, 다음수인 3으로 넘어가
마지막 최종 값이 나누어지지 않을 때까지 반복문을 사용하여 나누어준다.

