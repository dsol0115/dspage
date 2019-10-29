---
title: "숫자 거꾸로 출력하기 : Reverse the digits"
date: 2019-10-29 10:10:00 -0400
categories: Algorithm
tag: Algorithm
---

숫자 N이 있을 때 자릿수를 거꾸로 출력할 것.

예를 들어 12345 라면 54321로, -123이라면 -321로 출력하기

- 첫번 째 방법: int를 string으로 바꾼 후 거꾸로 출력하기

```
public static int reversenum (int num){
         String str = Integer.toString(Math.abs(num));
         int revnum=0;
         for (int i=str.length()-1; i>=0; i--){
            revnum*=10;
            revnum += Integer.parseInt(str.substring(i,i+1));
         }
         return num>0?revnum : -revnum;
     }
```

- 두번 째 방법: %, / 사용하기

```
public static int reversenum (int num){
        int revernum =0;
        int remain = Math.abs(num);
        while(remain>0){
            revernum*=10;
            revernum+=remain%10;
            remain/=10;
        }
        return num>0?revernum : -revernum;
     }
```