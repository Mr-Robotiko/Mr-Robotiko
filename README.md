
<div align="center">

# 👋 Hi, I'm Raffi (Mr-Robotiko)

### Hacker by heart - "breaking systems to make them safer"

<!-- Add your contact badges here (they appear centered under the title), e.g.:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Raffi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-HANDLE)
[![Email](https://img.shields.io/badge/Email-you%40example.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:you@example.com)
[![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-Profile-111927?style=flat-square&logo=hackthebox&logoColor=9FEF00)](https://app.hackthebox.com/profile/YOUR-ID)
-->
![Profile views](https://komarev.com/ghpvc/?username=Mr-Robotiko&style=flat-square&color=00C853)

</div>

---

## 🎯 What I Do

I work in **offensive security**. I find vulnerabilities before attackers do, and I like building my own tooling along the way.

- 🔓 **Penetration Testing**: web applications, networks and Active Directory, from recon to reporting
- 🤖 **AI in Security**: researching the AI arms race across offensive, defensive and regulatory perspectives.
- 🛠️ **Security Tooling**: building toolkits and references that make security work faster and more accessible

> [!NOTE]
> **Currently working on:** an isolated Red vs. Blue lab where LLM agents attack and defend, measuring detection rate, false positives and time-to-detect.

```mermaid
flowchart LR
    LLM["🧠 Local LLM<br/>(Ollama)"]
    subgraph LAB ["🧪 Isolated Docker Lab"]
        direction LR
        RED["🔴 Red Team Agents<br/>Recon · Exploit"] -->|attacks| TARGET["🎯 Target Systems"]
        TARGET -->|logs & telemetry| BLUE["🔵 Blue Team Agents<br/>Detection · Triage"]
    end
    LLM <-.-> RED
    LLM <-.-> BLUE
```

---

## 📌 Selected Repositories

| Repository | Description |
| ---------- | ----------- |
| [**Gilfi**](https://github.com/Mr-Robotiko/Gilfi) | Security & network analysis toolkit (PyQt6 + Flask) with port scanner, hash cracking, password analysis and a local AI assistant via Ollama |
| [**Pentest-Cheatsheet**](https://github.com/Mr-Robotiko/Pentest-Cheatsheet) | Command-ready pentest reference with live variables: set target IP & creds once, and every command fills itself in · [Live site](https://mr-robotiko.github.io/pentest-cheatsheet/) |

<details>
<summary><b>📂 More projects</b></summary>
<br />

| Repository | Description | Stack |
| ---------- | ----------- | ----- |
| [**cryptography**](https://github.com/Mr-Robotiko/cryptography) · [**krypto-code-abgabgen**](https://github.com/Mr-Robotiko/krypto-code-abgabgen) | Cryptographic algorithms & exercises | Python |
| [**studyflow**](https://github.com/Mr-Robotiko/studyflow) | Web engineering project | PHP |
| [**Studentenverwaltung_C_DHBW**](https://github.com/Mr-Robotiko/Studentenverwaltung_C_DHBW) | Student management system | C |
| [**Loginsystem-mit-integriertem-Spiel**](https://github.com/Mr-Robotiko/Loginsystem-mit-integriertem-Spiel) | Login system on MS SQL Server that unlocks a game | C# |
| [**BreakOut**](https://github.com/Mr-Robotiko/BreakOut) · [**GameLauncher-Projekt**](https://github.com/Mr-Robotiko/GameLauncher-Projekt) | Classic game & launcher | C# |
| [**Weather-App-Angular**](https://github.com/Mr-Robotiko/Weather-App-Angular) | Weather app on the OpenWeatherMap API | Angular / TS |
| [**ToDo-App-React**](https://github.com/Mr-Robotiko/ToDo-App-React) | To-do app | React / TS |

</details>

## 🧰 Tech Stack

**Offensive Security**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Hashcat](https://img.shields.io/badge/Hashcat_/_John-333333?style=flat-square)

**Languages**

![Python](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/c-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C#](https://img.shields.io/badge/c%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/php-777BB4?style=flat-square&logo=php&logoColor=white)

**Frameworks & Web**

![Flask](https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white)
![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white)
![Angular](https://img.shields.io/badge/angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/react-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![MkDocs](https://img.shields.io/badge/MkDocs_Material-526CFE?style=flat-square&logo=materialformkdocs&logoColor=white)

**Platforms, AI & Databases**

![Docker](https://img.shields.io/badge/docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square)
![SQLite](https://img.shields.io/badge/sqlite-003B57?style=flat-square&logo=sqlite&logoColor=white)

---

## 🤝 Let's Connect

Always happy to exchange ideas:

- 🔐 **Security folks?** Let's talk about pentesting methodology, AD attacks, CTFs or tooling.
- 🤖 **Into AI?** I'm interested in LLM agents for offensive and defensive security, local models and detection engineering.
- 💻 **Developer?** Happy to discuss secure-by-design architecture or how your app would hold up in a pentest.

Feel free to open an issue on any of my repositories.

> [!WARNING]
> All offensive tooling and content in my repositories is intended for **authorized testing and education only**. Never use it against systems you don't have explicit permission to test.

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.shion.dev/api?username=Mr-Robotiko&theme=github_dark&hide_border=true&bg_color=00000000" />
  <img alt="GitHub stats" src="https://github-readme-stats.shion.dev/api?username=Mr-Robotiko&theme=default&hide_border=true&bg_color=00000000" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.shion.dev/api/top-langs/?username=Mr-Robotiko&theme=github_dark&hide_border=true&layout=compact&bg_color=00000000" />
  <img alt="Top languages" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Mr-Robotiko&theme=default&hide_border=true&layout=compact&bg_color=00000000" />
</picture>

</div>
