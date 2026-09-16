<div align="center">

# Hi, I'm Srihas Inaganti 👋

**CS + Applied Math @ University of Maryland**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/srihas-inaganti)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:srihas.inaganti@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/srihasInaganti)

</div>

---

### 🧭 About Me

- 🎓 B.S. Computer Science & Applied Mathematics, University of Maryland — *Expected May 2028* (Dean's List, GPA 3.79)
- 🛠️ Currently: Software Engineer at **TestuGo** (VIP)
- 🤝 Incoming Fall 2026: Software Engineer at **Hack4Impact-UMD**

---

### 🧱 Tech Stack

**Languages**

![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frameworks & Libraries**

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/-Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Data & Tools**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Bitbucket](https://img.shields.io/badge/-Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white)

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🖼️ Serverless Image Processor**

[![Live](https://img.shields.io/badge/Live-000000?style=flat-square&logo=githubpages&logoColor=white)](https://srihasinaganti.github.io/job-platform/)
[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/srihasInaganti/job-platform)

`AWS · GitHub Actions · Terraform`

Event-driven pipeline decoupling ingestion from compute via SQS.

- ⚡ **350+ req/sec** sustained, 20ms p50 / 110ms p99
- 🔁 Recovered **100/100** jobs from injected SIGKILL crashes, zero stuck/duplicate completions
- 🔒 Blocked a verified zombie-worker race with a DynamoDB fencing token

</td>
<td width="50%" valign="top">

**🗳️ Raft-KV**

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/srihasInaganti/raft-kv)

`Go`

A from-scratch Raft consensus implementation with a linearizable KV store.

- ✅ **107k+ commands** validated across 6k chaos iterations, zero safety violations
- ⏱️ **556ms** median / 814ms p99 leader failover across 100 live kills (5-node cluster)
- 📖 **7.6k reads/sec** at 1.0ms latency via ReadIndex, bypassing Raft log disk commits

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧠 Mini-vLLM**

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/srihasInaganti/mini-vllm)

`Python · PyTorch · torch.compile`

LLM inference engine implementing PagedAttention and continuous batching.

- 🎯 Reaches **~20%** of vLLM's throughput
- 📈 **10.8x** concurrency-32 throughput boost (106 → 1,143 tok/s)
- 🔌 OpenAI-compatible REST API for drop-in client integration

</td>
<td width="50%" valign="top">

**⚡ OCR Fixture Code Detector**

[![Live](https://img.shields.io/badge/Live-000000?style=flat-square&logo=vercel&logoColor=white)](https://ocr-fixture-code-detector.vercel.app)
[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/srihasInaganti/ocr-fixture-code-detector)

`Python · PyMuPDF · React · Document AI`

Automates manual fixture-code review from electrical plans.

- 🎯 **88%** detection accuracy across 23 real-world electrical plans
- 🔍 Custom regex over raw OCR tokens to isolate true fixture codes from circuit numbers
- 🖱️ Interactive bounding-box canvas with CSV export

</td>
</tr>
</table>

---

### 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=srihasInaganti&theme=tokyonight&hide_border=true" width="60%" />

</div>

---

<div align="center">

📫 **Let's connect:** [srihas.inaganti@gmail.com](mailto:srihas.inaganti@gmail.com) · [LinkedIn](https://linkedin.com/in/srihas-inaganti)

</div>
