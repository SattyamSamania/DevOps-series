#  Networking for DevOps


## 🌐 What is Networking?

Imagine your laptop is a house. And the internet is a big city full of houses (other devices). Networking is like the roads and phone lines that help all these houses talk to each other.

In technical terms, networking is the way computers and servers communicate with each other.

Whether you’re visiting a website, deploying an app, or pushing code to a remote server, networking is happening behind the scenes.
Networking helps systems:
- Transfer files
- Access websites
- Deploy code to servers

---

## 🧱 Basic Networking Terms

| Term | Meaning |
|------|---------|
| **IP Address** | Unique address for each device |
| **DNS** | Phonebook of the internet |
| **MAC Address** | Unique ID for each network device |
| **Port** | Virtual doors for services (e.g. 80 for HTTP) |
| **Protocol (TCP/UDP)** | Rules of data transfer |
| **Subnet** | Smaller network inside a bigger one |
| **Firewall** | Security guard for network traffic |

---

## 📚 Understanding the OSI Model

The **OSI (Open Systems Interconnection)** Model is a set of rules that explains how different computer systems communicate over a network. OSI Model was developed by the International Organization for Standardization (ISO). The OSI Model consists of 7 layers and each layer has specific functions and responsibilities.

Imagine sending a letter to your friend. The OSI model is like the steps your letter goes through, from writing it to your friend finally reading it.

1. **Application** – You write a message to your friend (e.g., "Hi! How are you?") using a messaging app like WhatsApp or Gmail.
 - It’s the software we see and use.

2. **Presentation** – Your app converts the message to a format both you and your friend understand (like emojis, pictures, etc.).
 - Takes care of data format, encryption, etc.

3. **Session** – A conversation is started between you and your friend. Keeps track of when it starts and ends.
 - Handles communication sessions

4. **Transport** – Your message is split into parts and given a number so it reaches in the right order.
 - Ensures reliable delivery (using TCP or UDP).

5. **Network** – Finds the best path to send the message to your friend.
 - Uses IP address (like a GPS for the internet).

6. **Data Link** – Adds info to send the message from one device to another on the same network (like routers, switches).
 - Uses MAC address here.

7. **Physical** – Actually sends the message using wires, Wi-Fi, or fiber cables.
 - Deals with real hardware and signals.

---

## 📦 Understanding the TCP/IP Model

A simplified version of OSI used in the real world.

| Layer | OSI Equivalent | Purpose |
|-------|----------------|---------|
| **Application** | Combines App + Presentation + Session | Browsers, email, etc. |
| **Transport** | Same | Reliable delivery (TCP/UDP) |
| **Internet** | Network Layer | Routing using IP |
| **Network Access** | Data Link + Physical | Data transfer over hardware |

---

## 📡 Protocols and Ports Every DevOps Engineer Should Know

| Protocol | Port | Purpose |
|----------|------|---------|
| **HTTP** | 80 | Basic web access |
| **HTTPS** | 443 | Secure web access |
| **SSH** | 22 | Connect to remote servers |
| **FTP** | 21 | File transfer |
| **DNS** | 53 | Domain resolution |
| **SMTP** | 25 | Send emails |
| **IMAP** | 143 | Read emails |
| **POP3** | 110 | Download emails |

---

## 🛠 Essential Networking Commands

| Command | Purpose | Usage |
|---------|---------|-------|
| `ping` | Check connection | Test server reachability |
| `traceroute` / `tracert` | Show route path | Identify bottlenecks |
| `nslookup` | Get IP of a domain | Debug DNS |
| `curl` | Make web requests | API testing |
| `netstat` | Show open ports | Find port conflicts |
| `ifconfig` / `ip a` | Show IP info | Network setup |
| `nmap` | Scan for open ports | Security checks |


> **Don’t just learn it – practice it.** Run these commands, explore the layers, and get hands-on!

