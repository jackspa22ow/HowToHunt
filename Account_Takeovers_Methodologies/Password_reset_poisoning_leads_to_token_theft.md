# PASSWORD RESET POISIONING LEADS TO TOKEN THEFT
```
1.Go to password reset funtion.
2.Enter email and intercept the request.
3.Change host header to some other host i.e,
    Host:target.com
    Host:attacker.com
    -> Prefix and postfix need to check.
    -> X-Forwarded-Host need to check.
4.Forward this if you found that in next request attacker.com means you successfully theft the token.:)
```

### Author
* [@Virdoex_hunter](https://twitter.com/Virdoex_hunter)
