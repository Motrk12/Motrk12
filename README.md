<h1 align="center">Hi, I'm Mohamed Tarek 👋</h1>

<p align="center">
  <b>Cybersecurity student · Network engineering · Full-stack development</b><br>
  Third-year B.Sc. Cybersecurity at Misr International University (MIU), Egypt
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohamed-tarek-64385a3b0"><img src="https://img.shields.io/badge/LinkedIn-Mohamed_Tarek-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="mailto:moh.tarek.arafa@gmail.com"><img src="https://img.shields.io/badge/Email-moh.tarek.arafa-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open_to-Internships_%26_Junior_roles-2EA44F?style=for-the-badge" alt="Open to internships and junior roles">
</p>

---

### About me

- 🛡️ I study **cybersecurity** at MIU (2024 to present, graduating 2027) and work on network deployment, secure web development and AI-driven security.
- 🌐 As a **Network Engineer Intern at Injaz Tech**, I helped deploy a school's complete network in Cairo Festival City, from the MDF/IDF to the access points.
- 🩺 I built a **veterinary clinic management system** that is now in use at **7 clinics** in Cairo and Alexandria.
- 🔎 I'm looking for **internships and junior roles** in cybersecurity, networking or software development.

---

### 🚀 Featured projects

#### 🦠 [Project Revenant](https://github.com/Motrk12/Renevant): AI intrusion detection & self-healing file recovery
`C# / .NET 8` `Python` `FastAPI` `LightGBM` `PyTorch` `ONNX` `PostgreSQL` `React + TypeScript` `Docker` · *Team of 5*

An AI intrusion detection system that protects a Windows PC from malware, ransomware and network attacks, and automatically restores the files an attack damages.

- A **native Windows agent** streams file, process and network telemetry over **mutual TLS** to a management laptop. Three ML models score it there: LightGBM on EMBER2024 and CIC-IDS2017, and a PyTorch GRU on RanSAP, all served as ONNX.
- The laptop answers with **Ed25519-signed commands** (terminate, quarantine, isolate, delete, restore). Detections are mapped to **MITRE ATT&CK**, and every response step is recorded in a **hash-chained audit log**.
- Before a protected file changes, the agent pushes the old version to a **write-only vault**. Ransomware on the PC can't read or delete the backups.
- **Results:** across 10 end-to-end runs, the median time from detection to the last file restored was **0.476 s**, and **80/80 files** came back byte-identical and hash-verified.

#### 🩺 Veterinary Clinic Management System
`Next.js 14` `React` `TypeScript` `Tailwind CSS` `Supabase (PostgreSQL, Auth, RLS)` `Vercel` `Claude Code`

A bilingual Arabic/English clinic management system **rolled out to 7 veterinary clinics** (5 in Cairo, 2 in Alexandria). I was the developer and product owner, so I handled requirements, roles and workflows, testing with clinic staff, migrations, deployment and rollout.

- **PostgreSQL Row Level Security** enforces role-based access, so vets never see purchase prices. **Cloudflare Turnstile** protects the login.
- I migrated six Excel workbooks into a normalized PostgreSQL schema with full history. Split and part payments reconcile at the daily close.
- About **20,000 lines** of TypeScript and SQL across **26 migrations**, with PDF receipts, an Excel export with no dependencies, and WhatsApp messaging.

<sub>🔒 The source code is private.</sub>

#### 🛍️ NileDrip, a clothing marketplace
`HTML` `CSS` `JavaScript` `Node.js` `Express` `MongoDB` `JWT` `Vercel`

A marketplace for Egyptian local brands with customer, seller and admin roles: listings, cart and wishlist, checkout, orders and reviews. The API uses JWT authentication and protected routes. Sellers and admins get bilingual dashboards for moderation, orders and analytics.

---

### 🧰 Open source

| Project | What it is | Stack |
|---|---|---|
| [**Revive**](https://github.com/Motrk12/ReviveDesktop) | A Windows app that recovers deleted photos, videos and documents from memory cards, USB sticks, drives and the Recycle Bin. It reads NTFS, FAT and exFAT, has a deep scan that carves files from free sectors, and never writes to the source drive. | C# · .NET |
| [**HyperCheck AI**](https://github.com/Motrk12/HyperCheck-AI) | A passive DevSecOps scanner for security misconfigurations in local web apps. It extracts 100+ features from headers, cookies and config and scores the risk with a Random Forest model. | Python · scikit-learn |
| [**Connect-4**](https://github.com/Motrk12/Connect-4-) | A JavaFX Connect 4 game with login, PvP and PvAI modes, AI difficulty strategies and score tracking. | Java · JavaFX · OOP |

---

### 💼 Experience

**Network Engineer Intern · Injaz Tech** · *Aug 2026 to Sep 2026*
- Deployed a school's complete network in Cairo Festival City, from the MDF and IDF through modular and access switches to the wireless access points.
- Set up the firewalls and UPS power protection as part of the build-out.

**Google Cloud Introductory / Internship Program**
- Completed introductory cloud training, with some exposure to Flutter mobile UI.

---

### 🛠️ Skills

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,py,java,cpp,cs,dotnet,nextjs,react,nodejs,express,fastapi,tailwind,html,css,postgres,supabase,mongodb,redis,pytorch,docker,vercel,cloudflare,git,github&perline=13" alt="Tech stack">
</p>

| Area | Skills |
|---|---|
| **Security** | Role-based access control · PostgreSQL RLS · JWT & bcrypt · Mutual TLS · Ed25519 signing · Cloudflare Turnstile · Firewalls · Malware detection & recovery · MITRE ATT&CK |
| **Networking** | Routing & switching · VLANs · OSPF · EIGRP · DHCP · DNS · MDF/IDF build-out · Wireless APs · Cisco Packet Tracer |
| **Programming** | TypeScript · JavaScript · Python · C# · Java · C++ · SQL |
| **Web & backend** | React · Next.js · Node.js · Express · FastAPI · .NET · Tailwind CSS · REST APIs · HTML/CSS |
| **AI / ML** | LightGBM · PyTorch · scikit-learn · ONNX |
| **Data, cloud & tools** | PostgreSQL · Supabase · MongoDB · Redis · Docker · Vercel · Git & GitHub · Claude Code |

---

### 📜 Certifications & courses

| | |
|---|---|
| <img src="https://img.shields.io/badge/-Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Cisco"> | **CCNA: Introduction to Networks**, Cisco Networking Academy |
| <img src="https://img.shields.io/badge/-Huawei-FF0000?style=flat-square&logo=huawei&logoColor=white" alt="Huawei"> | **HCIA-Datacom**, Huawei ICT Academy |
| <img src="https://img.shields.io/badge/-Huawei-FF0000?style=flat-square&logo=huawei&logoColor=white" alt="Huawei"> | **HCIA-AI V4.0**, Huawei ICT Academy (2026) |
| <img src="https://img.shields.io/badge/-AWS-FF9900?style=flat-square" alt="AWS"> | **Generative AI Foundations** and **Machine Learning Foundations**, AWS Academy Graduate |
| <img src="https://img.shields.io/badge/-NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA"> | **Fundamentals of Deep Learning**, NVIDIA (2026) |
| <img src="https://img.shields.io/badge/-SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white" alt="SAP"> | **Exploring End-to-End Business Processes in SAP**, SAP Learning (Intermediate, 2026) |

---

### 🗣️ Languages

**Arabic** (strong) · **English** (strong) · **German** (beginner)

<p align="center"><sub>Feel free to reach out on LinkedIn or by email. I'm always happy to talk about security, networks or a project idea.</sub></p>
