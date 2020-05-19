## Check reponse time from target server

On Linux OS
```
$curl -w "@curl-format.txt" -o /dev/null -s "https://www.google.com/"

    time_namelookup:  0.004307s
       time_connect:  0.041868s
    time_appconnect:  0.142114s
   time_pretransfer:  0.142194s
      time_redirect:  0.000000s
 time_starttransfer:  0.214814s
                    ----------
         time_total:  0.222003s
```

On Windows OS
```
$curl -w "@curl-format.txt" -o NUL -s "https://www.google.com/"

    time_namelookup:  0.004307s
       time_connect:  0.041868s
    time_appconnect:  0.142114s
   time_pretransfer:  0.142194s
      time_redirect:  0.000000s
 time_starttransfer:  0.214814s
                    ----------
         time_total:  0.222003s
```

[Reference website](https://stackoverflow.com/questions/18215389/how-do-i-measure-request-and-response-times-at-once-using-curl)
