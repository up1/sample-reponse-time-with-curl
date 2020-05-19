## Check reponse time from target server

On Linux OS
```
$curl -w "@curl-format.txt" -o /dev/null -s "https://www.google.com/"
```

On Windows OS
```
$curl -w "@curl-format.txt" -o NUL -s "https://www.google.com/"
```