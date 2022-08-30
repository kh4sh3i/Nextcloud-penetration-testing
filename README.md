<h1 align="center">
  <br>
  <a href=""><img src="/img/logo.png" alt="" width="300px;"></a>
  <br>
  <img src="https://img.shields.io/badge/PRs-welcome-blue">
  <img src="https://img.shields.io/github/last-commit/kh4sh3i/Nextcloud-penetration-testing"> 
  <img src="https://img.shields.io/github/commit-activity/m/kh4sh3i/Nextcloud-penetration-testing">
  <a href="https://twitter.com/intent/follow?screen_name=kh4sh3i_"><img src="https://img.shields.io/twitter/follow/kh4sh3i_?style=flat&logo=twitter"></a>
  <a href="https://github.com/kh4sh3i"><img src="https://img.shields.io/github/stars/kh4sh3i?style=flat&logo=github"></a>
</h1>

# Nextcloud penetration testing
A penetration tester’s guide for Nextcloud exploit and penetration testing 


## What is Nextcloud used for?
the free Nextcloud clients for Android, iOS and desktop systems allow you to sync and share files, in a fully secure way through an encrypted connection. The mobile clients feature automatic upload of pictures and videos you take and can synchronize select files and folders.


# 1.Recon

## find version
```
https://target/status.php
```

## find api
```
https://target/ocs-provider/
```



## Nextcloud Detection
```
nuclei -u target -t nextcloud-detect.yaml
```

# 2.Exploit
## brureforce api 
```
https://target/public.php/webdav
https://target/remote.php/dav/files/USERNAME/
```


## Nextcloud Exposed Installation
```
nuclei -u target -t nextcloud-install.yaml
```

# 3. Recommend
disable the web-based upgrader
simply set 'upgrade.disable-web' => true, in nextcloud’s config.php with this result:

```
https://target/updater/
```




# 4. Reports
## Nextcloud program at HackerOne

1. [Code injection possible with malformed Nextcloud Talk chat commands](https://hackerone.com/reports/851807) to Nextcloud - 314 upvotes, $3000
2. [User can delete data in shared folders he's not autorized to access](https://hackerone.com/reports/642515) to Nextcloud - 165 upvotes, $250
3. [Access to all files of remote user through shared file](https://hackerone.com/reports/258084) to Nextcloud - 149 upvotes, $750
4. [Attacker can obtain write access to any federated share/public link](https://hackerone.com/reports/1170024) to Nextcloud - 135 upvotes, $4000
5. [Missing ownership check on remote wipe endpoint](https://hackerone.com/reports/819807) to Nextcloud - 127 upvotes, $500
6. [Remote Code Execution via Extract App Plugin](https://hackerone.com/reports/546753) to Nextcloud - 121 upvotes, $0
7. [Re-Sharing allows increase of privileges](https://hackerone.com/reports/889243) to Nextcloud - 90 upvotes, $750
8. [No rate limiting for confirmation email lead to huge Mass mailings](https://hackerone.com/reports/997070) to Nextcloud - 78 upvotes, $0
9. [User deletion is not handled properly everywhere](https://hackerone.com/reports/1200700) to Nextcloud - 75 upvotes, $1000
10. [Arbitrary SQL command injection](https://hackerone.com/reports/508487) to Nextcloud - 73 upvotes, $500
11. [Nextcloud Desktop Client RCE via malicious URI schemes](https://hackerone.com/reports/1078002) to Nextcloud - 72 upvotes, $1000
12. [File-drop content is visible through the gallery app](https://hackerone.com/reports/719426) to Nextcloud - 68 upvotes, $500
13. [Arbitrary code execution in desktop client via OpenSSL config](https://hackerone.com/reports/622170) to Nextcloud - 59 upvotes, $100
14. [Extremly simple way to bypass Nextcloud-Client PIN/Fingerprint lock](https://hackerone.com/reports/331489) to Nextcloud - 56 upvotes, $100
15. [Default Nextcloud Server and Android Client leak sharee searches to Nextcloud](https://hackerone.com/reports/1167916) to Nextcloud - 53 upvotes, $750
16. [Clear text storage of proxy parameters and passwords](https://hackerone.com/reports/685990) to Nextcloud - 53 upvotes, $250
17. [Stored XSS in collabora via user name](https://hackerone.com/reports/968232) to Nextcloud - 48 upvotes, $0
18. [Two-factor authentication enforcement bypass](https://hackerone.com/reports/1050244) to Nextcloud - 46 upvotes, $750
19. [SSL certificate not validated when registering with a provider](https://hackerone.com/reports/903424) to Nextcloud - 42 upvotes, $300
20. [Memory Leak in OCUtil.dll library in Desktop client can lead to DoS](https://hackerone.com/reports/588562) to Nextcloud - 40 upvotes, $100
21. [[Reflected XSS] In Request URL](https://hackerone.com/reports/515484) to Nextcloud - 37 upvotes, $50
22. [Remote code execution via path traversal in Zip extraction in the Extract app](https://hackerone.com/reports/765291) to Nextcloud - 37 upvotes, $0
23. [http://www.nextcloud.com/wp-includes/js/swfupload/swfupload.swf allows open redirect / site defacement](https://hackerone.com/reports/209520) to Nextcloud - 37 upvotes, $0
24. [Scoped apptokens can be changed by that very apptoken](https://hackerone.com/reports/1193321) to Nextcloud - 36 upvotes, $1000
25. [Expired reshare links allow access to all files in share](https://hackerone.com/reports/452854) to Nextcloud - 36 upvotes, $400
26. [No session logout after changing password & alsoandroid sessions not shown in sessions list so they can be deleted](https://hackerone.com/reports/194329) to Nextcloud - 35 upvotes, $50
27. [Cross site scripting - XSRF Token](https://hackerone.com/reports/858255) to Nextcloud - 32 upvotes, $0
28. [2FA Session not expires after the password reset](https://hackerone.com/reports/486693) to Nextcloud - 31 upvotes, $50
29. [SQL Injection found in NextCloud Android App Content Provider](https://hackerone.com/reports/291764) to Nextcloud - 30 upvotes, $150
30. [Group admins can remove arbitrary data from "data" directory (including admin data)](https://hackerone.com/reports/508493) to Nextcloud - 30 upvotes, $150
31. [Passwords being stored as plain text in logging](https://hackerone.com/reports/469668) to Nextcloud - 30 upvotes, $0
32. [I am because bug](https://hackerone.com/reports/226097) to Nextcloud - 29 upvotes, $0
33. [Reflected XSS in error pages (NC-SA-2017-008)](https://hackerone.com/reports/216812) to Nextcloud - 28 upvotes, $450
34. [Code injection in macOS Desktop Client ](https://hackerone.com/reports/633266) to Nextcloud - 28 upvotes, $250
35. [Database error shown to the user when using a long guest name in richdocuments](https://hackerone.com/reports/1067824) to Nextcloud - 28 upvotes, $0
36. [CSRF vulnerability that allows an attacker to modify encryption settings](https://hackerone.com/reports/630146) to Nextcloud - 27 upvotes, $0
37. [Persistent XSS via filename in projects](https://hackerone.com/reports/662204) to Nextcloud - 23 upvotes, $150
38. [Blind Stored XSS on iOS App due to Unsanitized Webview](https://hackerone.com/reports/575562) to Nextcloud - 23 upvotes, $100
39. [Leak arbitrary file under nextcloud android client privacy directory](https://hackerone.com/reports/1142918) to Nextcloud - 23 upvotes, $100
40. [Bypass of privacy filter / tracking pixel blocker](https://hackerone.com/reports/1215251) to Nextcloud - 23 upvotes, $100



## refrencess
* [nextcloud docs](https://docs.nextcloud.com/server/latest/admin_manual/index.html)
* [disable the web-based upgrader](https://community.nethserver.org/t/nextcloud-disable-the-web-based-upgrader/18685)