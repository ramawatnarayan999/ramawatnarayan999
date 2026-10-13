<div align="center">
  <svg width="960" height="260" viewBox="0 0 960 260" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#07111f"/>
        <stop offset="50%" stop-color="#0b1f2d"/>
        <stop offset="100%" stop-color="#020812"/>
      </linearGradient>
      <linearGradient id="lineGlow" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#00f5d4"/>
        <stop offset="50%" stop-color="#5eead4"/>
        <stop offset="100%" stop-color="#00c2ff"/>
      </linearGradient>
    </defs>

    <style>
      .title {
        font: 700 42px 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        letter-spacing: 6px;
        fill: #a7f3d0;
        filter: drop-shadow(0 0 10px #00f5d4);
        animation: pulse 2s ease-in-out infinite;
      }

      .subtitle {
        font: 600 18px 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        letter-spacing: 3px;
        fill: #7dd3fc;
        animation: flicker 1.8s linear infinite;
      }

      .scan {
        animation: scan 4s linear infinite;
      }

      @keyframes pulse {
        0%, 100% { opacity: 0.9; transform: translateY(0px); }
        50% { opacity: 1; transform: translateY(-2px); }
      }

      @keyframes flicker {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.6; }
      }

      @keyframes scan {
        0% { transform: translateX(-10%); opacity: 0; }
        20% { opacity: 1; }
        100% { transform: translateX(120%); opacity: 0; }
      }
    </style>

    <rect x="0" y="0" width="960" height="260" rx="18" fill="url(#bg)"/>
    <rect x="30" y="32" width="900" height="196" rx="12" fill="none" stroke="url(#lineGlow)" stroke-width="1.5" opacity="0.9"/>

    <g opacity="0.35">
      <line x1="60" y1="80" x2="900" y2="80" stroke="#00f5d4" stroke-dasharray="8 10"/>
      <line x1="60" y1="180" x2="900" y2="180" stroke="#00f5d4" stroke-dasharray="8 10"/>
    </g>

    <g class="scan">
      <rect x="40" y="55" width="220" height="2" fill="#7dd3fc" opacity="0.9"/>
    </g>

    <text x="480" y="120" text-anchor="middle" class="title">CYBER SECURITY</text>
    <text x="480" y="162" text-anchor="middle" class="title" style="font-size: 26px; letter-spacing: 10px;">STUDENT</text>
    <text x="480" y="205" text-anchor="middle" class="subtitle">SECURING SYSTEMS • ANALYZING THREATS • LEARNING EVERY DAY</text>
  </svg>
</div>

<h1 align="center">👋 Hello, I’m Narayan</h1>

<p align="center">
  <img src="https://img.shields.io/badge/CyberSecurity-Student-00F5D4?style=for-the-badge&logo=shield&logoColor=white" alt="Cyber Security Student" />
  <img src="https://img.shields.io/badge/Learning-Ethical_Hacking-7DD3FC?style=for-the-badge&logo=linux&logoColor=white" alt="Ethical Hacking" />
  <img src="https://img.shields.io/badge/Focus-Network_Security-5EEAD4?style=for-the-badge&logo=security&logoColor=white" alt="Network Security" />
</p>

## 🚀 About Me
I’m a cybersecurity student passionate about protecting digital systems, understanding attacks, and learning how to defend against modern threats. I enjoy exploring topics like ethical hacking, networking, malware analysis, OWASP, and security engineering.

## 🔐 Areas of Interest
- Network Security
- Penetration Testing
- Web Application Security
- Linux & Kali Tools
- Incident Response
- Threat Analysis
- Cryptography
- Digital Forensics

## 🛠️ Skills & Tools
```bash
Kali Linux
Burp Suite
Wireshark
Nmap
Metasploit
Nessus
Python
Bash
Git & GitHub
Linux Commands
