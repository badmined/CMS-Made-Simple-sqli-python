# CMS-Made-Simple-sqli-python
CMS Made Simple &lt; 2.2.10 - SQL Injection updated code for python
CMS Made Simple < 2.2.10 - SQL Injection (rewritten for python3), CVE-2019-9053

I found it problematic to run this exploit on kali linux, since python2 doesn't have termcolor, so with very few brackets I made it working with python3. All credit goes to: https://www.exploit-db.com/exploits/46635

I tested it against a cms vulnerable machine on https://tryhackme.com . It is working as intended

 Specify an url target
```
python3 cmssimple.py
```

 Example usage (no cracking password):
```
python3 cmssimple.py -u http://target-uri
```

 Example usage (with cracking password): 
```
python3 cmssimple.py -u http://target-uri --crack -w /path-wordlist
```





