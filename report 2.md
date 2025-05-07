# TASK 1: Version Control
In this task i understood the working of git as a version control. Using git commands we intialize a directory as a git repository after which any commit we make can we stored in git for future refrences.The same can we done for a GitHub repository.Git commands:
- git init: intializing repository
- git add: staging changes
- git commit -m " ": to commit the changes
- git branch: to create new branch of the repo.
- git merge: merging a branch with main
- git revert HEAD: to revert(delete) the previous commit.
- git cherry-pick: to choose and apply a specific commit to another branch.
- git log: to view the history of commits made.


![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-03-26%20070654.png?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-03-26%20073536.png?raw=true)

# TASK 4: Database task: DynamoDB
In this task I created a user login system that validates the username and passwords of users.
DynamoDB is a NoSQL database service provided by AWS DynamoDB is a durable, secure data base. I have used Nodejs as backend and then connected it to AWS by Access key ID and secret access key.After this i created a table in DynamoDB for storing the user credentails. Later I used the bcrypt, a password hashing sysytem for security, through this function only the hashed password is stored in database and not the orginal password and is uses slow hashing intentionally to make it harder to crack.Finally I integrated frontned using HTML.
SQL is a language used to manange database in relational databases, its like a language used to communicate with the database to fetch or store data.
MySQL is a relational database with stucture data storing tables and it uses SQL language.
NoSQL is a Non-relational database where the data is not structured but they are document types, key-value pairs, graphs or columns.This database is offers flexibility ,the structure can be changed.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-07%20072021.png?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-03-26%20070654.png?raw=true)


# TASK 3: EC2 Instance
In this task I created 2 AWS EC2(elastic compute cloud) instances in different avaliability zones to solve a problem.EC2 Instances are server resources provided by the Amazon cloud services.There are virtual computers to manage applications and workloads.I launced the t3.micro instance type, there several instance types avaliable for different purpose and size requirements.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-03-28%20214517.png?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-03-29%20000741.png?raw=true)

# TASK 4: Amazon CloudFront
In this task i created a CloudFront distribution for an Amazon S3 bucket to serve the jpg objects in it.
Amazon S3 is a AWS service that helps us store any data at any time and retrieve data from web. S3 Buckets are like containers for the files we want to store, the files are reffered to as Objects.This can be used to host websites or just for data or media backup.
CloudFront is a content delivery system by AWS. When a CloudFront distribution is made for an S3 bucket or any other origin, the Cloudfront copies and caches the content. Thus, when a CloudFront url is opened it deliverers the cached content very fast.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-01%20124737.png?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-01%20124829.png?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-01%20124857.png?raw=true)




