## 函数的一个参数是函数指针(不是闭包), 但是使用的时候, 可以使用闭包的写法, 只是不能捕获变量

## 对已有方法进行过滤
- mod1:
```go
func test(c: char) -> bool {
}
```
- mod2:
```go
func test_filter(c: char) -> bool {
	if c == '\n' {
		return false;
	}
}
```

## 提供作用域结束时的处理方法
- 类似 golang 的 defer() {}() 方法