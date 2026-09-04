# My First DevOps Deployment 🚀

A simple web application deployed on an AWS EC2 instance using Linux, Git, and Nginx.

## 🛠️ Technologies Used

- HTML
- Git & GitHub
- Linux (Ubuntu)
- AWS EC2
- Nginx

## 🏗️ Deployment Architecture

Developer → GitHub → AWS EC2 → Nginx → Web Browser

## 🚀 Deployment Steps

### 1. Create Git Repository
Created a GitHub repository to manage the project source code.

### 2. Launch AWS EC2
Created an Ubuntu EC2 instance and configured the required security rules.

### 3. Connect to EC2
Connected to the EC2 instance using SSH.

### 4. Install Git

sudo apt update
sudo apt install git -y

### 5. Clone Repository

git clone https://github.com/kamthednyaneshwari80/devops-linux-git-ec2-deployment.git
cd devops-linux-git-ec2-deployment

### 6. Install Nginx

sudo apt install nginx -y

### 7. Deploy Website

sudo cp index.html /var/www/html/
sudo systemctl restart nginx

### 8. Access Application

Open the EC2 public IP address in http://EC2-PUBLIC-IP

your-public-ip

## ✅ Project Status

Application successfully deployed and accessible through AWS EC2.

## 📚 What I Learned

- Linux basic commands
- Git and GitHub
- AWS EC2
- SSH connection
- Nginx web server
- Web application deployment
- Basic cloud deployment workflow

## 👩‍💻 Author

Dnyaneshwari Kamthe