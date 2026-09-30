# Hi, I'm Krishna Karra 👋

Computer Science senior at the **University of Missouri–Columbia** building systems where **software meets the physical world**: field sensors, embedded controllers, real-time data pipelines, and intelligent applications.

- 🔬 Undergraduate Research Fellow building IoT and environmental sensing systems for agriculture and wildlife-refuge monitoring
- ⚛️ Former Quantum AI Research Intern at the Mizzou Quantum Innovation Center
- 🏅 2026 University of Missouri Award for Academic Distinction (one of 15 undergraduates selected)
- 🎤 Presented research at **AGU Fall Meeting 2025** and **NCUR 2026**
- 🏆 1st Place, TigerHacks 2024, and now HackerX Lead organizing TigerHacks
- 🌱 Interested in **embedded & cyber-physical systems, IoT platforms, edge computing, and reliable data pipelines**

---

## 🔬 Research

**Smart Irrigation System, South Farm Research Center** · *Undergraduate Research Fellow, Hydrology Lab*
- Designed and deployed a semi-automated micro-irrigation system that schedules water from reference evapotranspiration (ET₀) instead of fixed timers
- Solar-powered pumps, pressure/flow regulation, a Raspberry Pi scheduler, and an ESP32 valve controller programmed with ESPHome
- Integrated 20+ soil-moisture, temperature, flow, and weather sensors into one pipeline with a real-time dashboard for remote monitoring and control

**Environmental Monitoring, Swan Lake National Wildlife Refuge**
- Helped plan and build a low-cost telemetry system for a multi-station monitoring network at a remote federal site
- Campbell Scientific dataloggers post over cellular (HTTPS) to a Google Cloud VM (nginx, gunicorn, TLS), with a Flask dashboard serving live station data to the public

**Longitudinal Audit of Google AI Overviews** · *manuscript under peer review*
- Built the parallel data collection pipeline behind the study: 2,402 health queries in English and Spanish across three waves
- Four-worker architecture cut each wave from ~30 hours to as few as 3; checkpointed resume/retry recovered every query after rate-limit failures
- Logged **14,812 captures** and **134,879 cited source URLs**

**Quantum Machine Learning** · *Mizzou Quantum Innovation Center, Summer 2026*
- Benchmarked quantum kernel methods and variational quantum classifiers against classical SVM baselines across 72 walk-forward folds of a ~10,000-record multimodal dataset
- Traced the performance ceiling to kernel variance collapse with circuit depth; validated results on IBM superconducting hardware

---

## 🚀 Featured Projects

### 🌾 AgBot: Crop Disease & Pest Intelligence
Hybrid pipeline pairing CNN-based disease and pest classification (EfficientNet-B0, ResNet-50) with LLM-generated treatment recommendations, deployed as a web app for in-field decision support.
`Python` `Computer Vision` `LLMs`

### 🔎 OmniSearch: AI Answer Aggregation & Drift Tracking
Multi-platform pipeline that normalizes Google SerpApi, Perplexity, Brave, and YouTube Data API results into a unified Pydantic schema, with timepoint-based versioning to track AI response drift across 5+ languages.
`Python` `Pydantic` `REST APIs`

### 🌱 [IoT Greenhouse Controller](https://github.com/krishna684/IoT-GreenHouse-Controller)
Automated greenhouse monitoring and control: soil-moisture-triggered irrigation, temperature-driven fan control, LDR light sensing, and an LCD status display.
`C++` `Arduino` `Embedded Systems`

### 💰 [iFINANCE Web Application](https://github.com/krishna684/Group19_iFINANCEAPP)
Financial accounting platform implementing double-entry bookkeeping, with role-based authentication, a validated transaction ledger, trial balance and balance sheet generation, and automated PDF reports.
`ASP.NET MVC` `C#` `SQL Server`

### 🤖 [Mental Health Check-in Bot](https://github.com/krishna684/mental-health-bot)
Conversational check-in assistant with mood-based flows, persistent chat history, and animated SVG transitions.
`Next.js` `OpenAI API` `Tailwind CSS`

### 📦 [Lost & Found Management System](https://github.com/krishna684/lost-found-management)
Campus platform for reporting and retrieving lost items, with admin moderation and database-driven matching.
`PHP` `MySQL` `HTML/CSS`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

**Embedded, IoT & Edge**

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ESPHome](https://img.shields.io/badge/ESPHome-000000?style=for-the-badge&logo=esphome&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home_Assistant-18BCF2?style=for-the-badge&logo=homeassistant&logoColor=white)

**Web & Backend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

**Data, Cloud & DevOps**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**AI & Quantum**

![PyTorch](https://img.shields.io/badge/Computer_Vision-EE4C2C?style=for-the-badge&logo=opencv&logoColor=white)
![OpenAI](https://img.shields.io/badge/LLM_Integration-412991?style=for-the-badge&logo=openai&logoColor=white)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)

---

## 🎓 Education

**B.S. Computer Science**, University of Missouri–Columbia · *Expected December 2026*
Minor in Information Technology · Certificate in Web & Mobile Applications Development

---

## 🏆 Awards & Recognition

- 🏅 **University of Missouri Award for Academic Distinction**, 2026
- 🎓 **Undergraduate Research Fellowship (URF)**, University of Missouri, 2025
- 🎤 **Presenter:** AGU Fall Meeting 2025 · National Conference on Undergraduate Research 2026 · MU Show Me Research Week 2025 & 2026
- 📰 Featured in Mizzou Engineering: *"Computer Science Students Take on Neuroscience"* (2026)
- 🏆 **1st Place, TigerHacks 2024**
- 🎖 **Upsilon Pi Epsilon** Honor Society · High Dean's List
- 🤖 Robotics championship wins (IIT Kharagpur national & state competitions)

---

## 🤝 Leadership & Involvement

- **HackerX Lead, TigerHacks**: organizing Mizzou's flagship hackathon
- **Teaching Assistant, ENGR 1000 & 1050**: supported 40+ students weekly (2025–2026)
- **Web Master, Cultural Association of India**: helping organize *Indianite*, the 34th Annual India Night
- **STEM Outreach Lead**: robotics challenges for high school students at the Geospatial Science Summer Camp (2025, 2026)
- **Publicity Director, Missouri International Student Council** (2025–2026)
- **Student Supervisor, Campus Dining Services**

---

## 📊 GitHub Stats

![Krishna's GitHub stats](https://github-readme-stats-sigma-five.vercel.app/api?username=krishna684&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=krishna684&layout=compact&theme=tokyonight)
![GitHub Streak](https://streak-stats.demolab.com?user=krishna684&theme=tokyonight)

---

## 📫 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-krishna684-181717?style=for-the-badge&logo=github)](https://github.com/krishna684)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Krishna%20Karra-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/krishnarithwikkarra)
[![Email](https://img.shields.io/badge/Email-kkffz%40missouri.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kkffz@missouri.edu)

---

💡 *I like building systems that keep working after they leave the lab: sensors in a field, stations at a remote refuge, pipelines that don't drop a single record.*
