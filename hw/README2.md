# 作業 2

1. 請寫一個程式可以印出指定數量的 * 號

例如： star(5) 會印出 5 個 * 號

star(5) 

*****

2. 請寫一個函數可以印出 a..b 之間的所有整數

例如： between(3,8) 會印出 

3 4 5 6 7 8

## 第一題


  
3 4 5 6 7 8

---
### 檔案 

  hw2.js

```js
function st(n) {
    for (var i=0; i<n; i++)
    console.log('*')
}
st(5)
function bt(x,y){
for (var i=x; i<=y; i++ )
     console.log(i)
}
bt(3,8)
```

### 執行結果
```
PS C:\Users\User\Desktop\NQU@\NQU\VScode jstest\hw> deno run hw2.js
*
*
*
*
*
3
4
5
6
7
8
```
