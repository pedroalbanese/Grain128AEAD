# grain
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/grain/blob/master/LICENSE.md) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/Grain128AEAD?status.png)](http://godoc.org/github.com/pedroalbanese/grain)
[![GitHub downloads](https://img.shields.io/github/downloads/pedroalbanese/grain/total.svg?logo=github&logoColor=white)](https://github.com/pedroalbanese/grain/releases)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/grain)](https://goreportcard.com/report/github.com/pedroalbanese/grain)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/grain)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/grain)](https://github.com/pedroalbanese/grain/releases)  

Grain is a stream cipher submitted to eSTREAM in 2004 by Martin Hell, Thomas Johansson and Willi Meier. It has been selected for the final eSTREAM portfolio for Profile 2 by the eSTREAM project. Grain is designed primarily for restricted hardware environments. It accepts an 80-bit key and a 64-bit IV. The specifications do not recommended a maximum length of output per (key, iv) pair. A number of potential weaknesses in the cipher have been identified and corrected in Grain 128a which is now the recommended cipher to use for hardware environments providing both 128bit security and authentication. 
### Command-line Grain128AEAD Encryption Tool. 
<pre>Usage of grain:
grain [-d] -p "pass" [-i N] [-s "salt"] -f &lt;file.ext&gt;
  -a string
        Additional Associated Data.
  -d    Decrypt instead of Encrypt.
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
