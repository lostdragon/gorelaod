#goreload

## Zero-downtime restarts in Go

The `goreload` support zero-downtime restarts in go applications that provide HTTP and/or TCP service.

## Installation

    go get github.com/lostdragon/goreload

## Usage
Send `HUP` to a process using `goreload` and it will restart without downtime.

    kill -HUP ${pid}


## Refer

    https://github.com/rcrowley/goagain
    http://grisha.org/blog/2014/06/03/graceful-restart-in-golang/
    https://github.com/mindreframer/golang-stuff/blob/master/github.com/astaxie/beego/reload.go
