🚀 **Mastering Virtual Hosting with Nginx on Linux!**

🔧 Real-time Setup for Hosting Multiple Environments 🧑‍💻

---

🚀 **Why Virtual Hosting is a Game-Changer for DevOps & Web Engineers**

In today's cloud-native and microservices-driven world, deploying multiple environments or domains on a single server has become a necessity — and **Virtual Hosting** is the solution! 🌐

---

### 💡 **What is Virtual Hosting?**

Virtual Hosting allows a single server to host **multiple websites/domains** by mapping each domain to a separate directory with isolated configurations.

---

### ✅ **Key Benefits of Virtual Hosting:**

* 🧩 **Host multiple domains** on one server (e.g., dev.awsguruji.net & prod.awsguruji.net)
* 💰 **Reduces infrastructure cost** by maximizing server utilization
* 🔐 **Isolated configurations** for dev, prod, and staging environments
* 🛠️ **Simplified maintenance** and deployment workflows

---

### ⚙️ **Why Choose Nginx for Virtual Hosting?**

* ⚡ **High-performance & low resource usage**
* 🔄 **Handles concurrent connections efficiently**
* 🔐 **Supports SSL/TLS & reverse proxy features**
* 📁 **Simple, modular config management (sites-available/sites-enabled)**
* ♻️ **Built-in load balancing & caching capabilities**

---

🔹 **Step-by-Step Guide to Host Two Domains:**
`dev.awsguruji.net` & `prod.awsguruji.net` using **Nginx Virtual Hosts**

---

### 📦 1. Install Nginx

```bash
sudo apt update
sudo apt install nginx -y
```

---

### 📁 2. Create Directory Structures

```bash
sudo mkdir -p /var/www/dev.awsguruji.net/html
sudo mkdir -p /var/www/prod.awsguruji.net/html
```

---

### 📝 3. Add Sample `index.html` Pages

```bash
echo "<h1>Welcome to DEV Environment</h1>" | sudo tee /var/www/dev.awsguruji.net/html/index.html
echo "<h1>Welcome to PROD Environment</h1>" | sudo tee /var/www/prod.awsguruji.net/html/index.html
```

---

### 🛠️ 4. Create Virtual Host Config Files

**➡️ Dev: `/etc/nginx/sites-available/dev.awsguruji.net`**

```nginx
server {
    listen 80;
    server_name dev.awsguruji.net;

    root /var/www/dev.awsguruji.net/html;
    index index.html;

    location / {
        try_files $uri $uri/ =404;
    }
}
```

**➡️ Prod: `/etc/nginx/sites-available/prod.awsguruji.net`**

```nginx
server {
    listen 80;
    server_name prod.awsguruji.net;

    root /var/www/prod.awsguruji.net/html;
    index index.html;

    location / {
        try_files $uri $uri/ =404;
    }
}
```

---

### 🔗 5. Enable Virtual Hosts

```bash
sudo ln -s /etc/nginx/sites-available/dev.awsguruji.net /etc/nginx/sites-enabled/
sudo ln -s /etc/nginx/sites-available/prod.awsguruji.net /etc/nginx/sites-enabled/
```

---

### ✅ 6. Test & Reload Nginx

```bash
sudo nginx -t
sudo systemctl reload nginx
```

---

### 🔍 7. Verify Nginx Status

```bash
sudo systemctl status nginx
```

---

### 🔐 **Enable Free SSL with Let's Encrypt**

**Install Certbot:**

```bash
sudo apt install certbot python3-certbot-nginx -y
```

**Obtain SSL:**

```bash
sudo certbot --nginx -d dev.awsguruji.net -d prod.awsguruji.net
```

**Dry-run renewal check:**

```bash
sudo certbot renew --dry-run
```

---

### 🌐 **Verify Access:**

🔗 [https://dev.awsguruji.net](https://dev.awsguruji.net)

🔗 [https://prod.awsguruji.net](https://prod.awsguruji.net)

---

### 📚 **Directory Structure Insight**

* `/etc/nginx/sites-available/`: Stores all virtual host configs (inactive by default).
* `/etc/nginx/sites-enabled/`: Contains symbolic links to active configs that Nginx loads.

---

💬 **Why Virtual Hosting?**

👉 Host multiple environments/domains on a single server

👉 Simplified config management

👉 Cost-effective and scalable 💡


---

