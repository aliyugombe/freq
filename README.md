# frequest
This is go CLI tool for send fast Multiple  get HTTP request.
forked from https://github.com/takshal/freq and I modified it to print only suspected endpoints for saving to text file

# How to Use?
`echo domain | waybackurls | gf xss | qsreplace '"><img src=x onerror=alert(1);>' | freq | tee -a xss-vuln.txt`

# How to Install?
```
go install -v github.com/aliyugombe/freq
```

# Credit
Credit goes to takshal tojojo https://github.com/takshal/freq for bringing the first idea
