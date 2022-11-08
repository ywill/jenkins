## Requirment skill
linux
git
CI/CD

### What is Jenkins?
Jenkins is an open source CI/CD and deployment automation software DevOps tool writeen in the **Java** programming language

### Install Jenkins Ubuntu 22
```
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key |sudo gpg --dearmor -o /usr/share/keyrings/jenkins.gpg
sudo sh -c 'echo deb [signed-by=/usr/share/keyrings/jenkins.gpg] http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
sudo apt update
sudo apt install openjdk-11-jdk -y
sudo apt install jenkins -y
```

### 