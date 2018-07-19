Simple http proxy for telegram api use in China.

```
Usage:
  go-proxy --bind addr:port hosts...
```

```
go get -v -u github.com/caiguanhao/go-proxy
go-proxy --bind :8888 api.telegram.org:443
```

Reference: [HTTP(S) Proxy in Golang in less than 100 lines of code](https://medium.com/@mlowicki/http-s-proxy-in-golang-in-less-than-100-lines-of-code-6a51c2f2c38c)
