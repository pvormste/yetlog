[![GoDoc](https://godoc.org/github.com/pvormste/yetlog?status.svg)](https://godoc.org/github.com/pvormste/yetlog)

# yetlog

`yetlog` provides a universal logger interface.

## Usage

```go
func DoSomething(logger yetlog.Logger) {
    logger.Warn("this function is useless", "funcName", "DoSomething")
}
```

## Implementations

| logger | impl. name | impl. repo | 
| ------ | ---------- | ---------- |
| [zap](https://github.com/uber-go/zap) | yetzap | [github.com/pvormste/yetzap](https://github.com/pvormste/yetzap) |