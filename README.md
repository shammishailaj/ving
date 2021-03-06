[![Go Report Card](https://goreportcard.com/badge/github.com/yittg/ving)](https://goreportcard.com/report/github.com/yittg/ving)

# 🐸 ving

`ving` is a visualization ping utility written in Golang(1.11+).
Special thanks to the amazing [termui](https://github.com/gizak/termui) library.

# 🦁 Features

* ping multiple targets independently at once;
* ping gateway conveniently, `-g`;
* ping interval option, `-i`;
* error rate and speed statistics in sliding window, as emoji;
* responsive terminal display (based on termui).

# 🙈 Install

```
$ go get -u github.com/yittg/ving
```

# ⚡ Usage

```
$ ving 192.168.0.1 127.0.0.1 8.8.8.8

$ ving -i 100ms 192.168.0.1

$ ving -g
```

![](./assets/screenshot.png)
