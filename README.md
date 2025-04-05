# 🚀 Ansible Apache Setup on AWS EC2

![Ansible](https://img.shields.io/badge/Ansible-%230A57A1?style=flat-square&logo=ansible&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-%23D22128?style=flat-square&logo=apache&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-%23E95420?style=flat-square&logo=ubuntu&logoColor=white)
![SSH](https://img.shields.io/badge/SSH-%232C6B7D?style=flat-square&logo=openssh&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

This project contains an **Ansible playbook** to automate the installation and configuration of the **Apache web server** on an **AWS EC2 instance** running Ubuntu. 
The playbook installs Apache (`apache2`), ensures the service is running, and deploys a custom `index.html` page.

## 📌 Features
- ✅ **Automated Apache Installation** (`apache2`)
 
- ✅ **Deploys a custom web page** (`index.html`)
 
- ✅ **Runs on AWS EC2 (Ubuntu/Debian-based servers)**
  
- ✅ **Ensures Apache is running & enabled at startup**
 
- ✅ **Passwordless SSH Authentication** used to connect to EC2 for secure and easy management
 

## 🛠️ Technologies Used

- **Ansible** – Configuration management
 
- **Apache (httpd)** – Web server
 
- **AWS EC2 Instance** – Cloud deployment
 
- **Passwordless SSH Authentication** – Secure and easy EC2 access



## 🚀 How It Works

1️⃣ Clone this repository onto your control node  
 
   git clone https://github.com/yourusername/ansible-apache-setup.git
   cd ansible-apache-setup

2️⃣ Define your EC2 instance details in inventory.ini

3️⃣ Run the Ansible playbook:
ansible-playbook -i inventory.ini apache_setup.yml

4️⃣ Verify Apache is running:
systemctl status apache2

5️⃣ Access your deployed webpage via:
http://your-ec2-public-ip/



## 🎯 Future Improvements

🔹 Convert the playbook into an Ansible Role

🔹 Implement SSL (HTTPS) with Let's Encrypt

🔹 Automate EC2 provisioning with Terraform + Ansible

🔹 Set up CI/CD with GitHub Actions or Jenkins



![Screenshot 2025-04-04 191848](https://github.com/user-attachments/assets/02d543d7-785c-40c7-b030-03a7f7c16bb1)
![Screenshot 2025-04-04 192744](https://github.com/user-attachments/assets/29848681-7182-4825-882c-1e11f722acae)



