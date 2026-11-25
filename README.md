### Hi there, I'm [Diego Peña Vicente](https://www.linkedin.com/in/diegopenavicente/) 👋

I am a Mechanical Engineer turned **Software Architect**. I design and build full-stack platforms end to end, from the database and backend APIs to 3D web interfaces and the DevOps pipeline behind them. I care about clean code, solid architecture, and software that solves real engineering and business problems.

**What I'm into**:
- Software as a Service (SaaS) and multi-tenant architecture
- Engineering software and 3D simulation on the web
- AI-assisted tooling (LLMs, MCP)
- Data processing and integrations

**I am open to**:
- SaaS and web platform projects
- Collaborations on engineering and simulation software
- Architecture reviews and consulting

## 🚀 What I'm working on

- **Mid 2025 – Present · [Isomorphic Software](https://smartclient.com/)**  
  Working on the **SmartClient** framework, its **Showcase** and **Reify**, Isomorphic's low-code visual builder.  
  - Built new **Java-based Showcase examples and connectors**, including **Model Context Protocol (MCP)** integration (e.g., GitHub Copilot API), **Parquet file readers** and **Delta Share integrations**.  
  - Testing **Reify** and **AUN**, reporting and verifying fixes across releases.  
  - Building **automated tests for the SmartClient Showcase**, so examples are checked on every release.

- **2025 – Present · [Digital Process IT](https://www.digitalprocessit.com/) · Founder & Software Architect**  
  My own software company. I design, build and run its products, starting with **PuntoCita**.  
  - Designed and built the **company platform** (Laravel): clients, contracts, quotes, invoices, billing follow-up and support tickets.  
  - Built **automated tenant provisioning** for SaaS customers: signup requests, trial plans, test vs. production environments, and per-tenant SMTP and seeding.

- **2025 – Present · [Medialítica](https://medialitica.pe/) · Co-founder & Lead Developer**  
  Digital marketing agency I run with a partner. I lead everything technical: client websites, online stores, integrations and handover.  
  - Built websites and e-commerce for clients in food, retail, footwear, printing, flowers, industrial supply, medical distribution and manufacturing.  
  - Custom **WordPress block themes** (`theme.json` brand tokens, no page builders), **WooCommerce** stores with card and Yape payments, and **Astro** sites, shipped through **GitHub Actions** to **Hostinger**.  
  - Lead capture and compliance: chatbot and form leads synced to **Google Sheets** (Apps Script), Peru's virtual complaints book (*Libro de Reclamaciones*), WhatsApp contact routing, and **Google Ads / Tag Manager** conversion tracking.  
  - Client handover: a Python tool that generates each client's **admin guide PDF** from a YAML file, plus branded thank-you graphics rendered from HTML with Playwright.

- **2026 – Present · [PuntoCita](https://puntocita.com) · SaaS product of Digital Process IT (Founder & Architect)**  
  A **multi-tenant booking and business management SaaS** for service businesses: salons, nail studios, barbershops, dental clinics, podiatry, nutrition and therapy.  
  - Every business gets its own site (`yourbusiness.puntocita.com`) or connects its own domain, plus an admin panel to run the business.  
  - Online booking 24/7, staff schedules, multi-location agendas, automatic reminders and loyalty.  
  - Online payments and deposits through **Culqi** (cards, Yape, wallets).  
  - Vertical features such as a **digital odontogram** for dentists and consent forms for clinics.  
  - Public API so clients can run a fully custom front end on their own hosting.  
  - Stack: **Java 21 + Spring Boot**, **React + TypeScript (Vite)**, **PostgreSQL**, monorepo with shared types and i18n, Nginx and Jenkins CI/CD.  
  - Live demos: [barbershop](https://barbershop.puntocita.com/) · [sonrisafeliz](https://sonrisafeliz.puntocita.com/) · [podologia](https://podologia.puntocita.com/) · [superpet](https://superpet.puntocita.com/)

- **2026 – Present · [OCS – Overhead Contact System Design Platform](https://github.com/DiegoPevi05/ocs) · Personal open-source project**  
  An engineering platform for **designing, calculating and simulating railway overhead contact lines** (catenary systems). [Watch the demo ▶](https://www.youtube.com/watch?v=OpfH7FzPALA)  
  - **2D/3D visual editor** (React, TypeScript, **Three.js**) for tracks, foundations, poles, cantilevers and spans, with DXF import.  
  - **C++17 calculation engine** that solves cantilever geometry, catenary physics, dropper lengths and fabrication cut lists, plus a **truss solver** for stress and utilization.  
  - **Real-time streaming** of results over STOMP/WebSocket from a **Java 21 / Spring Boot** API backed by PostgreSQL.  
  - **AI-assisted design**: an LLM places poles, cantilevers and spans while engineering rules are enforced in code.  
  - **Train simulation** that checks zigzag, contact wire height and pantograph contact live, plus PDF reports.

## 📁 Projects (2025 – 2026)

#### Products & platforms

| Project | Year | What it is | Stack |
|---|---|---|---|
| **[PuntoCita](https://puntocita.com)** | 2026 | Multi-tenant booking & business management SaaS for service businesses, with a public API for custom front ends and a series of per-vertical video ads (nails, vets, barbershops, nutritionists) built as code with HyperFrames. | Java 21, Spring Boot, React, TypeScript, PostgreSQL, Jenkins |
| **[OCS](https://github.com/DiegoPevi05/ocs)** | 2026 | Railway overhead contact line design platform: 2D/3D editor, C++ calculation engine, train simulation and AI-assisted design. | C++17, Java 21, Spring Boot, React, Three.js, PostgreSQL |
| **Digital Process IT platform** | 2025 | Company platform for clients, contracts, quotes, invoices, support tickets and automated SaaS tenant provisioning. | Laravel, PHP, MySQL |

#### Custom PuntoCita front ends

Brand-specific websites that run on the PuntoCita public API, so the business keeps its own design and domain while bookings, staff and payments live in the SaaS.

- **[Luas Studio](https://luastudionails.com)** – nail studio site (Astro, React, Tailwind CSS v4).
- **Nuna** – custom client app deployed on its own domain on top of the PuntoCita API.

#### Client websites & e-commerce (Medialítica)

Custom WordPress themes (block themes with `theme.json` brand tokens, no page builders) and Astro sites, so clients can edit their own content. Most ship through GitHub Actions to Hostinger.

- **[INANNA](https://inannacheesecakes.com)** – cheesecake bakery: website, shop and admin guide for the owner.
- **[Grupo Hanzing](https://www.grupohanzing.com/)** – corporate B2B site for a Mexican tarpaulin manufacturer (Lonas Fieraflex), with a custom product type for specs (weight, light transmission, uses, colours).
- **Olimed** – redesign for a medical and pharmaceutical distributor: WooCommerce catalog with WhatsApp quote requests.
- **OK Impresores** – print shop for offices and businesses, WooCommerce block theme with versioned releases.
- **Mick** – women's footwear e-commerce, WooCommerce block theme with card and Yape payments.
- **[Cassadó](https://cassado.com.pe)** – industrial supplier celebrating 100 years: theme maintenance, product catalog, chatbot and form leads synced to Google Sheets, virtual complaints book, WhatsApp routing, Google Ads / Tag Manager conversion tracking, database deployments and an admin manual.
- **Canelas** – online florist and gift shop.
- **[La Botella](https://labotella.site)** and **[Ledy's](https://ledys.store)** – online stores with product catalogs loaded from spreadsheets with their images, plus admin guides for the owners.

#### Tools

- **Spanish video transcriptor** – local Python CLI using `faster-whisper` and FFmpeg to transcribe videos with timestamps.
- **WordPress admin guide generator** – Python tool that turns a per-client YAML file into a branded PDF manual for managing their site.

## 🕓 Previously

- **Mid 2025 · [Gelly Consulting](https://www.gellyconsulting.com/)**  
  Developed a **Catenary Calculator**, a 3D web application built with **Three.js** for simulating and calculating **railway overhead contact line systems**, including droppers, cantilever geometry and mechanical tensioning. This work was the starting point for OCS.

- **Sep 2020 – Apr 2025 · 4 yrs 8 mos · BRIM Consultant – Brazil**  
  Worked as a **Billing and Revenue Innovation Management (BRIM)** Consultant, implementing SAP-based billing solutions.  
  - Implemented **billing process workflows** using **SAP Convergent Mediation (Mediation Zone)**, with **SAP HANA**, **Oracle SQL Developer** and **Microsoft SQL Server**.  
  - Managed and optimized **large-scale datasets**, applying **clean code principles** for efficient and maintainable systems.  
  - Designed new algorithms and processes that cut **data processing time by 75%**.  
  - Automated **billing item extraction** through **web service integrations**, reducing manual work and errors.  
  - Wrote and maintained **technical documentation** for billing workflows and integrations.

## Skills:

#### Languages:

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)&nbsp;
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white)&nbsp;
![Php](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=PHP&logoColor=white)&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)&nbsp;
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)&nbsp;
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)&nbsp;
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)&nbsp;
![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)&nbsp;
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

#### Web Frameworks & Tools

![React & React Native](https://img.shields.io/badge/React_&_React_Native-61DAFB?style=for-the-badge&logo=React&logoColor=white)&nbsp;
![Spring](https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)&nbsp;
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white)&nbsp;
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flaskn&logoColor=white)&nbsp;
![Express.js](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white)&nbsp;
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=Laravel&logoColor=white)&nbsp;
![Node.js](https://img.shields.io/badge/Node-339933?style=for-the-badge&logo=Node.js&logoColor=white)&nbsp;
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)&nbsp;
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)&nbsp;
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)&nbsp;
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)&nbsp;
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)&nbsp;
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)&nbsp;
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)&nbsp;
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white)&nbsp;
![SmartClient](https://img.shields.io/badge/SmartClient-1F5FA8?style=for-the-badge)&nbsp;
![WebSocket STOMP](https://img.shields.io/badge/WebSocket_STOMP-010101?style=for-the-badge&logo=socketdotio&logoColor=white)&nbsp;

#### Database

![MySQL](https://img.shields.io/badge/mysql-316192?style=for-the-badge&logo=mysql&logoColor=white)&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)&nbsp;
![Redis](https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)&nbsp;
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)&nbsp;
![SAP HANA](https://img.shields.io/badge/SAP_HANA-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)&nbsp;
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge)&nbsp;
![Apache Parquet](https://img.shields.io/badge/Apache_Parquet-50ABF1?style=for-the-badge&logo=apache&logoColor=white)&nbsp;
![Delta Sharing](https://img.shields.io/badge/Delta_Sharing-00ADD4?style=for-the-badge&logo=delta&logoColor=white)&nbsp;

#### Tools and Technologies
![Convergent Mediation](https://img.shields.io/badge/Convergent_Mediation-B366F6?style=for-the-badge)&nbsp;
![Kubernetes](https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)&nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)&nbsp;
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)&nbsp;
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)&nbsp;
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)&nbsp;
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)&nbsp;
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)&nbsp;
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)&nbsp;
![PostMan](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)&nbsp;
![Lens](https://img.shields.io/badge/lens-3D90CE?style=for-the-badge&logo=lens&logoColor=white)&nbsp;
![Microsoft SQL Server](https://img.shields.io/badge/microsoftsqlserver-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)&nbsp;
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)&nbsp;
![Hostinger](https://img.shields.io/badge/Hostinger-673DE6?style=for-the-badge&logo=hostinger&logoColor=white)&nbsp;
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)&nbsp;
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)&nbsp;
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)&nbsp;
![Claude AI](https://img.shields.io/badge/Claude_AI-D97757?style=for-the-badge&logo=claude&logoColor=white)&nbsp;
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)&nbsp;
![HyperFrames](https://img.shields.io/badge/HyperFrames-111111?style=for-the-badge)&nbsp;


#### IDEs
![NeoVim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)&nbsp;
![intellijidea](https://img.shields.io/badge/intellijidea-000000?style=for-the-badge&logo=intellijidea&logoColor=white)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)&nbsp;



## Connect with me:

<p align = "center">

<!--[<img src="https://img.shields.io/badge/kaggle-%2312100E.svg?&style=for-the-badge&logo=kaggle&logoColor=white&color=black" />](https://www.kaggle.com/themlphdstudent)
[<img src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white&color=black" />](https://medium.com/@themlphdstudent)
-->
[<img src ="https://img.shields.io/badge/Digital_Process_IT-%23.svg?&style=for-the-badge&logo=www&logoColor=white%22&color=black">](https://www.digitalprocessit.com/)
[<img src ="https://img.shields.io/badge/Medialítica-%23.svg?&style=for-the-badge&logo=www&logoColor=white%22&color=black">](https://medialitica.pe/)
[<img src="https://img.shields.io/badge/email-%2312100E.svg?&style=for-the-badge&logo=gmail&logoColor=white&color=black" />](mailto:diegopevi05@gmail.com)
[<img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white&color=black" />](https://twitter.com/diego10azul) 
[<img src="https://img.shields.io/badge/linkedin-%2312100E.svg?&style=for-the-badge&logo=linkedin&logoColor=white&color=black" />](https://www.linkedin.com/in/diegopenavicente/)
[<img src="https://img.shields.io/badge/instagram-%2312100E.svg?&style=for-the-badge&logo=instagram&logoColor=white&color=black" />](https://www.instagram.com/diegopea05/)
</p>
<a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api?username=DiegoPevi05&show_icons=true&include_all_commits=true&theme=buefy&hide_border=true" alt="Diego's github stats" /></a> | <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiegoPevi05&layout=compact&theme=buefy&hide_border=true" /></a>
<!-- 
----
[<img src="https://github-profile-trophy.vercel.app/?username=DiegoPevi05&row=2&column=3" />](https://github.com/ryo-ma/github-profile-trophy)
[<img src="https://github-readme-stats.vercel.app/api?username=DiegoPevi05&theme=algolia&count_private=true&include_all_commits=true&show_icons=true" />](https://github.com/anuraghazra/github-readme-stats)
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=DiegoPevi05&theme=dark)](https://github.com/DenverCoder1/github-readme-streak-stats)
[![Durgesh's Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=themlphdstudent&theme=algolia&hide=Jupyter&layout=compact&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)
 -->

<!--
**DiegoPevi05** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
