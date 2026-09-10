# 🚀 EC2 Linux Nginx Web Server Deployment

## 🌐 What is Nginx?

**Nginx (pronounced “Engine-X”)** is an open-source, high-performance web server used to deliver websites and web applications.

It can also work as a **Reverse Proxy, Load Balancer, and HTTP Server**.

---

## ❓ Why is Nginx Used?

Nginx is commonly used because it can:

* 🌐 Serve websites and static files
* ⚡ Handle a large number of requests efficiently
* 🔄 Work as a Reverse Proxy
* ⚖️ Distribute traffic using Load Balancing
* 🚀 Improve web application performance
* 🔒 Support secure HTTPS connections

---

## ⭐ Benefits of Nginx

* ⚡ **High Performance** – Handles many concurrent connections efficiently.
* 🚀 **Lightweight** – Uses relatively low system resources.
* 📈 **Scalable** – Suitable for high-traffic applications.
* 🔄 **Reverse Proxy** – Connects clients with backend servers.
* ⚖️ **Load Balancing** – Distributes traffic across multiple servers.
* 🔒 **Security** – Supports SSL/TLS.
* 🌍 **Static Content Delivery** – Efficiently serves HTML, CSS, JavaScript and images.
* 🛠️ **DevOps Friendly** – Commonly used with AWS, Docker, Kubernetes and CI/CD.

---

# 🛠️ Nginx Installation & Configuration

```bash
sudo su

yum update -y

yum install nginx -y

cd /usr/share/nginx/html

touch index.html

vi index.html

systemctl start nginx

systemctl enable nginx
```

---

## 👨‍💻 Author

**Mohit Gadilohar**

**Cloud & DevOps Engineer**

AWS | Linux | Nginx | Git | Docker | CI/CD
