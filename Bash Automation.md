# Bash Automation

This file formatted in IDEA style run script, try open it in IntelliJ IDEA  
Works from file and markdown rendering with good look


GET
----------------------------------------

## Name
- description

```shell
curl -v -H "Accept: application/json" 'http://localhost:8080/' | json_pp
```


## curl parameters
-v, --verbose              Make the operation more talkative

-d, --data <data>          HTTP POST data
-f, --fail                 Fail silently (no output at all) on HTTP errors
-i, --include              Include protocol response headers in the output
-o, --output <file>        Write to file instead of stdout. curl -o out.json http://www.example.com/index.html
-O, --remote-name          Write output to a file named as the remote file
-s, --silent               Silent mode
-T, --upload-file <file>   Transfer local FILE to destination
-u, --user <user:password> Server user and password
-A, --user-agent <name>    Send User-Agent <name> to server

-H, --header <header/@file> Pass custom header(s) to server
-X, --request <method> Change the method to use when starting the transfer. Without it GET