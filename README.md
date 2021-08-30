
# Online Test Assessment

Online Quiz is a web application for candidate to appear for an
 online test in an effective way and there is no loss of time to 
 check the paper. The chief aim of Online Quiz is to effectively 
 estimate the candidate completely via a totally automated system 
 which besides preserving time, offers swifter outcomes.


## Authors
- [@Gravish Purohit](https://www.github.com/gravishpurohit)
- [@Harshit Raj](https://www.github.com/harshitraj12)
- [@Praveen Takpuriya](https://www.github.com/praveenyadavtak)

  
## Tech Stack

**Client:** HTML, CSS, JAVASCRIPT

**Server:** JAVASCRIPT, AWS 

  
## CI/CD SETUP

Setup Instance(Amazon linux) in EC2 at AWS. 

Install httpd server.

Start httpd server.



```bash
  yum install httpd
  systemctl start httpd
```

  
## Project Setup

Clone webapp from https://github.com/harshitraj12/MCQ_Project.git

Hosted on httpd server at Amazon Linux AMI



Command setup 
```bash
sudo su - root
cd /var/www/html
git clone https://github.com/harshitraj12/MCQ_Project.git

```
Check if server is active

```bash
systemctl status httpd

```
If not then start server

```bash
systemctl start httpd

```
## Features

- Assessment is MCQ pattern
- There is a question pool for the assessment
- The questions displayed in the assessment are only from that pool
- Number of questions in the pool are more than questions displayed
- There is a time limit for the assessment (individual timerfor a question/optional)
- Question order is shuffled for each candidate appearing
- Assessment score will be generated at the time of submission

## Additional Features

- Result status of candidate will be send through email.
- Result will be displayed with Name taken initially.
  