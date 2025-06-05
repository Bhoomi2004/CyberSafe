# 🌐 CyberSafe - Website Security Scanner

## 📌 Overview

**CyberSafe** is a website security scanner designed to analyze website URLs for vulnerabilities, trustworthiness, SSL certificate status, and backlink profiles. It helps users assess the reliability of websites by displaying key security metrics in an interactive and visual format.

---

## 🚀 Features

* 🔍 **Trust Score Analysis**: Evaluate a website's credibility based on multiple security indicators
* 🛡 **Vulnerability Detection**: Detect potential threats using the **OWASP ZAP API**
* 🔗 **Backlink Analysis**: Check inbound links to verify the site's authenticity
* 🔒 **SSL Certificate Validation**: Confirm the presence of a valid SSL certificate
* 📊 **Graphical Representation**: Interactive charts display overall security scores

---

## 🛠 Tech Stack

* **Frontend**: HTML, CSS, JavaScript, Bootstrap
* **Backend**: Python
* **APIs Used**:

  * 🔸 [VirusTotal API](https://www.virustotal.com/gui/home/upload)
  * 🔸 [OWASP ZAP API](https://www.zaproxy.org/docs/api/)

---

## 🔧 Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/website-scanner.git
   cd website-scanner
   ```

2. **Install Dependencies**

   ```bash
   pip install -r backend/requirements.txt
   ```

3. **Set Up OWASP ZAP**

   * Install OWASP ZAP on your system
   * Add your OWASP ZAP API key in `backend/back.py`

4. **Run the Backend**

   ```bash
   python backend/back.py
   ```

5. **Launch the Frontend**

   * Open `frontend/front.html` in your browser

---

## 🔗 Live Demo

▶️ **Watch the Demo Video**
[Click here to view the demo](https://drive.google.com/file/d/1AT-a48vNWlijMheJn-SUlUbIv3nxmxrx/view?usp=sharing)

---

## ✅ How It Works

1. Enter the website URL in the input field
2. Click the **Scan** button
3. View trust score, vulnerability level, and SSL status
4. Explore the results through visual dashboards and interactive charts
