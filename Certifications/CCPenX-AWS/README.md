# Certified Cloud Pentesting eXpert-AWS (CCPenX-AWS)

Here you can find tips and resources that will help you to pass the [Certified Cloud Pentesting eXpert-AWS (CCPenX-AWS)](https://pentestingexams.com/product/certified-cloud-pentesting-expert/) certification from SecOpsGroup.

## Content

- [My experience](#my-experience)
- [Tips and tricks](#tips-and-tricks)
- [Training resources](#training-resources)
- [Exam reviews](#exam-reviews)
- [Cheat sheets](#cheat-sheets)
- [Useful tools](#useful-tools)
- [Pentesting OS](#pentesting-os)

## My experience

In general, I started learning AWS pentesting more than 2 years ago from something simple like [flaws.cloud](http://flaws.cloud/) and constantly work on improving my knowledge. I decided to take the CCPenX-AWS exam after finishing AWS Cloud Pentesting bootcamp from Pwned Labs and studiying CARTS course from Cyber Warfare Labs. Also, I have previous experience in web/API pentesting that also helped me a lot during the CCPenX-AWS exam itself. Exam syllabus covers a lot of topics like Enumeration, Identity and Access Management, Vulnerability Identification, Exploiting AWS, Best Security Practices and hardening techniques. More detailed list of topics can be reviewed on the [exam details page](https://pentestingexams.com/product/certified-cloud-pentesting-expert/). I can say that in order to pass the exam you should cover (at least at basic level) all of them. Exam itself lasts 7 hours and can be started whenever you're ready to test your skills. After you've have purchased the exam voucher, you just need to ensure that VPN connection works and start the exam itself. VPN instructions will be sent in a dedicated email after you purchase the exam.
Before starting the exam I also prepared a dedicated Kali Linux VM with all the necessary tools installed (like enumerate-iam, cloudfox, awscli, Pacu, etc.), so it was easier to proceed with the recon and exploitation activities later. 
Exam has 12 questions that are dedicated to different topics, covered in the syllabus. They were implemented in CTF-like style where you should gather flags by exploiting different vulnerabilities. In order to pass you should complete most of them. I can claim that knowledge from Pwned Labs bootcamp, CARTS course and HackTricks Cloud was enough to complete the necessary amount of tasks, required to pass the exam. In general, exam environment was stable and the process itself went pretty smoothly. I used nearly 5 hours to complete the required amount of challenges and it was fun, interesting experience for me. I would definitely recommend this exam for anyone looking to test their AWS Pentesting skills. 

## Tips and tricks

- Develop practical skills. You can do it by using platforms like Cybr, Pwned Labs, TryHackMe. HackTricks Training
- Make notes during the course to quickly refresh your knowledge when needed. Especially, document aws cli commands that are required when working with different AWS services
- Do an additional research if you want to better understand a specific topic. Use [HackTricks Cloud](https://cloud.hacktricks.wiki/en/index.html), blog articles on security topics
- Refresh or develop web pentesting skills (PortSwigger labs are probably the best place for this)
- Review AWS documentation for specific challenges in order to better understand how they work
- You can also use AI to summarise articles, structure knowledge when studying to save some time and make the learning process more efficient

## Training resources

Below are resources that I've used during my preparation to this exam:

- [Pwned Labs ACRTP bootcamp](https://bootcamps.pwnedlabs.io/acrtp-bootcamp)
- [PwnedLabs AWS Labs](https://pwnedlabs.io/)
- [PwnedLabs Electra](https://cyber-ranges.pwnedlabs.io/electra-overview)
- [AWS Red Team Learning Path from Cybr](https://cybr.com/learning-path/aws-red-team-learning-path/)
- [flaws.cloud](http://flaws.cloud/)
- [flaws2.cloud](http://flaws2.cloud/)
- [SQL Injection](https://portswigger.net/web-security/sql-injection)
- [XXE](https://portswigger.net/web-security/xxe)
- [SSRF](https://portswigger.net/web-security/ssrf)
- [Path Traversal](https://portswigger.net/web-security/file-path-traversal)
- [API testing](https://portswigger.net/web-security/api-testing)
- [Hacking the CLoud: AWS](https://hackingthe.cloud/aws/general-knowledge/aws_cli_tips_and_tricks/)
- [HackTricks Cloud](https://cloud.hacktricks.wiki/en/index.html)
- [Learn AWS Pentesting by Tyler Ramsbey](https://www.youtube.com/watch?v=Bdwurohdhq4&list=PLMoaZm9nyKaNRN0SoR_PBVYc_RAhbZdG4)
- [Wiz Big IAM challenge](https://bigiamchallenge.com/challenge/1)
- [HTB Business CTF 2024](https://github.com/hackthebox/business-ctf-2024/tree/main/cloud)

## Exam reviews

- [Review — Certified Cloud Pentesting eXpert-AWS (CCPenX-AWS)](https://medium.com/@kariarce2377/review-certified-cloud-pentesting-expert-aws-ccpenx-aws-407b209b3cc9)

## Cheat Sheets

- [AWS CLI cheat sheet](https://www.bluematador.com/learn/aws-cli-cheatsheet)

## Useful tools

- [enumerate-iam](https://github.com/andresriancho/enumerate-iam)
- [cloudfox](https://github.com/BishopFox/cloudfox)
- [bf-aws-permissions](https://github.com/carlospolop/bf-aws-permissions)
- [s3-bucket-finder](https://github.com/gwen001/s3-buckets-finder)
- [More](https://github.com/mxm0z/awesome-sec-s3?tab=readme-ov-file)

## Pentesting OS

- [RedCloud OS](https://github.com/RedTeamOperations/RedCloud-OS)
- [PwnCloud OS](https://pwncloudos.pwnedlabs.io/)
