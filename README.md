# one-liners

This aims at listing day-to-day useful one-liners.

## HTTP

Run an HTTP server in the current directory:

```bash
# Python 2
python -m SimpleHTTPServer

# Python 3
python -m http.server
```

[Improved scripted version (better case and encoding support)](https://github.com/MattiSG/DotFiles/blob/master/functions/serve.sh)

## SMTP

Run a SMTP server that dumps messages to the standard output:

```bash
python -m smtpd -n -c DebuggingServer localhost:1025
```
