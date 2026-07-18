<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:0f766e&height=170&section=header&text=Tr%E1%BA%A7n%20Nh%E1%BA%A5t%20Long&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineering%20Student%20%C2%B7%20FPT%20University%20%C2%B7%20Backend%20%C2%B7%20QA&descAlignY=58&descSize=15" width="100%"/>

[![GitHub followers](https://img.shields.io/github/followers/TNL293107?label=Follow&style=for-the-badge&color=0f766e&labelColor=1e293b)](https://github.com/TNL293107)
[![Profile views](https://komarev.com/ghpvc/?username=TNL293107&style=for-the-badge&color=0f766e&label=PROFILE+VIEWS&labelColor=1e293b)](https://github.com/TNL293107)

</div>

### About Me

Software Engineering student at **FPT University, Đà Nẵng**. Most of my personal project work is backend — schema design, DAO/service layers, and the parts of an app that are less visible but have to be right. On my capstone team (5 people, building **CVerify**), I ended up owning deployment and infrastructure — migrating the stack between cloud providers, wiring up CI/CD, and keeping production actually running — on top of testing and AI-audit documentation.

- Software Engineering student, FPT University Đà Nẵng
- Backend development — C#/.NET and Java (Servlet/JSP, Maven)
- On the CVerify capstone team (SWP391, SE20A02): deployment/DevOps (GCP migration, CI/CD, Docker, SSL, backups), plus testing, AI-audit documentation, and occasional feature/bugfix work across the Next.js and ASP.NET Core layers
- Comfortable picking up a stack I didn't design when the team needs it — most of my CVerify commits are outside my "home" language (C#/Java), in Docker configs, GitHub Actions, and Next.js

---

### Tech Stack

**Languages & Core**

![C#](https://img.shields.io/badge/C%23-1e293b?style=for-the-badge&logo=csharp&logoColor=0f766e)
![Java](https://img.shields.io/badge/Java-1e293b?style=for-the-badge&logo=openjdk&logoColor=0f766e)
![JavaScript](https://img.shields.io/badge/JavaScript-1e293b?style=for-the-badge&logo=javascript&logoColor=0f766e)
![SQL Server](https://img.shields.io/badge/SQL_Server-1e293b?style=for-the-badge&logo=microsoftsqlserver&logoColor=0f766e)

**Backend & Tooling**

![.NET](https://img.shields.io/badge/.NET-1e293b?style=for-the-badge&logo=dotnet&logoColor=0f766e)
![Servlet/JSP](https://img.shields.io/badge/Servlet%2FJSP-1e293b?style=for-the-badge&logo=openjdk&logoColor=0f766e)
![Maven](https://img.shields.io/badge/Maven-1e293b?style=for-the-badge&logo=apachemaven&logoColor=0f766e)
![Docker](https://img.shields.io/badge/Docker-1e293b?style=for-the-badge&logo=docker&logoColor=0f766e)
![Git](https://img.shields.io/badge/Git-1e293b?style=for-the-badge&logo=git&logoColor=0f766e)

**DevOps & Infra (hands-on, via CVerify)**

![Docker](https://img.shields.io/badge/Docker_Compose-1e293b?style=for-the-badge&logo=docker&logoColor=0f766e)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1e293b?style=for-the-badge&logo=githubactions&logoColor=0f766e)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-1e293b?style=for-the-badge&logo=googlecloud&logoColor=0f766e)

Migrated CVerify's production deployment from AWS EC2 to GCP Compute Engine, set up subdomain routing, SSL renewal automation, self-hosted MinIO object storage, and daily backups.

**Working with, on the CVerify team**

PostgreSQL · Redis · Next.js/React · FastAPI · Anthropic Claude API — I ship fixes and small features against this stack (auth cookie scoping, email provider config, a JD-matching pipeline feature, a landing page update) as part of my testing and deployment work, without owning the overall architecture.

---

### Featured Projects

**[CVerify](https://github.com/fptu-se-su26/swp391-su26-ai-audit-project-swp391_se20a02_group-05)** — Developer source-code verification platform *(team capstone, SWP391)*
`ASP.NET Core` `Next.js/React` `FastAPI` `PostgreSQL` `Redis` `Docker`

A monorepo built by a 5-person team: a Next.js/React frontend, an ASP.NET Core (Clean Architecture) backend, and a Python/FastAPI AI microservice that analyzes candidate repositories for contribution patterns and code originality. Deployed at a live domain, containerized with a hardened Docker Compose setup (network segmentation, non-root containers).

*My role:* the team's documented split lists me under testing, AI-audit documentation, and feature support — in practice that's grown to include most of the deployment work: migrating production from AWS EC2 to GCP, setting up CI/CD and SSL automation, hardening the Docker Compose setup, and fixing cross-cutting bugs (OAuth cookie scoping, reverse-proxy header trust, email provider config) as they surfaced. I've also implemented a slice of the JD-matching pipeline and kept the AI-audit documentation trail up to date.

**[DWatch](https://github.com/TNL293107/DWatch)** — E-commerce watch store
`Java` `Servlet/JSP` `Maven` `Microsoft SQL Server` `Docker`

A solo full-stack build covering the full purchase flow: catalog with search/filtering, cart and checkout (COD or VietQR QR-code payment), guest order lookup, product comparison, wishlist, and an admin panel — plus email-based password reset and order confirmation.

*Why it matters:* end-to-end ownership — DB schema, DAO layer, servlet routing, a real payment integration, and a working Docker deployment, done alone.

<a href="https://github.com/TNL293107/DWatch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=TNL293107&repo=DWatch&bg_color=1e293b&title_color=0f766e&text_color=e2e8f0&border_color=334155&icon_color=0f766e" /></a>

**[FU-Autokit](https://github.com/TNL293107/FU-Autokit)** — Browser toolkit for FPT University students
`JavaScript` `HTML` `CSS`

A Chromium extension that automates recurring tasks across FPT University's web systems (auto-login, GPA calculation, form autofill, and more). Built as a compiled toolkit — individual features are sourced from and credited to their original authors in the README, with the extension architecture, integration, and ongoing maintenance (260+ commits) as my contribution.

*Why it matters:* real day-to-day usage by other students, and practical experience integrating and maintaining third-party scripts inside a single coherent extension.

<a href="https://github.com/TNL293107/FU-Autokit"><img src="https://github-readme-stats.vercel.app/api/pin/?username=TNL293107&repo=FU-Autokit&bg_color=1e293b&title_color=0f766e&text_color=e2e8f0&border_color=334155&icon_color=0f766e" /></a>

---

### GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=TNL293107&show_icons=true&bg_color=1e293b&title_color=0f766e&text_color=e2e8f0&border_color=334155&icon_color=0f766e&hide_border=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=TNL293107&background=1e293b&ring=0f766e&fire=0f766e&currStreakLabel=e2e8f0&sideLabels=e2e8f0&currStreakNum=e2e8f0&sideNums=e2e8f0&dates=94a3b8&border=334155&hide_border=true" height="165"/>

</div>

---

### Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-1e293b?style=for-the-badge&logo=github&logoColor=0f766e)](https://github.com/TNL293107)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1e293b?style=for-the-badge&logo=linkedin&logoColor=0f766e)](https://www.linkedin.com/in/trần-nhất-long-a78122325/)
[![Facebook](https://img.shields.io/badge/Facebook-1e293b?style=for-the-badge&logo=facebook&logoColor=0f766e)](https://www.facebook.com/long293107)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,100:1e293b&height=100&section=footer" width="100%"/>

</div>
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:0f766e&height=170&section=header&text=Tr%E1%BA%A7n%20Nh%E1%BA%A5t%20Long&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineering%20Student%20%C2%B7%20FPT%20University%20%C2%B7%20Backend%20%26%20QA&descAlignY=58&descSize=15" width="100%"/>

[![GitHub followers](https://img.shields.io/github/followers/TNL293107?label=Follow&style=for-the-badge&color=0f766e&labelColor=1e293b)](https://github.com/TNL293107)
[![Profile views](https://komarev.com/ghpvc/?username=TNL293107&style=for-the-badge&color=0f766e&label=PROFILE+VIEWS&labelColor=1e293b)](https://github.com/TNL293107)

</div>

### About Me

Software Engineering student at **FPT University, Đà Nẵng**. Most of my personal project work is backend — schema design, DAO/service layers, and the parts of an app that are less visible but have to be right. On my capstone team (5 people, building **CVerify**), I ended up owning deployment and infrastructure — migrating the stack between cloud providers, wiring up CI/CD, and keeping production actually running — on top of testing and AI-audit documentation.

- Software Engineering student, FPT University Đà Nẵng
- Backend development — C#/.NET and Java (Servlet/JSP, Maven)
- On the CVerify capstone team (SWP391, SE20A02): deployment/DevOps (GCP migration, CI/CD, Docker, SSL, backups), plus testing, AI-audit documentation, and occasional feature/bugfix work across the Next.js and ASP.NET Core layers
- Comfortable picking up a stack I didn't design when the team needs it — most of my CVerify commits are outside my "home" language (C#/Java), in Docker configs, GitHub Actions, and Next.js

---

### Tech Stack

**Languages & Core**

![C#](https://img.shields.io/badge/C%23-1e293b?style=for-the-badge&logo=csharp&logoColor=0f766e)
![Java](https://img.shields.io/badge/Java-1e293b?style=for-the-badge&logo=openjdk&logoColor=0f766e)
![JavaScript](https://img.shields.io/badge/JavaScript-1e293b?style=for-the-badge&logo=javascript&logoColor=0f766e)
![SQL Server](https://img.shields.io/badge/SQL_Server-1e293b?style=for-the-badge&logo=microsoftsqlserver&logoColor=0f766e)

**Backend & Tooling**

![.NET](https://img.shields.io/badge/.NET-1e293b?style=for-the-badge&logo=dotnet&logoColor=0f766e)
![Servlet/JSP](https://img.shields.io/badge/Servlet%2FJSP-1e293b?style=for-the-badge&logo=openjdk&logoColor=0f766e)
![Maven](https://img.shields.io/badge/Maven-1e293b?style=for-the-badge&logo=apachemaven&logoColor=0f766e)
![Docker](https://img.shields.io/badge/Docker-1e293b?style=for-the-badge&logo=docker&logoColor=0f766e)
![Git](https://img.shields.io/badge/Git-1e293b?style=for-the-badge&logo=git&logoColor=0f766e)

**DevOps & Infra (hands-on, via CVerify)**

![Docker](https://img.shields.io/badge/Docker_Compose-1e293b?style=for-the-badge&logo=docker&logoColor=0f766e)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1e293b?style=for-the-badge&logo=githubactions&logoColor=0f766e)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-1e293b?style=for-the-badge&logo=googlecloud&logoColor=0f766e)

Migrated CVerify's production deployment from AWS EC2 to GCP Compute Engine, set up subdomain routing, SSL renewal automation, self-hosted MinIO object storage, and daily backups.

**Working with, on the CVerify team**

PostgreSQL · Redis · Next.js/React · FastAPI · Anthropic Claude API — I ship fixes and small features against this stack (auth cookie scoping, email provider config, a JD-matching pipeline feature, a landing page update) as part of my testing and deployment work, without owning the overall architecture.

---

### Featured Projects

**[CVerify](https://github.com/fptu-se-su26/swp391-su26-ai-audit-project-swp391_se20a02_group-05)** — Developer source-code verification platform *(team capstone, SWP391)*
`ASP.NET Core` `Next.js/React` `FastAPI` `PostgreSQL` `Redis` `Docker`

A monorepo built by a 5-person team: a Next.js/React frontend, an ASP.NET Core (Clean Architecture) backend, and a Python/FastAPI AI microservice that analyzes candidate repositories for contribution patterns and code originality. Deployed at a live domain, containerized with a hardened Docker Compose setup (network segmentation, non-root containers).

*My role:* the team's documented split lists me under testing, AI-audit documentation, and feature support — in practice that's grown to include most of the deployment work: migrating production from AWS EC2 to GCP, setting up CI/CD and SSL automation, hardening the Docker Compose setup, and fixing cross-cutting bugs (OAuth cookie scoping, reverse-proxy header trust, email provider config) as they surfaced. I've also implemented a slice of the JD-matching pipeline and kept the AI-audit documentation trail up to date.

**[DWatch](https://github.com/TNL293107/DWatch)** — E-commerce watch store
`Java` `Servlet/JSP` `Maven` `Microsoft SQL Server` `Docker`

A solo full-stack build covering the full purchase flow: catalog with search/filtering, cart and checkout (COD or VietQR QR-code payment), guest order lookup, product comparison, wishlist, and an admin panel — plus email-based password reset and order confirmation.

*Why it matters:* end-to-end ownership — DB schema, DAO layer, servlet routing, a real payment integration, and a working Docker deployment, done alone.

<a href="https://github.com/TNL293107/DWatch"><img src="https://github-readme-stats.vercel.app/api/pin/?username=TNL293107&repo=DWatch&bg_color=1e293b&title_color=0f766e&text_color=e2e8f0&border_color=334155&icon_color=0f766e" /></a>

**[FU-Autokit](https://github.com/TNL293107/FU-Autokit)** — Browser toolkit for FPT University students
`JavaScript` `HTML` `CSS`

A Chromium extension that automates recurring tasks across FPT University's web systems (auto-login, GPA calculation, form autofill, and more). Built as a compiled toolkit — individual features are sourced from and credited to their original authors in the README, with the extension architecture, integration, and ongoing maintenance (260+ commits) as my contribution.

*Why it matters:* real day-to-day usage by other students, and practical experience integrating and maintaining third-party scripts inside a single coherent extension.

<a href="https://github.com/TNL293107/FU-Autokit"><img src="https://github-readme-stats.vercel.app/api/pin/?username=TNL293107&repo=FU-Autokit&bg_color=1e293b&title_color=0f766e&text_color=e2e8f0&border_color=334155&icon_color=0f766e" /></a>

---

### GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=TNL293107&show_icons=true&bg_color=1e293b&title_color=0f766e&text_color=e2e8f0&border_color=334155&icon_color=0f766e&hide_border=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=TNL293107&background=1e293b&ring=0f766e&fire=0f766e&currStreakLabel=e2e8f0&sideLabels=e2e8f0&currStreakNum=e2e8f0&sideNums=e2e8f0&dates=94a3b8&border=334155&hide_border=true" height="165"/>

</div>

---

### Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-1e293b?style=for-the-badge&logo=github&logoColor=0f766e)](https://github.com/TNL293107)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1e293b?style=for-the-badge&logo=linkedin&logoColor=0f766e)](https://www.linkedin.com/in/trần-nhất-long-a78122325/)
[![Facebook](https://img.shields.io/badge/Facebook-1e293b?style=for-the-badge&logo=facebook&logoColor=0f766e)](https://www.facebook.com/long293107)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f766e,100:1e293b&height=100&section=footer" width="100%"/>

</div>
