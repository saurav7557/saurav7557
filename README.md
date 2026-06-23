<div align="center">

# Saurav Kumar

**Backend & Full-Stack Developer · Java · Spring Boot · React · Blockchain**

B.Tech Computer Science — Rungta College of Engineering & Technology · Graduated June 2026

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saurav-kumar-5b03a9391)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sauravkumar9447@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/saurav7557)
[![Twitter](https://img.shields.io/badge/X%2FTwitter-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/sauravkcode)

**Open to full-time SDE / Full-Stack / Backend roles and internships — available immediately.**

</div>

---

## What I Build

I work across the full stack with a focus on backend systems, security, and applied AI. My recent work covers distributed payment architecture, blockchain credentialing, and computer vision pipelines — built end-to-end, deployed, and documented.

---

## Featured Projects

### [MeshPay — Offline UPI Settlement Network](https://github.com/saurav7557/MeshPay)
**Java · Spring Boot · PostgreSQL · AES-256-GCM · RSA-OAEP · Docker · Render**

UPI payments that survive basements and dead zones. Payment packets are encrypted on the sender's device, hop peer-to-peer through nearby phones that can't read them, and settle the moment any device gets connectivity.

Three concrete things this proves:
- A payment travels through untrusted intermediaries with zero information leakage — hybrid RSA-OAEP + AES-256-GCM, same scheme as TLS
- Three bridge nodes deliver the same packet simultaneously — exactly one settles, two are rejected as duplicates — via atomic `ConcurrentHashMap.putIfAbsent` (Redis `SETNX` semantics)
- Tampered or replayed packets are rejected before touching the ledger — GCM auth tag + `signedAt` freshness check

**Live demo:** https://meshpay-hw8w.onrender.com · **Swagger:** https://meshpay-hw8w.onrender.com/swagger-ui.html

---

### [Blockchain Certificate System](https://github.com/saurav7557/Blockchain-Certificate-System)
**Solidity · Ethereum · IPFS · Helia · React**

Tamper-proof digital certificates issued as NFTs on Ethereum and pinned to IPFS via Helia. Verifiable by anyone on-chain — no central authority required. Eliminates credential fraud without a trusted intermediary.

- Smart contract handles issuance, ownership, and revocation
- IPFS stores certificate metadata; only the content hash lives on-chain
- React frontend for institution-side issuance and student-side verification

---

### [FarmFlo — Agricultural Marketplace](https://github.com/saurav7557/FarmFlo)
**React.js · Node.js · Express · MongoDB**

Full-stack marketplace connecting farmers directly to buyers — no middlemen, no commission layer. Built with a REST API backend, JWT auth, and a mobile-responsive React frontend.

---

### [AR FloorPlan Detection](https://github.com/saurav7557/AR-FloorPlan-Detection)
**MATLAB · Computer Vision · 3D Visualization**

Detects structural elements from 2D architectural blueprints and renders them as navigable 3D spatial models in real time. Built entirely in MATLAB using image processing and projection geometry.

---

### [Dynamic Portfolio Generator](https://github.com/saurav7557/Dynamic-Portfolio)
**React.js · JSON · CSS**

JSON-driven portfolio generator — swap one config file, get a fully personalized site. No-code customization, clean component architecture, and zero hard-coded content.

---

### [Library Management System](https://github.com/saurav7557/Library-Management-System)
**Java · Cross-platform · Secure Auth**

Desktop and web application for managing academic resources, lending records, and user roles. Includes auth, fine calculation, and inventory tracking.

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**AI / ML / Vision**

![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=flat-square&logo=google&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

**Blockchain**

![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=flat-square&logo=ipfs&logoColor=white)
![Web3.js](https://img.shields.io/badge/Web3.js-F16822?style=flat-square&logo=web3dotjs&logoColor=white)

---

## Competitions

- **Hackindia Spark 4 · 2025** — Built a JavaScript-based solution under competitive time constraints with team *Tech No Logic*
- **GDG Solution Challenge** — Delivered a Python project addressing a real-world accessibility problem

---

## Contact

**sauravkumar9447@gmail.com** · [LinkedIn](https://www.linkedin.com/in/saurav-kumar-5b03a9391) · [Twitter/X](https://twitter.com/sauravkcode)

Available immediately for full-time SDE, full-stack, backend roles, and internships.
