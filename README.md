# go-xdr

[![Build Status](https://github.com/diamcircle/go-xdr/workflows/Go/badge.svg)](https://github.com/diamcircle/go-xdr/actions)
[![GoDoc](https://godoc.org/github.com/diamcircle/go-xdr/xdr3?status.png)](http://godoc.org/github.com/diamcircle/go-xdr/xdr3)

Go-xdr implements the data representation portion of the External Data
Representation (XDR) standard protocol as specified in RFC 4506 (obsoletes RFC
1832 and RFC 1014) in Pure Go (Golang).

Version 1 and 2 of this package are available in the `xdr` and `xdr2` packages
respectively. The current version is in the `xdr3` package. diamcircle exclusively
uses the `xdr3` version in `diamcircle/go`.

## Thanks

Thanks to @davecgh for developing the [original go-xdr]. This is a fork of @davecgh's
module. This version diverged and adds a new `xdr3` package which was a copy of
`xdr2` but has added optionals, automatic enum deciding, union decoding,
changes to pointer decoding, ability to constrain sizes and some fixes.

## License

Licensed under the ISC License.

[original go-xdr]: https://github.com/davecgh/go-xdr
