# Hi there, I'm Moosa Raza 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/moosa-raza-baig-mirza-b22b399a/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:moosaraza24@gmail.com)
[![Location](https://img.shields.io/badge/Location-Abu%20Dhabi%2C%20UAE-green?style=for-the-badge&logo=google-maps)](https://www.google.com/maps/place/Abu+Dhabi)

</div>

## 🚀 About Me

**Software Engineer** at **Finance House PJSC** | Backend & Full Stack .NET Developer

🏦 Building enterprise-grade **banking systems** and **custom CRM platforms** in Abu Dhabi, UAE  
🏗️ Specialized in **Clean Architecture**, **CQRS (MediatR)**, and **.NET 10**  
🔐 Passionate about **secure**, **scalable**, and **compliant** financial systems  
🤖 Productive user of **GitHub Copilot** and **Cursor** for AI-assisted development  
🛠️ Strong focus on **DevOps**, **CI/CD**, **Docker**, and **Kubernetes (AKS)**

---

## 💼 Professional Experience

### 🏢 Finance House PJSC, Abu Dhabi 🇦🇪
**Software Engineer** | *June 2024 – Present*

- 🏦 Architected enterprise CRM modules (Leads, Customer360, Cards, Loan Applications) on **.NET 10 Clean Architecture + CQRS (MediatR)** serving **100K+ customers**
- 🎯 Built **RaffleDraw** — weighted-probability draw engine (1 ticket per AED 10 spent) with eligibility rules, claim workflow, audit trail; deployed via **Docker → Azure DevOps → AKS**
- 🔄 Migrated **FHGSPApprovalSystem** from SharePoint Online workflows to **.NET 10 REST API** — 12 approval workflows, up to 15 sequential approver levels
- 🔗 Integrated **AECB** and **CRIF** credit bureau systems via **WCF + XSLT** for real-time automated credit decisioning
- ⚙️ Engineered **SIP (Systematic Investment Plan)** automation for recurring financial transactions
- 🔒 Implemented **RBAC/RAC** security models with authorization behaviors in the CQRS pipeline; **Azure AD JWT** authentication
- 📊 Maintained **Decision Support System (DSS)** for credit and lending rule management

### 💻 Centra Hub Technologies Pvt. Ltd, India
**Full Stack Software Developer** | *September 2020 – June 2024*

- 👥 Led a team of **10–15 developers**, managing requirements, code reviews, and delivery
- Built scalable CRM solutions using **C#, .NET Core, ASP.NET MVC, React**
- Designed optimized **T-SQL** stored procedures and reports for high-performance data access
- Delivered end-to-end solutions across the full SDLC

### 🖥️ Focus Softnet Pvt. Ltd, India
**Technical Support Executive** | *May 2018 – June 2020*

- Customized **ERP workflows** and developed SQL-based custom reports
- Performed functional testing, UAT support, and production issue resolution

---

## 🛠️ Tech Stack

### Backend
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![MediatR](https://img.shields.io/badge/MediatR_CQRS-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Hangfire](https://img.shields.io/badge/Hangfire-00A4EF?style=for-the-badge)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Database
![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

### DevOps & Tools
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes_AKS-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=github&logoColor=white)

---

## 🔥 Featured Projects

### 🎯 RaffleDraw — Weighted Draw Engine
**Finance House PJSC | Promotional Campaign System**

- Weighted-probability winner selection — each participant's win chance scales proportionally with ticket count
- Issues **1 raffle ticket per AED 10** spent; entries generated and persisted per participant per campaign
- Enforced eligibility rules: cooling-off periods between wins, related-party exclusions (employees, board, family)
- Full claim workflow: notify → claim → expiry → promote next eligible ticket, with complete audit trail
- Deployed via **Docker → Azure DevOps CI/CD → AKS** with **≥80% test coverage**, SonarQube quality gates
- **Tech:** .NET 10, C#, MediatR (CQRS), EF Core, Hangfire, MS SQL Server, Docker, AKS, SonarQube

*Note: Internal banking project (cannot be shared publicly)*

---

### 🔄 ApprovalSystem — SharePoint Workflow Migration
**Finance House PJSC | Workflow Modernization**

- Migrated **12 approval workflows** from SharePoint Online native workflows to a custom **.NET 10 REST API**
- Replaced brittle no-code flows with Clean Architecture + CQRS (MediatR) — BRD, Project Charter, EPMO CR, GL/RF Exception, Collection Recovery, CorpAC Opening
- **17 orchestration services**, 50+ optimized query handlers, up to **15 sequential approver levels**
- Configurable concurrence chains, automated email notifications on every stage transition
- **Tech:** .NET 10, C#, MediatR (CQRS), EF Core, MS SQL Server, Serilog, SonarQube, Swagger

*Note: Internal banking project (cannot be shared publicly)*

---

### 🏦 Finance House CRM — Enterprise Banking Platform
**Finance House PJSC | Core Banking CRM**

- Full-stack CRM: **.NET 10 Clean Architecture** backend + **React 18/Vite** frontend
- Modules: Leads, Customer 360, Cards, Loan Applications — serving **100K+ customer records**
- **AG Grid Enterprise** server-side grids, **TanStack React Query**, **Azure AD MSAL.js** authentication
- RBAC authorization behaviors in CQRS pipeline; Hangfire for async document processing
- **Tech:** .NET 10, C#, React 18, Vite, EF Core, Hangfire, AG Grid Enterprise, Azure AD, Docker, Nginx

*Note: Internal banking project (cannot be shared publicly)*

---

### 📡 DSS Bureau — Credit Bureau & Decision Support System
**Finance House PJSC | Credit Infrastructure**

- **WCF service** exposing 5 AECB bureau enquiry operations (New Application, Monitor, Additional, Update, Subject)
- **CRIF DSS** integration via XSLT transformations for eligibility checks and application allocation
- ASP.NET WebForms admin portal: dashboard analytics, portfolio scrubbing, billing, audit logs, PDF reports
- **Tech:** C#, .NET Framework, WCF, ASP.NET WebForms, MS SQL Server, T-SQL, XSLT

*Note: Internal banking project (cannot be shared publicly)*

---

## 🎓 Education

**Bachelor of Science in Computer Science**
Osmania University, India

---

## 🌍 Languages

- 🇬🇧 **English** (Professional)
- 🇮🇳 **Hindi** (Native)
- 🇮🇳 **Urdu** (Native)

---

## 📫 Get In Touch

- 📧 Email: [moosaraza24@gmail.com](mailto:moosaraza24@gmail.com)
- 🌐 LinkedIn: [Connect with me](https://www.linkedin.com/in/moosa-raza-baig-mirza-b22b399a/)
- 📍 Location: Abu Dhabi, UAE 🇦🇪

---

<div align="center">

### 💼 Software Engineer at Finance House PJSC, Abu Dhabi 🇦🇪

**"Building secure, scalable, and compliant banking systems with Clean Architecture & CQRS"**

</div>
