# cis379.github.io

Charles S's Research Projects

# 🌟 Welcome to My Portfolio! 🌟

Hi there! I'm Charles, a passionate tech enthusiast diving into **Networking, Data Science, API Development, and Cybersecurity**. This repository is still under construction, however I'll be adding my codebase for my basic trust and safety classifiers I've been developing using BlueSKy and OpenAI's API's.    

## 🔍 About Me
- 💻 Former Army Ranger, Cyber Command Intelligence Officer, and Twitter Trust and Safety Alum
- 📚 Currently at Johns Hopkins University Applied Physics Lab building cyber targeting solutions.
- 🌎 Open to collaboration on interesting ideas.

---

## 🧪 My Cyber Home Lab Setup

This a conceptual overview of my personal home lab environment, designed for cybersecurity practice, learning, and experimentation.

### Core Components:

1.  **Home Router:**
    * The central gateway providing internet connectivity to the lab and segmenting the internal network.

2.  **Kali Linux Laptop:**
    * **Role:** Offensive security operations and network analysis.
    * **Key Activities:**
        * Conducting penetration testing scans against internal lab targets (VMs and server).
        * Performing Open Source Intelligence (OSINT) gathering, utilizing a Tor tunnel for anonymized internet access.

3.  **Ubuntu Server:**
    * **Role:** Centralized server hosting various network services and tools.
    * **Services Hosted:**
        * **OpenVPN:** Provides secure remote access to the lab network.
        * **Pi-Hole:** Network-wide ad and tracker blocking.
        * **Squid Proxy:** Web proxy for caching and traffic filtering.
        * **Webcheck (Docker):** A containerized application for website monitoring or analysis.
        * **SQL Server:** Database server for various applications and projects.
        * **Ollama (LLM):** Local Large Language Model hosting for AI experimentation.
    * **Connectivity:** Connected to the home router for necessary internet access for its services.

4.  **Windows Workstation:**
    * **Role:** General purpose workstation and virtualization platform for hosting target machines.
    * **Key Software/Activities:**
        * **VirtualBox:** Runs multiple virtual machines (e.g., "Target VM 1", "Target VM 2") for testing and exploitation practice.
        * **Web Exploration:** Used for general internet browsing and research, with traffic routed through the home router.

### Network Flow & Activities:

* **Internal Network Traffic:** The Kali Linux laptop and Windows Workstation communicate with the Ubuntu Server and each other over the local network.
* **Pentesting Scans (LAN):** The Kali Linux machine actively scans and interacts with the virtual machines on the Windows Workstation and services on the Ubuntu Server for security testing purposes.
* **OSINT via Tor:** The Kali Linux machine routes specific OSINT-related traffic through the Tor network (via the Home Router) for anonymity before reaching the wider internet.
* **Web Exploration:** The Windows Workstation accesses the internet for general browsing through the Home Router.
* **Services Online:** The Ubuntu Server connects through the Home Router to allow its services (like OpenVPN, or potentially web-hosted applications) to be accessible or to fetch updates.

This setup allows for a flexible and isolated environment to practice a variety of cybersecurity skills, from network reconnaissance and exploitation to defensive configurations and service management.

---

## 📫 Connect with Me
- LinkedIn: [https://www.linkedin.com/in/charles-alexander-smith/](#)

---

Stay tuned for updates! 🚀
