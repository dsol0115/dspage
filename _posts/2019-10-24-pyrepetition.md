---
title: "파이썬 중복값 제거"
date: 2019-10-24 10:10:00 -0400
categories: Python
tag: Python 
---

파이썬 자료형 set의 성질을 이용하면 쉽게 중복값을 제거할 수 있다.

```
oldstr = [1,2,3,4,5,1,3,5]
newstr = list(set(oldstr)) #리스트를 set으로 바꿨다가 다시 리스트로 바꿈
print(newstr)
```

```
[1, 2, 3, 4, 5]
```





