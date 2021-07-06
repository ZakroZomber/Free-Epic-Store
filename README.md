Free on Epic
A discord bot that tells you what the free games on the Epic Store are

$ go get
$ go build main.go
$ ./main -url "[your channel webhook URL]"
Run as a cron (7pm every day):

0 19 * * * ./main -url "[your channel webhook URL]" > /dev/null 2>&1
Build for DigitalOcean Ubuntu 16.4:

$ env GOOS=linux GOARCH=amd64 go build main.go
