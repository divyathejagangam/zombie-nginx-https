# zombie-nginx-https

# 🧟 Zombie Game Hosted with HTTPS on GCP

A lightweight project to demonstrate how to deploy a static HTML5 zombie shooting game securely over HTTPS using a self-hosted NGINX server on Google Cloud Platform (GCP).

---

## 🔒 What This Project Covers

- ✅ Provisioning a GCP Compute Engine VM (e2-micro, Debian)
- ✅ Installing and configuring NGINX
- ✅ Hosting a static HTML game (`testanime.html`)
- ✅ Creating a self-signed TLS certificate using OpenSSL
- ✅ Enabling HTTPS access with NGINX
- ✅ Redirecting all HTTP traffic to HTTPS

---

## 📸 Screenshots

> Screenshots here under `screenshots/` folder:
- HTTPS game running in browser
- NGINX config (`sites-available/default`)
- OpenSSL cert/key generation
- Successful `nginx -t` validation

---

## 🛠 Technologies Used

| Tool            | Purpose                            |
|-----------------|------------------------------------|
| Google Cloud    | Cloud VM Hosting (Free Tier)       |
| NGINX           | Web server                         |
| OpenSSL         | Self-signed SSL certificate        |
| Debian GNU/Linux| VM OS                              |
| HTML5/CSS/JS    | Zombie game static assets          |

---

## 🧠 Skills Demonstrated

- TLS/SSL Certificate Management (OpenSSL)
- Web server configuration (NGINX)
- Cloud VM setup and firewall (GCP)
- Basic Linux administration
- HTTP to HTTPS redirection

---

## 🚀 How to Try This Locally (Optional)

```bash
# Clone the repo
git clone https://github.com/divyathejagangam/zombie-nginx-https.git

# View the testanime.html in browser (or host with Python or NGINX locally)
