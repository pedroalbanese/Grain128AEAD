# grain
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/grain/blob/master/LICENSE.md) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/grain?status.png)](http://godoc.org/github.com/pedroalbanese/grain)
[![GitHub downloads](https://img.shields.io/github/downloads/pedroalbanese/grain/total.svg?logo=github&logoColor=white)](https://github.com/pedroalbanese/grain/releases)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/grain)](https://goreportcard.com/report/github.com/pedroalbanese/grain)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/grain)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/grain)](https://github.com/pedroalbanese/grain/releases)  

A lightweight AEAD stream cipher submitted to the CAESAR competition for authenticated ciphers. 
### Command-line Grain128AEAD Encryption Tool
<pre>Usage of grain:
grain [-d] -p "pass" [-i N] [-s "salt"] -f &lt;file.ext&gt;
  -d    Decrypt instead Encrypt.
  -f string
        Target file. ('-' for STDIN)
  -i int
        Iterations. (for PBKDF2) (default 1024)
  -k string
        128-bit key to Encrypt/Decrypt.
  -p string
        PBKDF2.
  -r    Generate random 128-bit cryptographic key.
  -s string
        Salt. (for PBKDF2)</pre>

## License

This project is licensed under the ISC License.

##### Industrial-Grade Reliability. Copyright (c) 2020-2022 ALBANESE Research Lab.
