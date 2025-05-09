# 🎣 Phishing Awareness Demo – Fake Amazon Login (For Educational Use)

This project simulates a realistic phishing attack to help teach others how easily users can be tricked by fake login pages. It features a mock Amazon login site that looks convincing, collects fake credentials, and then reveals the simulation with a warning message.

> ⚠️ **This project is for educational and ethical hacking demonstrations only.** Do not deploy or share outside a controlled classroom or workshop setting.

---

## 📂 Project Contents

- `index.html` – Fake Amazon login page that displays a warning after login.
- `email.html` – A sample phishing email styled like a security alert from Amazon, containing a link to `index.html`.

---

## 🔧 How to Use (Local Demo Setup)

### 1. Clone or Download This Repo
```bash
git clone https://github.com/yourusername/phishing-awareness-demo.git
cd phishing-awareness-demo
```

### 2. Start a Local Server
```bash
python -m http.server 8000 --bind 0.0.0.0
```

### 3. Find Your Local IP
```bash
# On Windows
ipconfig

# On Mac/Linux
ifconfig
```
Look for an IP address like `10.0.0.243` or `192.168.x.x`.

### 4. Share the Link on the Same Wi-Fi Network
```bash
http://<your-local-ip>:8000/email.html
```
Open this link in a browser to simulate the phishing email. Clicking "Verify Account" will take users to the fake login page (`index.html`) and reveal the simulation after form submission.
