# eLearnSecurity Web Application Penetration Tester

Here you can find tips and resources that will help you to pass the eWPT certification from eLearnSecurity.
BTW, [here](https://github.com/CyberSecurityUP/eWPT-Preparation) you can enormous amount of useful links and resources
that are dedicated to the eWPT preparation.

## Content

- [Tips and tricks](#tips-and-tricks)
- [Training resources](#training-resources)
- [Books](#books)
- [Exam reviews](#exam-reviews)
- [Cheat sheets](#cheat-sheets)
- [Vulnerable applications](#vulnerable-applications)
- [OWASP Resources](#owasp-resources)
- [Reporting](#reporting)

## Tips and tricks

**Disclaimer**: I used INE [Web Application Penetration testing](https://my.ine.com/CyberSecurity/courses/38316560/web-application-penetration-testing) course during my preparation. It includes all that you need to pass this exam but during my learning journey I also used other resources that are listed on this page.

- Do all the labs and challenges from the course
- Make notes during the course
- Do an additional research if you want to better understand a specific topic
- Practice, practice, practice. Setup home lab using vulnerable web applications and try to find
as many vulnerabilities as possible
- Prepare a cheat sheet with commands and payloads that you've used in labs
- Automate attacks where possible. It'll come in handy not only during the exam but also in real life engagements
- Know your tools
- Review mitigation strategies for each vulnerability
- Pay attention to reporting and Letter of Engagement
- Do not rush, 14 days is more than enough to complete the pentest and write a report
- Make breaks when you're stuck

## Training resources

- [Web Application Penetration testing course from INE & eLearnSecurity](https://my.ine.com/CyberSecurity/courses/38316560/web-application-penetration-testing)
- [Port Swigger Web Academy](https://portswigger.net/web-security)
- [TryHackMe Beginner Path](https://tryhackme.com/path/outline/beginner)
- [TryHackMe Web Fundamentals Path](https://tryhackme.com/path/outline/web)
- [TryHackMe Jr Penetration Tester Path](https://tryhackme.com/path/outline/jrpenetrationtester)
- [HackTheBox](https://forum.hackthebox.com/tag/web)

## Books

- [Web Hacking 101](https://leanpub.com/web-hacking-101)
- [The Web Application Hacker's Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470)
- [Web Application Security: Exploitation and Countermeasures for Modern Web Applications](https://www.amazon.com/Web-Application-Security-Exploitation-Countermeasures/dp/1492053112/ref=sr_1_1?crid=2GM2DG4TXUW6&dchild=1&keywords=web+security&qid=1617222285&s=books&sprefix=Web+sec%2Cstripbooks-intl-ship%2C262&sr=1-1)
- [Web Security For Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald/dp/1593279949/ref=sr_1_2?crid=2GM2DG4TXUW6&dchild=1&keywords=web+security&qid=1617222285&s=books&sprefix=Web+sec%2Cstripbooks-intl-ship%2C262&sr=1-2)
- [Real-World Bug Hunting: A Field Guide to Web Hacking](https://www.amazon.com/Real-World-Bug-Hunting-Field-Hacking/dp/1593278616/ref=sr_1_10?crid=2GM2DG4TXUW6&dchild=1&keywords=web+security&qid=1617222285&s=books&sprefix=Web+sec%2Cstripbooks-intl-ship%2C262&sr=1-10)

## Exam reviews

- [Extended list of reviews](https://github.com/CyberSecurityUP/eWPT-Preparation#reviews)
- [https://telegra.ph/eWPT-review-10-15](https://telegra.ph/eWPT-review-10-15)
- [https://anontuttuvenus.medium.com/ewpt-review-11208fc43a9a](https://anontuttuvenus.medium.com/ewpt-review-11208fc43a9a)
- [https://robertscocca.medium.com/%EF%B8%8Fewpt-review-the-g-932b1245e51a?source=rss------cybersecurity-5](https://robertscocca.medium.com/%EF%B8%8Fewpt-review-the-g-932b1245e51a?source=rss------cybersecurity-5)
- [https://community.infosecinstitute.com/discussion/129238/elearnsecurity-web-application-penetration-testing-ewpt-review](https://community.infosecinstitute.com/discussion/129238/elearnsecurity-web-application-penetration-testing-ewpt-review)

## Cheat sheets

Complete list can be reviewed [here](https://github.com/IgorSasovets/web-security-learning-resources/tree/main/Cheat_sheets).
Below you can find the most relevant cheat sheets

- XSS
  - [XSS Vector Cheat Sheet](https://gist.github.com/kurobeats/9a613c9ab68914312cbb415134795b45)
  - [PortSwigger XSS Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet)
  - [XSS Filter Evasion Cheat Sheet](https://owasp.org/www-community/xss-filter-evasion-cheatsheet)
  - [XSS Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
  - [XSS Cheat sheet](https://gist.github.com/dave5623/2fe3013686e7ee1bc9324512055e146a)
  - [Tiny XSS Payloads](https://github.com/terjanq/Tiny-XSS-Payloads)
- SQLi
  - [NetSparker SQLi Cheat Sheet](https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/)
  - [Port Swigger SQLi Cheat Sheet](https://portswigger.net/web-security/sql-injection/cheat-sheet)
  - [Acunetix SQLi Cheat Sheet](https://www.acunetix.com/blog/web-security-zone/sql-injection-cheat-sheet-for-developers/)
  - [SQLi prevention cheat sheet](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)
  - [Advanced SQLi Cheat sheet](https://github.com/kleiton0x00/Advanced-SQL-Injection-Cheatsheet)
- NoSQLi
  - [NoSQLi Cheat Sheet](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/NoSQL%20Injection)
  - [HackTricks NoSQLi cheat sheet](https://book.hacktricks.xyz/pentesting-web/nosql-injection)
- Nmap
  - [nmap cheat sheet by Station X](https://www.stationx.net/nmap-cheat-sheet/)
  - [Nmap GitHub cheat sheet](https://github.com/jasonniebauer/Nmap-Cheatsheet)
  - [Infosec Institute nmap cheat sheet](https://resources.infosecinstitute.com/topic/nmap-cheat-sheet/)
- SQLMap
  - [sqlmap cheat sheet by jkullick](https://gist.github.com/jkullick/03b98b1e44f03986c5d1fc69c092220d)
  - [sqlmap cheat sheet from sleuth](https://www.security-sleuth.com/sleuth-blog/2017/1/3/sqlmap-cheat-sheet)
  - [sqlmap cheat sheet from hacktricks](https://book.hacktricks.xyz/pentesting-web/sql-injection/sqlmap)
- wpscan
  - [WPScan CLI cheat sheet poster](https://github.com/wpscanteam/blog/blob/1075e542446584a722a380de931ef20deb664b4b/assets/posts/wpscan-posters/WPScan_CLI_Cheat_Sheet.pdf)
  - [WPScan with metasploit](https://www.exploit-db.com/docs/english/45556-wordpress-penetration-testing-using-wpscan-and-metasploit.pdf?rss)
- LFI & RFI
  - [File inclusion cheat sheet from hacktricks](https://book.hacktricks.xyz/pentesting-web/file-inclusion)
- File upload attacks
  - [File upload attacks cheat sheet, part 1](https://blog.yeswehack.com/yeswerhackers/exploitation/file-upload-attacks-part-1/)
  - [File upload attacks cheat sheet, part 2](https://blog.yeswehack.com/yeswerhackers/file-upload-attacks-part-2/)
  - [File upload attacks by PortSwigger](https://portswigger.net/web-security/file-upload)
  - [File upload attacks cheat sheet from hacktricks](https://book.hacktricks.xyz/pentesting-web/file-upload)
- Subdomain enumeration
  - [Subdomain enumeration cheat sheet](https://pentester.land/cheatsheets/2018/11/14/subdomains-enumeration-cheatsheet.html)
- Burp Suite
  - [BurpSuite cheat sheet from xl7dev](https://github.com/xl7dev/BurpSuite/blob/master/CheatSheet.md)
  - [Burp Suite cheat sheet from SANS](https://www.sans.org/posters/burp-suite-cheat-sheet/)

## Vulnerable applications

- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)
- [DVWA](https://dvwa.co.uk/)
- [Node Goat](https://github.com/OWASP/NodeGoat)
- [web-security-dojo](https://www.mavensecurity.com/resources/web-security-dojo)
- [bWAPP](http://www.itsecgames.com/download.htm)
- [mutillidae](https://github.com/webpwnized/mutillidae)
  
## OWASP Resources

- [WSTG](https://owasp.org/www-project-web-security-testing-guide/)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP API Security Top 10](https://owasp.org/www-project-api-security/)
- [Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
- [OWASP-Testing-Checklist](https://github.com/tanprathan/OWASP-Testing-Checklist)

## Reporting

- [TCM Security Sample Pentest report](https://github.com/hmaverickadams/TCM-Security-Sample-Pentest-Report)
- [public-pentesting-reports](https://github.com/juliocesarfort/public-pentesting-reports)
