<p align="center"><a href="#readme"><img src="https://gh.kaos.st/go-zabbix.svg"/></a></p>

<p align="center">
  <a href="https://godoc.org/pkg.re/essentialkaos/zabbix.v1"><img src="https://godoc.org/pkg.re/essentialkaos/zabbix.v1?status.svg"></a>
  <a href="https://goreportcard.com/report/github.com/essentialkaos/zabbix"><img src="https://goreportcard.com/badge/github.com/essentialkaos/zabbix"></a>
  <a href="https://travis-ci.org/essentialkaos/zabbix"><img src="https://travis-ci.org/essentialkaos/zabbix.svg"></a>
  <a href="https://codebeat.co/projects/github-com-essentialkaos-zabbix"><img alt="codebeat badge" src="https://codebeat.co/badges/a8a976b8-8fdc-4a65-8a4b-754c284db842" /></a>
  <a href="https://essentialkaos.com/ekol"><img src="https://gh.kaos.st/ekol.svg"></a>
</p>

<p align="center"><a href="#installation">Installation</a> • <a href="#build-status">Build Status</a> • <a href="#license">License</a></p>

<br/>

`zabbix` is a Go package for sending metrics data to Zabbix Server 3+.

### Installation

Before the initial install allows git to use redirects for [pkg.re](https://github.com/essentialkaos/pkgre) service (_reason why you should do this described [here](https://github.com/essentialkaos/pkgre#git-support)_):

```
git config --global http.https://pkg.re.followRedirects true
```

For install, do:

```
go get pkg.re/essentialkaos/zabbix.v1
```

For update to latest stable release, do:

```
go get -u pkg.re/essentialkaos/zabbix.v1
```

### Build Status

| Branch | Status |
|--------|--------|
| `master` | [![Build Status](https://travis-ci.org/essentialkaos/zabbix.svg?branch=master)](https://travis-ci.org/essentialkaos/zabbix) |
| `develop` | [![Build Status](https://travis-ci.org/essentialkaos/zabbix.svg?branch=develop)](https://travis-ci.org/essentialkaos/zabbix) |

### License

[EKOL](https://essentialkaos.com/ekol)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
