<h1 align="center">
  <br>
  <a href=""><img src="/img/logo.png" alt="" width="400px;"></a>
  <br>
  <img src="https://img.shields.io/badge/PRs-welcome-blue">
  <img src="https://img.shields.io/github/last-commit/kh4sh3i/DevSecOps">
  <img src="https://api.codacy.com/project/badge/Grade/e5fd334a431848dcb6ecdb3784fb5dfb">
  <a href="https://twitter.com/intent/follow?screen_name=kh4sh3i_"><img src="https://img.shields.io/twitter/follow/kh4sh3i_?style=flat&logo=twitter"></a>
  <a href="https://github.com/kh4sh3i"><img src="https://img.shields.io/github/stars/kh4sh3i?style=flat&logo=github"></a>
</h1>

# Nextcloud penetration testing
A penetration tester’s guide for Nextcloud exploit and penetration testing 


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
41. [Stored XSS on Share-popup of a directory's Gallery-view](https://hackerone.com/reports/145355) to Nextcloud - 22 upvotes, $750
42. [Ratelimiting can be bypassed using IPv6 subnets](https://hackerone.com/reports/1154003) to Nextcloud - 21 upvotes, $250
43. [XSS in PDF Viewer](https://hackerone.com/reports/819863) to Nextcloud - 21 upvotes, $100
44. [https://help.nextcloud.com::: Web cache poisoning attack](https://hackerone.com/reports/429747) to Nextcloud - 21 upvotes, $0
45. ["Secure View" aka "Hide Download" can be bypassed easily](https://hackerone.com/reports/788257) to Nextcloud - 20 upvotes, $100
46. [Session fixation on public talk links](https://hackerone.com/reports/1181962) to Nextcloud - 20 upvotes, $100
47. [XSS through image upload of contacts using svg file with png extension ](https://hackerone.com/reports/998422) to Nextcloud - 20 upvotes, $0
48. [Notification implicit PendingIntent in com.nextcloud.client allows to access contacts](https://hackerone.com/reports/1161401) to Nextcloud - 19 upvotes, $250
49. [SMTP Command Injection in iCalendar Attachments to Emails via Newlines](https://hackerone.com/reports/1516377) to Nextcloud - 19 upvotes, $250
50. [SQLi allow query restriction bypass on exposed FileContentProvider](https://hackerone.com/reports/518669) to Nextcloud - 19 upvotes, $100
51. [Gallery: No feedback for invalid password](https://hackerone.com/reports/428660) to Nextcloud - 19 upvotes, $50
52. [OAuth2 Access Token and App Password Security Vulnerability](https://hackerone.com/reports/343111) to Nextcloud - 18 upvotes, $400
53. [Log pollution can lead to HTML Injection.](https://hackerone.com/reports/146278) to Nextcloud - 18 upvotes, $350
54. [Username and Access Token Disclousure](https://hackerone.com/reports/672623) to Nextcloud - 18 upvotes, $250
55. [Denial of Service by requesting to reset a password](https://hackerone.com/reports/812754) to Nextcloud - 18 upvotes, $250
56. [XSS through image upload of contacts using svg file](https://hackerone.com/reports/894876) to Nextcloud - 18 upvotes, $100
57. [Session fixation in password protected public download.](https://hackerone.com/reports/237184) to Nextcloud - 18 upvotes, $50
58. [Server side request forgery (SSRF) on nextcloud implementation.](https://hackerone.com/reports/145524) to Nextcloud - 18 upvotes, $0
59. [bypass of 2FA](https://hackerone.com/reports/248656) to Nextcloud - 17 upvotes, $750
60. [Folder architecture and Filesizes of private file drop shares can be getten](https://hackerone.com/reports/1337422) to Nextcloud - 17 upvotes, $500
61. [SSRF protection bypass](https://hackerone.com/reports/736867) to Nextcloud - 17 upvotes, $100
62. [Ransomware protection is missing extentions take 2](https://hackerone.com/reports/1200785) to Nextcloud - 17 upvotes, $100
63. [public webdav endpoint not bruteforce protected](https://hackerone.com/reports/1192159) to Nextcloud - 17 upvotes, $100
64. [Reflected XSS / Markup Injection in `index.php/svg/core/logo/logo` parameter `color`](https://hackerone.com/reports/605915) to Nextcloud - 17 upvotes, $50
65. [IDOR unsubscribe Anyone from NextClouds Newsletters by knowing their Email ](https://hackerone.com/reports/230328) to Nextcloud - 17 upvotes, $0
66. [DOM XSS vulnerability in search dialogue (NC-SA-2017-007)](https://hackerone.com/reports/213227) to Nextcloud - 16 upvotes, $250
67. [User with read-only access to a share can gain write access to sub-folders in the share](https://hackerone.com/reports/619484) to Nextcloud - 16 upvotes, $250
68. [Clients do not verify server public key](https://hackerone.com/reports/1192470) to Nextcloud - 16 upvotes, $250
69. [Sensitive files/ data exists  post deletion of user account](https://hackerone.com/reports/1222873) to Nextcloud - 16 upvotes, $150
70. [Access control issue -- [Allow file system access not validated when using session auth]](https://hackerone.com/reports/388515) to Nextcloud - 16 upvotes, $100
71. [XSS in desktop client via invalid server address on login form](https://hackerone.com/reports/685552) to Nextcloud - 16 upvotes, $100
72. [Reflected XSS when renaming a file with a vulnerable name which results in an error](https://hackerone.com/reports/896522) to Nextcloud - 16 upvotes, $100
73. [Response Header injection using redirect_uri together with PHP that utilizes Header Folding according to RFC1945 and Internet Explorer 11](https://hackerone.com/reports/145392) to Nextcloud - 16 upvotes, $0
74. [Possible denial of service when entering a loooong password](https://hackerone.com/reports/952349) to Nextcloud - 16 upvotes, $0
75. [Access control missing while viewing the attachments in the "All boards"](https://hackerone.com/reports/916704) to Nextcloud - 15 upvotes, $150
76. [Non-admin users can trigger writes to memcached by entering a malicious server as a share URL](https://hackerone.com/reports/592864) to Nextcloud - 15 upvotes, $100
77. [Missing server side controls when editing the board’s sharing permissions per user](https://hackerone.com/reports/827816) to Nextcloud - 15 upvotes, $100
78. [Authentication Issue](https://hackerone.com/reports/146133) to Nextcloud - 15 upvotes, $50
79. [Android - Possible to intercept broadcasts about uploaded files](https://hackerone.com/reports/167481) to Nextcloud - 15 upvotes, $0
80. [Registered users can change app password permissions for any user](https://hackerone.com/reports/297751) to Nextcloud - 14 upvotes, $100
81. [Nextcloud domain and name of every user leaked to lookup server](https://hackerone.com/reports/508490) to Nextcloud - 14 upvotes, $100
82. [Docker image with FPM is vulnerable to CVE-2019-11043](https://hackerone.com/reports/720306) to Nextcloud - 14 upvotes, $100
83. [Unrestricted file upload on the image of contacts](https://hackerone.com/reports/808287) to Nextcloud - 14 upvotes, $100
84. [When sharing a Deck card in conversation the metaData can be manipulated to open arbitrary URL](https://hackerone.com/reports/1358977) to Nextcloud - 14 upvotes, $100
85. [Nextcloud 10.0 privilege escalation issue - Normal user can mask external storage shared by admin    ](https://hackerone.com/reports/165229) to Nextcloud - 14 upvotes, $50
86. [Unauthenticated Stored xss ](https://hackerone.com/reports/168054) to Nextcloud - 14 upvotes, $0
87. [https://xmpp.nextcloud.com///;@www.google.com allows open redirect](https://hackerone.com/reports/211213) to Nextcloud - 14 upvotes, $0
88. [Content Spoofing /Text Injection in https://docs.nextcloud.com](https://hackerone.com/reports/666557) to Nextcloud - 14 upvotes, $0
89. [File drop public link can also be converted to federated share](https://hackerone.com/reports/1167929) to Nextcloud - 13 upvotes, $500
90. [Linux client is vulnerable to directory traversal when downloading files](https://hackerone.com/reports/590319) to Nextcloud - 13 upvotes, $250
91. [Only the file extensions are checked, not the MIME types as configured](https://hackerone.com/reports/697959) to Nextcloud - 13 upvotes, $175
92. [Combination of content provider allows private data disclosure](https://hackerone.com/reports/534541) to Nextcloud - 13 upvotes, $100
93. [Delete permission can be added on reshare](https://hackerone.com/reports/633245) to Nextcloud - 13 upvotes, $100
94. [Access Control: Inject tasks into other users decks](https://hackerone.com/reports/867052) to Nextcloud - 13 upvotes, $100
95. [Android app does not clear end to end encryption keys](https://hackerone.com/reports/1189168) to Nextcloud - 13 upvotes, $100
96. [Talk / spreed: Disclosure of Room names and participants for password protected rooms](https://hackerone.com/reports/428010) to Nextcloud - 13 upvotes, $50
97. [Design Issues on ( ███ ) Lead to show ( IPS of Users ) ](https://hackerone.com/reports/218733) to Nextcloud - 13 upvotes, $0
98. [Content Spoofing/Text Injection in https://demo.nextcloud.com](https://hackerone.com/reports/222058) to Nextcloud - 13 upvotes, $0
99. [Stored XSS in markdown file with Nextcloud Talk using Internet Explorer](https://hackerone.com/reports/1023787) to Nextcloud - 12 upvotes, $150
100. [Virtual Data Room / Hide download on collabora is easy to bypass](https://hackerone.com/reports/1194606) to Nextcloud - 12 upvotes, $150