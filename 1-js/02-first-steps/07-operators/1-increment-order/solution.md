
答案如下：

- `a = 2`
- `b = 2`
- `c = 2`
- `d = 1`

```js run no-beautify
let a = 1, b = 1;

alert( ++a ); // 2，前置操作符返回最新值
alert( b++ ); // 1，后置操作符返回旧值

alert( a ); // 2，自增加一次
alert( b ); // 2，自增加一次
```

