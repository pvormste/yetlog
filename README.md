[![GoDoc](https://godoc.org/github.com/pvormste/yetlog?status.svg)](https://godoc.org/github.com/pvormste/yetlog) ![](https://github.com/pvormste/yetlog/workflows/lint/badge.svg)

# yetlog (Yet (Another) Logger)

`yetlog` provides a universal logger interface.

## Install

```bash
go get -u github.com/pvormste/yetlog
```

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
