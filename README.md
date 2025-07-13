# Cloud Landing Page – AltSchool Second Semester Project

## 🌐 Project Overview
This is a dynamic prototype of a cloud-hosted landing page showcasing my technical skills as a cloud engineer. It was deployed on an Ubuntu Linux server using AWS EC2 and includes a secure HTTPS connection using Let's Encrypt SSL.

---

## 🔧 What I Did

1. **Provisioned a Linux Server**
   - Cloud Provider: AWS EC2
   - OS: Ubuntu 22.04 LTS
   - Instance Type: t2.micro (Free Tier)

2. **Web Server Setup**
   - Installed and configured **Nginx** as the web server
   - Allowed public access via ports 80 (HTTP) and 443 (HTTPS)

3. **Created a Dynamic Landing Page**
   - Includes my name, role, project title, a short pitch, and my bio
   - Designed with simple HTML and inline CSS (optionally upgrade with Tailwind)

4. **Networking & Security**
   - Opened ports 80 and 443 in AWS Security Group
   - Secured the site with **Let’s Encrypt SSL** using **Certbot**
   - Configured automatic HTTP to HTTPS redirection

---

## 👩‍💻 About Me

**Name**: Anthony Onyeka  
**Role**: Lead Cloud Engineer  
**Project Title**: The Future of Smart Cloud Logistics  
**Pitch**: This project helps businesses optimize delivery through smart cloud-based logistics. It reduces cost and delivery time using real-time monitoring and scalable cloud technology.  
**Bio**: I am a cloud engineering student skilled in AWS, Ubuntu Linux, web servers, and DevOps tools. I enjoy building practical and secure cloud applications.

---

## 📍 Live Demo

- **Public IP Address**: [http://98.84.98.231]
---

## 🖼️ Screenshot

<img width="1366" height="768" alt="my-project" src="https://github.com/user-attachments/assets/414f33ca-b054-453f-8de5-fa0c07b7efa8" />


---

## 📁 How to Reproduce

1. Launch Ubuntu EC2 server on AWS
2. SSH into the instance
3. Install Nginx:
   ```bash
   sudo apt update
   sudo apt install nginx -y

4. Edit landing page:

sudo nano /var/www/html/index.html



---

📬 Contact

Name:  Anthony Onyeka 

Email: wilz.soft@hotmail.com
