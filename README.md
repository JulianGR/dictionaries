# Dictionaries
+ Custom wordlists for fuzzing (forked from SecLists - credits: https://github.com/danielmiessler/SecLists).
+ Also good to check out: https://wiki.skullsecurity.org/index.php?title=Passwords
+ https://security.stackexchange.com/questions/1376/where-can-i-find-good-dictionaries-for-dictionary-attacks
+ Alternative to seclists: https://wordlists.assetnote.io/

All of the combined wordlists are medium size: perfect for CTFs and regular pentesting, but not for bug bounty since they may be too short.


# Tools for combining wordlists
+ https://github.com/sts10/tidy

```shell
tidy 1.txt 2.txt  -O -q -C -o dic_combinado.txt
```

There also exists https://s1gh.sh/tool-listcombine/ but is slower


# General
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/big-list-of-naughty-strings.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/quickhits.txt

## Symbols
+ https://github.com/JulianGR/dictionaries/blob/main/symbols.txt

### Spanish
**spanish_general.txt: https://github.com/JulianGR/dictionaries/blob/main/spanish_general.txt**
Dictionary with all words from spanish dictionary

Combination of:
+ https://www.openwall.com/wordlists/
+ https://security.stackexchange.com/questions/1376/where-can-i-find-good-dictionaries-for-dictionary-attacks
+ https://web.archive.org/web/20120207113205/http://www.insidepro.com/eng/download.shtml



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



//TODO: combination of api file 

### Spanish

**spanish_directories.txt: https://github.com/JulianGR/dictionaries/blob/main/spanish_directories.txt**

⚠️ It only contains words that are NOT in directories_combined.txt. The idea is to, **FIRST** use directories_combined.txt **AND THEN** use spanish_directories.txt

Combination of:
+ Manual translation of directories_combined.txt
+ https://web.archive.org/web/20120207113205/http://www.insidepro.com/eng/download.shtml
+ https://github.com/xmendez/wfuzz/tree/master/wordlist/general
+ https://github.com/v0re/dirb/blob/master/wordlists/spanish.txt
+ https://github.com/fuzzdb-project/fuzzdb/blob/master/discovery/predictable-filepaths/filename-dirname-bruteforce/spanish.txt
+ https://github.com/SooLFaa/fuzzing/blob/master/Dictionary-Lists-master/Dictionary-Lists/Wordlists/spanish.txt



# Subdominios

+ https://github.com/theMiddleBlue/DNSenum/blob/master/wordlist/subdomains-top1mil-20000.txt





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



## JavaScript events for XSS

+ https://github.com/JulianGR/dictionaries/blob/main/xss-events.txt

# LFI
+ https://github.com/danielmiessler/SecLists/blob/master/Fuzzing/LFI/LFI-Jhaddix.txt


# Files

files-combined.txt: https://github.com/JulianGR/dictionaries/blob/main/files-combined.txt

//TODO
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/Common-PHP-Filenames.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/LinuxFileList.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/Randomfiles.fuzz.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/UnixDotfiles.fuzz.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-large-files-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-large-files.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-medium-files-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-medium-files.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-small-files-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-small-files.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/versioning_metafiles.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/combined_words.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/combined_directories.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-medium-files.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/raft-small-files.txt




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
+ /SecLists/blob/master/Discovery/Web-Content/api/objects-lowercase.txt (slash) /SecLists/blob/master/Discovery/Web-Content/api/actions-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/actions-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/objects-lowercase.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/api-seen-in-wild.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/api-endpoints-res.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/api-endpoints.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/salesforce-aura-objects.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/api/ispsystem_billmanager_api.txt







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



**top-passwords.txt: https://github.com/JulianGR/dictionaries/blob/main/top-passwords.txt**
Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/best15.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/top-20-common-SSH-passwords.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/top-passwords-shortlist.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/darkweb2017-top10.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/xato-net-10-million-passwords-10.txt
+ First 30 lines of https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10-million-password-list-top-100.txt


### Spanish
**spanish_passwords.txt: https://ns2.elhacker.net/wordlists/rockealo.txt.gz**
Spanish version of rockyou



# Default passwords

+ https://cirt.net/passwords
+ https://default-password.info/
+ https://datarecovery.com/rd/default-passwords/


# Usernames

**usernames-combined.txt: https://github.com/JulianGR/dictionaries/blob/main/usernames-combined.txt**

Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Usernames/top-usernames-shortlist.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Passwords/UserPassCombo-Jay.txt



**top-usernames.txt: https://github.com/JulianGR/dictionaries/blob/main/top-usernames.txt**
Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Usernames/top-usernames-shortlist.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Usernames/mssql-usernames-nansh0u-guardicore.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Usernames/sap-default-usernames.txt


### Spanish
**spanish_usernames.txt: //TODO**


# JWT secrets

+ https://github.com/wallarm/jwt-secrets/blob/master/jwt.secrets.list

# SAP

**sap.txt: https://github.com/JulianGR/dictionaries/blob/main/sap.txt**
**sap-reduced.txt: https://github.com/JulianGR/dictionaries/blob/main/sap-reduced.txt**

Combination of:
+ https://gist.github.com/0x240x23elu/88327494cf7331008a13bc7d5aabfe74
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/CMS/SAP.fuzz.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/SAP-NetWeaver.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/sap-analytics-cloud.txt
+ https://github.com/danielmiessler/SecLists/blob/master/Discovery/Web-Content/URLs/urls-SAP.txt
  
## SAP usernames, passwords and default credentials


**sap-usernames.txt: https://github.com/JulianGR/dictionaries/blob/main/sap-usernames.txt**

Combination of:
+ https://github.com/danielmiessler/SecLists/blob/master/Usernames/sap-default-usernames.txt

**sap-passwords.txt: https://github.com/JulianGR/dictionaries/blob/main/sap-passwords.txt**
Combination of:
+ https://help.sap.com/docs/SAP_NETWEAVER_700/12a2bc096c53101493cef874af478673/3ecdaccbedc411d3a6510000e835363f.html
+ https://www.wallsec.de/blog/sap-default-passwords
+ https://github.com/OWASP/pysap/blob/master/examples/default_sap_credentialsç
+ https://www.cisoplatform.com/profiles/blogs/sap-netweaver-abap-security-configuration-part-2-default

Clients:
```
000
001
066
```




# Bug bounty
Massive dictionaries
+ https://github.com/six2dez/OneListForAll

