# brutessh
SSH bruteforcer written in Go

## Building

```bash
go build brutessh.go
```

## Usage
```bash
$> brutessh -h                                                                
CAUTION: |worker-count| <= |passwords|
Usage of brutessh:
  -count int
    	Amount of worker working concurrently (default 5)
  -file string
    	File with passwords
  -ip string
    	IP of the SSH server
  -port string
    	Port of the SSH server (default "22")
  -timeout int
    	Timeout per connection in seconds (default 5)
  -user string
    	SSH user to bruteforce
exit status 2
```
## Why

To learn about context, channels, synchro, ...
