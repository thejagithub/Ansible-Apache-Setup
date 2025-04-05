# 🚀 Ansible Apache Setup on AWS EC2

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
   ```bash
   git clone https://github.com/yourusername/ansible-apache-setup.git
   cd ansible-apache-setup

2️⃣ Define your EC2 instance details in inventory.ini

3️⃣ Run the Ansible playbook:
ansible-playbook -i inventory.ini apache_setup.yml

4️⃣ Verify Apache is running:
systemctl status apache2

5️⃣ Access your deployed webpage via:
http://your-ec2-public-ip/



🎯 Future Improvements

🔹 Convert the playbook into an Ansible Role

🔹 Implement SSL (HTTPS) with Let's Encrypt

🔹 Automate EC2 provisioning with Terraform + Ansible

🔹 Set up CI/CD with GitHub Actions or Jenkins


