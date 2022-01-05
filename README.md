# goanda

forked from https://github.com/AwolDes/goanda with the intent to create versioned releases and maintain a Go module

---

A Golang wrapper for the [OANDA v20 API](http://developer.oanda.com/rest-live-v20/introduction/). Currently OANDA has wrappers for Python, Javascript and Java. Goanda exists to extend upon those languages because of the increasing popularity of Go and for a side prject I'm working on.

## Use

`go get github.com/cconcannon/goanda`

```go
oanda := goanda.NewConnection(accountID, key, false)
history := oanda.GetCandles("EUR_USD", "10", "S5")
```

Check the examples directory for more

### License

This project was created under the [MIT license](https://choosealicense.com/licenses/mit/)
