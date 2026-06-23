# Hi, I'm Gaurav Sharma 👋

### BCA Graduate | Web Developer & Cybersecurity Analyst 🛡️💻

I am a technical professional specializing in bridging the gap between web application development and proactive digital security. I focus on building robust, responsive web projects and rigorously testing them against modern threat frameworks.

---

### 🛠️ My Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Development** | HTML5, CSS3, JavaScript, Bootstrap, Git, Web Architecture |
| **Cybersecurity** | Linux CLI, Network Security, Wireshark, SIEM Basics, Python Scripting |

---

### 📈 What I'm Focused On
- 🌐 Building modern, fully accessible web applications.
- 🔒 Implementing defensive coding standards (OWASP Top 10 mitigation).
- 🐍 Automating security workflows using Python and Bash scripts.

---

### 🤝 Connect With Me
[@LinkedIn](YOUR_LINKEDIN_URL) | ✉️ [Email Me](mailto:gs443004@gmail.com)## Hi there 👋

# Project Name: Secure vs. Vulnerable Web Application

### 🎯 Objective
To design and deploy a dual-environment web application that explicitly demonstrates common OWASP Top 10 vulnerabilities (such as SQL Injection and XSS) alongside a secondary, securely remediated environment demonstrating defensive coding best practices.

### 🧰 Tools & Technologies Used
- **Frontend/Backend:** HTML5, CSS3, JavaScript
- **Testing Environment:** Linux CLI, Localhost Sandbox
- **Security Concepts:** Input Sanitization, Parameterized Queries, Context-aware Output Encoding

### ⚙️ How It Works & Steps
1. **The Vulnerable State:** The application accepts direct user input into database queries and renders raw input to the screen, allowing malicious scripts to execute.
```javascript
   // Vulnerable Code Snippet Example:
   let query = "SELECT * FROM users WHERE username = '" + userInput + "'";
