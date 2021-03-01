# Only working repl.it scraper as of 28/02/2021 (that doesn't just return the URL)

Downloads the repl.it repository as a .zip file, extracts, then looks for a discord token.

Code is ugly I know, but it works.

Not gonna be extremely fast. Deal with it.

I was too lazy to partition it into multiple files.


```YAML
How to build:
go build -ldflags "-s -w"

Don't want to build it for whatever reason? (here's a way to run it through source):
go run main.go
```
