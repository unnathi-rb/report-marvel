# Task 1: Terraform
Terraform is an Infrastructure as Code(IaC) tool, it lets us mange infrastructure using Configuration files rather then using Graphic UI on several platforms. This task was to create,manage and destroy infrastructure in AWS using Terraform.By creating terraform files using HCL and running them using CLI, i was able to create and delete infrastructure in AWS.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-08-17%20120213.jpg?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/Screenshot%202025-08-17%20233228.jpg?raw=true)

# Task 2: SSH
SSH- Secure Shell is used to connect to a server over the network.It is safe method to connect to an external server on the local device.
This task was to create a server and use ssh to find all th key files concerned with that server. Then copy all the files from there to a new server. I searched for all private keys,public keys and authorized keys in the first server and stored them in a file, then I ssh into other server and transferred the file into that.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/ssh2.jpg?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/ssh1.jpg?raw=true)

# Task 3: Hashing
Hashing is a method of converting an input(int or string of char) into another string of values obtained using a Hash function. It prevents easy hacking of confidential infomation becoz a hashed string cannot be 
reversed into orginal data. In this task I used the hashlib python library to hash the passwords, the hashed passwords are stored with usernames in a dictionary.During login, the password verification is easily done by applying the same hash function to the input in password field. I have used SHA-256 hash function.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/hashing%20task.jpg?raw=true)

# Task 4: Jenkins
Jenkins is a tool that automates the repetitive processes in software development.
In this task, I created and automated a simple Rock–Paper–Scissors game using Jenkins. The Java program reads the user’s choice from an input.txt file, generates a random computer choice, compares the two, and displays the result. Using a Jenkins pipeline, the program is automated. It is complied using javac and executed with java.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/jenkins3.png?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/jenkins1.jpeg?raw=true)

# Task 5: Docker
Docker is a tool that helps you run applications in small, isolated environments called containers. A container is like a small, isolated box that holds everything an application needs to run like
its code, libraries, settings, and dependencies.
Container image as a single package that contains everything needed to run a process.
In this task, by following the resourced guide:
- Installed docker
- Ran container
- Cloned and developed a project from Github(TODO APP)
- Built a repository. Built and pushed a container image.
  ![image](https://github.com/unnathi-rb/report-marvel/blob/main/docker%203.jpg?raw=true)
  ![image](https://github.com/unnathi-rb/report-marvel/blob/main/docker.jpg?raw=true)
  
# Task 6: NMap
In this task, I explored how Nmap (Network Mapper) works for network discovery.I scanned a host to check for open posts, running services and operating systems.
nmap scanme.nmap.org - to find open ports and services.
nmap -sV scanme.nmap.org - to detct services
nmap -A scanme.nmap.org -oN results.txt - to scan and save results to a file.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/nmap1.jpg?raw=true)

# Task 7: Wireshark
Wireshark is a Network packet analyzer tool. In this task , I was able to learn how this tool works. Firstly I captured the live network (Wi-Fi) in which I was able to see the all those live packets across protocols liake TCP,IPv4 etc. I also applied filter like Retransmissions and duplicate acknowledgement. I also viewed Statistics options like Protocol hierarcy and I/O Graphs.This task helped me understand Wi-Fi packet capture, protocol layers, and network troubleshooting.
![image](https://github.com/unnathi-rb/report-marvel/blob/main/ws1.jpg?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/ws3.jpg?raw=true)
![image](https://github.com/unnathi-rb/report-marvel/blob/main/ws4.jpg?raw=true)


  
