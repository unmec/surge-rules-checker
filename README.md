# surge-rules-checker
Check duplicate DOMAIN-SUFFIX rules for ss clients such as Surge, Quantumult or Shadowrocket

### How to run
put the your rules.conf file that contains only DOMAIN-SUFFIX rules in ./

```node check-rules.js```

duplicate rules will be flagged in console, you can then manually search and delete them.

output example

<img src="https://raw.githubusercontent.com/unmec/surge-rules-checker/master/output.jpg" width = "441" height = "123" alt="output" align=left />
