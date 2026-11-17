<img src="assets/header.svg" width="100%" alt="Pablo Vinicius, Full Stack Developer" />

<div align="center">

<a href="https://www.linkedin.com/in/pablo-viniciuss/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:pablovinicius.pv939@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

## 👨‍💻 About me

I design and build a company ERP from scratch, as the technical lead of the project.
I work as a full stack developer, from the database to the screen, with Python, FastAPI,
JavaScript, SQL Server and AWS.

The ERP replaces a legacy Delphi system and will cover the whole company, from finance to sales.
I designed its modular architecture, review and approve every change that goes into the codebase,
and build features end to end. The finance module is already in production.

Before writing code, I worked in IT support and with TOTVS Protheus, so I learned ERPs from the
user's side first. In financial systems, one wrong cent becomes a support ticket.

## 🧩 What I build

| | Area | Stack |
|---|---|---|
| 🏗️ | **ERP architecture**: modular monolith with clear module boundaries, shared platform (login with 2FA, per-screen permissions, audit trail) and a shared design system | FastAPI · Jinja2 · Pydantic · SQLAlchemy · SQL Server · vanilla JS |
| 🔌 | **Banking integrations**: CNAB 240 payment files (Pix, TED, boleto) over SFTP, bank statement API with OAuth 2.0 + mTLS, bank reconciliation engine | requests · Paramiko · cryptography |
| 🧾 | **Brazilian e-invoicing**: NFS-e issuing through an API with idempotent references and automatic fallback to the national standard, NF-e received from SEFAZ, boleto PDF with barcode | PyNFe · signxml · ReportLab · fpdf2 · python-barcode |
| 📊 | **BI dashboards and data APIs**: reporting dashboards that replaced manual spreadsheet updates | pandas · FastAPI · SQL Server · Chart.js · Netlify |
| ☁️ | **Deploy and quality**: 36% faster server boot, 21% shorter deploy pipeline, 84% test coverage, lint and dependency audit blocking CI | Docker · AWS ECS · CloudWatch · GitHub Actions · pytest · Ruff |

## 📌 Public projects

- **[hermes-alexa](https://github.com/pablo-afterlife/hermes-alexa)**: Alexa as a native channel for [Hermes Agent](https://github.com/NousResearch/hermes-agent). Talk to an AI agent through an Echo device without replacing Alexa. Python.

## 🛠️ Tech stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=py,js,html,css,bash&theme=dark" alt="Python, JavaScript, HTML, CSS, Bash" />

**Backend & data**

<img src="https://skillicons.dev/icons?i=fastapi&theme=dark" alt="FastAPI" />
<br/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square" alt="SQL Server" />
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic" />
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
<img src="https://img.shields.io/badge/Jinja-B41717?style=flat-square&logo=jinja&logoColor=white" alt="Jinja" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />

**Cloud, DevOps & quality**

<img src="https://skillicons.dev/icons?i=docker,aws,githubactions,linux,git,github&theme=dark" alt="Docker, AWS, GitHub Actions, Linux, Git, GitHub" />
<br/>
<img src="https://img.shields.io/badge/Amazon_ECS-FF9900?style=flat-square" alt="Amazon ECS" />
<img src="https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square" alt="CloudWatch" />
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
<img src="https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black" alt="Ruff" />

**Learning:** React · TypeScript

</div>

## 🐍 Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pablo-afterlife/pablo-afterlife/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/pablo-afterlife/pablo-afterlife/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/pablo-afterlife/pablo-afterlife/output/github-snake.svg" width="100%" />
</picture>

<div align="center">
  <i>"Simple code that works beats clever code that breaks."</i>
</div>

<img src="assets/footer.svg" width="100%" alt="" />
