Q 12 equal arrays
import numpy as geek  

   

a  = geek.equal([1., 2.], [1., 3.]) 

print("Check to be Equal : \n", a, "\n") 

   

b = geek.equal([1, 2], [[1, 3],[1, 4]]) 

print("Check to be Equal : \n", b, "\n") 

Q1
def is_palindrome(arr):
 start = 0
 end = len(arr)-1
 while start < end:
    if arr[start] != arr[end]:
      return False
    start +=1
    end -=1
  return True
assert is_palindrome('a')== True
assert is_palindrome('aba') == True
assert is_palindrome('abba') == True

Q2
let f =

s=>n=>[...s].reduce((s,c)=>n<0?c.repeat(-n)+s:s+c.repeat(n),'')

console.log(f(`Hello World!`)(3))
console.log(f(`foo`)(12))
console.log(f(`String`)(-3))
console.log(f(`This is a fun challenge`)(0))
console.log(f(`Hello
World!`)(2)

Q8

In [10]: import pandas as pd

In [11]: import numpy as np

In [12]: df = pd.DataFrame({'start': [1, 2, 3], 'end': [7, 9, 9]})

In [13]: df
Out[13]:
   end  start
0    7      1
1    9      2
2    9      3

In [14]: def fun(df):
    ...:     return pd.Series(np.arange(df['start'], df['end'], 1))
    ...:

In [15]: df.apply(fun, axis=1)
Out[15]:
     0    1    2    3    4    5    6
0  1.0  2.0  3.0  4.0  5.0  6.0  NaN
1  2.0  3.0  4.0  5.0  6.0  7.0  8.0
2  3.0  4.0  5.0
