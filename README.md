# Moodle Web3 + ZK Developer Program

Moodle Web3 integrates the popular Moodle LMS with Web3 tools, creating a decentralized educational platform that enables secure digital asset management, NFT certifications, and blockchain notifications. This system brings education into the decentralized era, fostering blockchain adoption through interactive and real-world educational applications.

The ZK Developer Program is an online bootcamp aiming to train Latin American developers in Zero-Knowledge (ZK) technologies, expanding the region’s contributions to open-source projects within the cryptography space. This program builds upon insights from the LATAM PSE Core Program to deliver structured learning and practical development in ZK technologies.

## 📋 Table of Contents
- [Moodle Web3 + ZK Developer Program](#moodle-web3)
  - [📋 Table of Contents](#-table-of-contents)
  - [👥 Team Information](#-team-information)
    - [Project Members](#project-members)
  - [🛠 Technical Approach](#-technical-approach)
    - [Components](#components)
  - [🗺 High-Level Outline](#-high-level-outline)
    - [Moodle Components](#moodle-components)
    - [Middleware Web Server](#middleware-web-server)
    - [Ethereum Wallet Integration](#ethereum-wallet-integration)
  - [🌐 Web3 Integration Benefits](#-web3-integration-benefits)
    - [Key Benefits:](#key-benefits)
  - [🌟 Transforming Education with Web3](#-transforming-education-with-web3)
  - [🏆 Sponsors](#-sponsors)
  - [🎯 Project Goals](#-project-goals)
  - [📚 Lessons Learned](#-lessons-learned)
  - [🔗 Project Links](#-project-links)
  - [🎥 Video Demo](#-video-demo)

## 👥 Team Information
### Project Members
**Name:** Alex Padilla (@padimaster)  
**GitHub:** [padimaster](https://github.com/padimaster)  
**Discord:** padimasterec  
**Role:** Fullstack Developer  
**Contributions:**
- Developed the API Middleware to connect Moodle with Push Protocol for event-based notifications (e.g., user enrollments, course completions).
- Created Smart Contract Factory to issue NFT certifications directly to students' Ethereum wallets.
- Integrated Push Protocol with automated group creation and real-time notifications per course.
- Configured a scalable Docker-based server for deployment.

**Name:** Paul Rodas  
**GitHub:** [0xarcano](https://github.com/0xarcano)  
**Discord:** 0xarcano  
**Role:** Senior Developer / DevOps  
**Contributions:**
- Developed a Moodle PHP plugin for Push Protocol, enabling event-driven notifications for actions like course enrollments, completions, and quiz submissions.
- Set up Docker configurations for streamlined Moodle deployment.

**Name:** Carlos Jimenez  
**GitHub:** [cijimenez](https://github.com/cijimenez)  
**Discord:** carlos_israelj  
**Role:** Developer  
**Contributions:**
- Integrated Moodle with MetaMask for secure Web3 Login and user creation with wallet connections in Moodle’s database.

**Name:**  Nathalia Barreiros
**GitHub:** NathaliaBarreiros  
**Discord:** nathbarreiros   
**Role:** Developer - Instructor

**Name:** Daniel Arroyo  
**GitHub:**  daniel0ar
**Discord:** daniel0ar 
**Devfolio Username:** 
**Role:** Smart Contract and FE developer 

**Name:** Lucila Pastore   
**GitHub:** lucilapastore
**Discord:** lucilajuliana 
**Devfolio Username:** lucilajuliana
**Role:** Technical PM  

## 🛠 Technical Approach
### Components
- Frontend: ✅
- Backend: ✅
- Smart Contracts: ✅
- ZK Circuits: ❌
- Machine Learning (ML): ❌

## 🗺 High-Level Outline

### Moodle Components
- Custom Moodle LMS: Manages courses, students, and data within a decentralized framework.
- Moodle Database: Stores user, course, and event information, with modifications to support web3 functionalities.

### Middleware Web Server
- Event-Driven Middleware: Links Moodle with Push Protocol to capture events (e.g., enrollments, course completions) and trigger notifications.
- Push Protocol Integration: Enables real-time notifications for new content, deadlines, and updates, engaging students through blockchain-enabled messaging.

### Ethereum Wallet Integration
- Web3 Login: Allows students to log in using their Ethereum wallets, improving security and introducing blockchain credentials.
- NFT Certifications & POAPs: Students receive NFTs as proof of course completions, creating verifiable, tamper-proof digital credentials.
- Smart Contract for Certifications: Deploys an ERC721 smart contract, issuing unique NFTs as certifications, accessible within students' Ethereum wallets.

<img width="405" alt="image" src="https://github.com/user-attachments/assets/a9048b92-1e4f-4408-a8d1-4c865a4f5e3b">


## 🌐 Web3 Integration Benefits
Moodle Web3 leverages blockchain technology to enhance educational accessibility, engagement, and credential security. This integration exemplifies the tangible benefits of blockchain in real-world scenarios.

### Key Benefits:
- Increased Engagement: Real-time notifications through Push Protocol keep students updated, fostering higher engagement and retention.
- Decentralized, Secure Access: Wallet-based logins enhance security while familiarizing users with blockchain-based identity management.
- Verifiable Credentials: NFT-based certifications offer students an authenticated, tamper-proof record of their achievements.

## 🌟 Transforming Education with Web3
By integrating web3 elements like wallet logins, NFT certifications, and decentralized notifications, Moodle Web3 empowers students and educators to explore blockchain technology in a practical setting, promoting understanding and widespread adoption.

### ZK Developer Program Components
- Program Content: Covers ZKPs, focusing on ZK-SNARKs and ZK-STARKs using Circom and Halo2.
- Community Contributions: “Good First Issues” and documentation projects for PSE projects.
- Mentor-Led Structure: Open to the LATAM region with progressive layers, personalized office hours, and access to PSE repositories.
  
## 🏆 Sponsors
- Push Protocol ✅
- PSE ✅

## 🎯 Project Goals
- **Moodle Web3 Goals:** Build a decentralized educational platform that leverages blockchain to foster engagement and verifiability in online learning.
- **ZK Developer Program Vision:** Scale LATAM’s contributions to privacy and cryptography through hands-on learning, access to mentorship, and a structured curriculum.
- **Future Collaboration:** Partnerships are encouraged to expand Web3 and PET adoption in education, targeting both students and institutions.

## 📚 Lessons Learned
- **Interoperability of Web2 & Web3:** Successfully bridging a traditional LMS with Web3 tools.
- **Importance of Reusable Code:** Maintaining scalable, community-friendly codebases for Moodle Web3 and ZK educational programs.
- **User Experience in Decentralization:** Balancing the technical complexities of Web3 and privacy technologies with an accessible user experience.

## 🔗 Project Links
- [ZKLP Final Submission](https://www.canva.com/design/DAGVyfW9XEE/Cn8ak01eYwPkuH-CK6YZVA/edit?utm_content=DAGVyfW9XEE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- [Moodle Web3 Repository](https://github.com/Privacy-Lab-Latam-Builders/moodle-web3)
- [Source Code - Custom Moodle](https://github.com/Privacy-Lab-Latam-Builders/moodle)
- [Source Code - Certifications Smart Contract](https://github.com/padimaster/certifications-smart-contract)
- [Source Code - Middleware Webserver and DB](https://github.com/padimaster/moodle-web3)
- [Docker Image - Middleware Webserver and DB](https://hub.docker.com/repository/docker/padimaster/moodle-push/general)
- [Source Code - Moodle Wallet Integration](https://github.com/Privacy-Lab-Latam-Builders/moodle/tree/login-web3)

---

## 🎥 Video Demo
- [Project Link](https://drive.google.com/file/d/1gAhVLpTACJlL_sYz9cHEVLpWEtlVS4PJ/view?usp=sharing)
