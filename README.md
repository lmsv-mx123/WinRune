# WinRune
An simulated rune client from Runescape 1 era, using the mudclient177-deob.

## Usage:
`java -jar ./rune.jar members=<members> address=<ip address> port=<port> rsaExponent=<RSA Exponent> rsaModulus=<RSA Modulus>`

* `<members>`
  * pass true to tell client to load members config or false to load free config
* `<ip address>`
  * an IPv4 address where the RSC177 compatible server is hosted
* `<port>`
  * network port number (e.g. 43594)
* `<RSA Exponent>`
* `<RSA Modulus>`
  * These two are used together to encrypt password, unique to each server

## Changes from original:
1. Original client loaded an html page containing the applet, which since 2015 is no longer supported
2. A static background image is set to style 2003, where the top banner is fixed
3. Command line arguments to help facilitate changing the client's endpoint
