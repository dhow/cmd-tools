# cmd-tools
My command-line tools for Linux

## check-tls

Check TLS version and certificate expiry. 
On a side note, [testssl.sh][1] does a far better job :smile:.

[1]: https://github.com/drwetter/testssl.sh

```
$ check-tls google.com
TLS 1.0: Supported
TLS 1.1: Supported
TLS 1.2: Supported
Cert valid: notAfter=Mar  3 08:42:43 2020 GMT
```
