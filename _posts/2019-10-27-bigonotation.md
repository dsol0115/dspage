---
title: "간단한 Big O Notation"
date: 2019-10-27 10:10:00 -0400
categories: Algorithm
tag: Algorithm
---

![](https://www.youtube.com/watch?v=waPQP2TDOGE) 보고 정리 한것.

Big O notation 은 결국 복잡도 그래프의 꼬리 모양을 보는 것이라 생각하면 쉽다. 
입력 값이 아주 많을 때 걸리는 시간.

1. O(1) "Constant Time"

상수 시간이다. 그래프가 계속해서 평행을 유지. 값 n에 따른 그래프의 모양이 변하지 않음.

2. O(log n) "Logarithmic Time"

보통 2를 base로 둔다. 결과 값으로 n이 나오기 위해서 log 2 위에 지수로 어떤 값이 들어가야 하는지? 이 질문은 결국 BST와 같은 2로 나눠지는 형태의 알고리즘에서 나타난다. 예를 들어 16이 1이 되기 위해서는 몇 번을 이등분 해야하는 가? 4번이다. 왜냐하면 2의 4제곱이 16이기 때문.

3. O(n) "Linear Time"
 
가장 일반적인 형태. n개의 요소를 가진 배열, n개의 트리노드 등

4. O(nlog n) 

퀵 소트, 머지 소트에서 주로 사용하며 linear time * logarithmic time 이라고 생각할 수 있다.

5. O(n*n) "n-square"

버블 정렬, 선택 정렬, 삽입 정렬에서 사용. 

6. O(2의 n승) "Exponential Time"

백트래킹 알고리즘, subsets

7. O(n!) "n-factorial"

Permutation 에 사용.



