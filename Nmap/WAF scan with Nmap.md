# WAF detection scan with Nmap
```
nmap <target-ip> --script=http-waf-detect
ex:
nmap example.com --script=http-waf-detect -p 80,443 -v
-v - for verbose
```
# WAF fingerprint scan with Nmap
```
nmap <target-ip> --script=http-waf-fingerprint
ex:
nmap example.com --script=http-waf-fingerprint -p 80,443 -v
```
