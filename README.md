# Dictionaries
Custom wordlists for fuzzing (forked from SecLists - credits: https://github.com/danielmiessler/SecLists)

All of the combined wordlists are medium size: perfect for CTFs and regular pentesting, but not for bug bounty since they may be too short.



### Tools for combining wordlists
+ https://github.com/sts10/tidy

```shell
tidy 1.txt 2.txt  -O -q -C -o dic_combinado.txt
```

There also exists https://s1gh.sh/tool-listcombine/ but is slower


Alternative wordlists to seclists:
https://wordlists.assetnote.io/


# Directories


**directories_combined.txt: https://github.com/JulianGR/dictionaries/blob/main/directories-combined.txt**


Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/dirsearch.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-medium-directories-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/RobotsDisallowed-Top500.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/common.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/common-and-spanish.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/directory-list-lowercase-2.3-small.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/fuzz-Bo0oM.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/fuzz-Bo0oM-friendly.txt




# Subdominios

+ https://github.com/theMiddleBlue/DNSenum/blob/master/wordlist/subdomains-top1mil-20000.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/quickhits.txt

# General
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/big-list-of-naughty-strings.txt

# SQLi
**sql_combined.txt: https://github.com/JulianGR/dictionaries/blob/main/sql-combined.txt**

Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/SQLi/Generic-SQLi.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/SQLi/quick-SQLi.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/SQLi/Generic-BlindSQLi.fuzzdb.txt



# XSS
**xss_combined.txt: https://github.com/JulianGR/dictionaries/blob/main/xss_combined.txt**

Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/XSS-Fuzzing
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/XSS/XSS-BruteLogic.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/XSS/XSS-Jhaddix.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/XSS/XSS-RSNAKE.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/XSS/XSS-Somdev.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/XSS/xss-without-parentheses-semi-colons-portswigger.txt


# LFI
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/LFI/LFI-Jhaddix.txt


# Files

files-combined.txt: https://github.com/JulianGR/dictionaries/blob/main/files-combined.txt

# XXE
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/XXE-Fuzzing.txt

# SSI
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/SSI-Injection-Jhaddix.txt


# SSTI
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/template-engines-expression.txt


# HTML Injection
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/HTML5sec-Injections-Jhaddix.txt


# Json
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/JSON.Fuzzing.txt

# API

**api.txt: https://github.com/JulianGR/dictionaries/blob/main/api.txt**

Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/objects.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/objects-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/api-seen-in-wild.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/api-endpoints.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/api-endpoints-res.txt







# Passwords

**passwords-combined.txt: https://github.com/JulianGR/dictionaries/blob/main/passwords-combined.txt**

Combination of:
+ First 30k lines of rockyou
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/xato-net-10-million-passwords-10000.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/2020-200_most_used_passwords.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10-million-password-list-top-10000.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10k-most-common.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/best1050.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/common-passwords-win.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/top-20-common-SSH-passwords.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/top-passwords-shortlist.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/worst-passwords-2017-top100-slashdata.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/500-worst-passwords.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Default-Credentials/default-passwords.txt
+ https://github.com/Karmaz95/crimson/blob/master/words/10k_commons_and_keymap.txt
+ https://github.com/Karmaz95/crimson/blob/master/words/credentials.txt




# Usernames

**usernames-combined.txt: https://github.com/JulianGR/dictionaries/blob/main/usernames-combined.txt**

Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Usernames/top-usernames-shortlist.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/UserPassCombo-Jay.txt



