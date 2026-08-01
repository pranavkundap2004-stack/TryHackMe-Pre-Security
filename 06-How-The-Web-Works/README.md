# 🌍 How The Web Works

> *"Before securing websites, it's essential to understand how they communicate, process requests, and deliver content to users."*

---

# 📖 Overview

The **How The Web Works** module explains the technologies that power the modern web. It introduces DNS, HTTP, web servers, browsers, and the complete journey of a web request from entering a URL to receiving a webpage.

Understanding these concepts is essential for cybersecurity because web applications are one of the most common targets of cyber attacks.

---

# 📊 Module Summary

| Property | Details |
|----------|---------|
| **Platform** | TryHackMe |
| **Learning Path** | Pre Security |
| **Module** | How The Web Works |
| **Difficulty** | 🟢 Beginner |
| **Status** | ✅ Completed |

---

# 🎯 Why This Module Matters

Most cybersecurity work involves protecting web applications and online services.

Understanding how browsers, DNS, HTTP, and web servers interact helps security professionals identify vulnerabilities, analyze traffic, and understand how attackers exploit web technologies.

---

# 📚 Topics Covered

## 🌐 DNS in Detail

- Domain Names
- DNS Resolution
- DNS Records
- Name Servers
- Translating Domain Names into IP Addresses

---

## 📡 HTTP in Detail

- HTTP Requests
- HTTP Responses
- HTTP Methods
- Status Codes
- Headers

---

## 🖥️ How Websites Work

- Web Browsers
- Web Servers
- HTML
- CSS
- JavaScript
- URLs

---

## 🔄 Putting It All Together

- Complete Request Lifecycle
- Browser Communication
- Server Response
- Rendering Web Pages

---

# 🧠 Core Concepts

## DNS Resolution Process

```
User
   │
   ▼
Browser
   │
   ▼
DNS Server
   │
   ▼
IP Address
   │
   ▼
Web Server
```

DNS converts human-readable domain names into IP addresses so browsers can locate the correct web server.

---

## HTTP Communication

```
Browser
      │
HTTP Request
      │
      ▼
Web Server
      │
HTTP Response
      │
      ▼
Browser
```

A browser sends an HTTP request to a web server, which processes the request and returns the requested webpage.

---

# 💻 Practical Knowledge

## Common HTTP Methods

| Method | Purpose |
|---------|---------|
| GET | Retrieve data |
| POST | Send data |
| PUT | Update data |
| DELETE | Remove data |

---

## Common HTTP Status Codes

| Code | Meaning |
|------|----------|
| 200 | OK |
| 301 | Moved Permanently |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

---

## Example URL

```
https://tryhackme.com/room/presecurity
```

Components:

- Protocol → HTTPS
- Domain → tryhackme.com
- Path → /room/presecurity

---

# 🛠️ Skills Gained

After completing this module, I developed the ability to:

- Explain how DNS resolves domain names.
- Understand HTTP requests and responses.
- Identify common HTTP methods and status codes.
- Describe how browsers communicate with web servers.
- Understand the complete lifecycle of a website request.

---

# 🌍 Real-World Applications

The concepts introduced in this module are widely used in:

- Web Application Security
- Penetration Testing
- SOC Operations
- Bug Bounty Hunting
- Incident Response
- Cloud Security

A strong understanding of web technologies helps security professionals identify vulnerabilities, troubleshoot web applications, and analyze network traffic.

---

# 💭 My Reflection

This module helped me understand what happens behind the scenes every time I visit a website. Learning how DNS, HTTP, browsers, and web servers interact gave me a much stronger understanding of the technologies that power the Internet.

I now better understand why these concepts are fundamental for web security and penetration testing.

---

# 📚 Key Takeaways

- DNS translates domain names into IP addresses.
- HTTP enables communication between browsers and web servers.
- Websites are built using HTML, CSS, and JavaScript.
- Every webpage request follows a structured communication process.
- Understanding web technologies is essential before studying web security.

---

# 🚀 Next Module

➡️ **Attacks & Defenses**

The final module introduces the CIA Triad, cryptography, offensive security, defensive security, and the mindset of both attackers and defenders.

---

# 📈 Progress

- ✅ Module Completed
- ✅ Repository Updated
- 🚀 Continuing to Attacks & Defenses

---

## 📖 References

- TryHackMe – Pre Security Learning Path
- Module completed through hands-on learning and practical demonstrations.

---

> 📌 This documentation reflects my personal understanding after completing the TryHackMe **How The Web Works** module.
