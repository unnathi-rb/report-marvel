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

# TASK 2: Database task: DynamoDB
In this task I created a user login system that validates the username and passwords of users.
DynamoDB is a NoSQL database service provided by AWS DynamoDB is a durable, secure data base. I have used Nodejs as backend and then connected it to AWS by Access key ID and secret access key.After this i created a table in DynamoDB for storing the user credentails. Later I used the bcrypt, a password hashing sysytem for security, through this function only the hashed password is stored in database and not the orginal password and is uses slow hashing intentionally to make it harder to crack.Finally I integrated frontned using HTML.
SQL is a language used to manange database in relational databases, its like a language used to communicate with the database to fetch or store data.
MySQL is a relational database with stucture data storing tables and it uses SQL language.
NoSQL is a Non-relational database where the data is not structured but they are document types, key-value pairs, graphs or columns.This database is offers flexibility ,the structure can be changed.
LINK: https://github.com/unnathi-rb/Dynamo
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-04%20141640.png?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-07%20072021.png?raw=true)



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

# Task 5: OSI Model
The Open Systems Interconnection(OSI) model is a conceptual model that represents how network communication work.It divides the network communication functions into 7 layers-
- Physical Layer: Layer that is responsible for actual physical connections between devices.Contains information in the form of bits. Physical layers includes devices like cables,hub and modem.
- Data-Link layer: Provides node-to-node data transfer.(Ethernet,Wifi)
- Network Layer: Network Layer is responsible for data routing, forwarding, and addressing.(IP)
- Transport Layer: it provides communication services for applications. It ensures complete data transfer, error recovery, and flow control between hosts.(TCP,UDP)
- Session Layer: Session Layer manages and controls the connections between computers. It establishes, maintains, and terminates connections.(Sockets)
- Presentation Layer: The key roles of the Presentation Layer is data translation and code conversion.It also does Data formatting ,encryption and compression.(TLC,SSL)
- Application Layer: This layer acts as an interface between the user applications and network services.(http,ftp)
  ![image](https://github.com/unnathi-rb/report-marvel/blob/main/1st%20osi.jpg?raw=true)

# TASK 6: IAAS,PAAS AND SAAS
#### IAAS: Infrastructure as a service: 
- It provides only the infrastructure required. the coustomers have to manage the opearting system , middle ware, applications and data.
- It provides computing resources like Virtual machines and storage.
- eg: Amazon EC2
#### PAAS: Platform as a service:
- It provides a platform for developers to build ,deploy and manage applications.
- Manages the opearting systems and Infrastructure for the users.
- PAAS is accessed directly through GUI by the users.
- Useful for developers to optimise time n resource usage.
- eg: Google App engine
#### SAAS: Software as a Service:
- It offers a fully working software application over the internet.
- It manages all the infrastructure and software.
- The software is ready to use by the users.
- eg: Email service


# TASK 7: Messaging app using Encryption Technique
In this task I created a simple chat application using Nodejs, Socket.io and cryptography. The chat application uses symmetric encryption that is same key for encryption and decryption.
Tools: Node js, Express js, Socket io, HTML.

##### Cipher: It is a mathematical process that converts plain readable text into cipher text(unreadable) using a secret key.
- Ceasar Cipher: It is an encryption technique where the letters in plain text are shifted by a certain number of positions.
- Vigenère Cipher: It is an encryption method where a keyword is used to shift letters of a plain text.
- Substitution Cipher: A technique where each letter in plain text is replaced by a fixed letter mapping. 

link: https://github.com/unnathi-rb/chatapp


![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-01%20233236.png?raw=true)


# TASK 8: IP Addressing and Web Scraping
Web srcaping: It is a process of Extracting data from websites.
In this task I have extracting Job details from RemoteOK Static HTML page using python library BeautifulSoup.In this a HTTP request is sent to the url of that Webpage and then the scraped data is stored in a created exel sheet.
Link: https://github.com/unnathi-rb/WEBSCRAPE

![image](https://github.com/unnathi-rb/report-marvel/blob/main/WhatsApp%20Image%202025-05-07%20at%207.49.48%20PM%20(1).jpeg?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-05%20154016.png?raw=true)

# TASK 9: Socket.IO
Socket.io is a Java script library that allows bidirectional communication in real-time, it is a connection between client and server. In this task I built simple chat application using node.js and socket.io where server and browser were able to connect.
link: https://github.com/unnathi-rb/chatapp

![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-05-01%20233236.png?raw=true)

# TASK 10: Kali Linux
Kali Linux is a Linux distribution which is used for security testing, ethical hacking and penetration testing.In this task I performed a simple penetration test using NMap. Found open ports, penetrated and opened a session in it. Learnt the use of Kali linux and Virtual machine penetration. 
![image](https://github.com/unnathi-rb/report-marvel/blob/main/WhatsApp%20Image%202025-06-03%20at%206.03.51%20PM%20(1).jpeg?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/WhatsApp%20Image%202025-06-03%20at%206.03.51%20PM.jpeg?raw=true)







