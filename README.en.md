<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <img src="assets/header-light.svg" width="840" alt="Terminal: whoami → Tiago Alcântara, Software Engineer, São Paulo. Tracks: software, devops-cloud, data, ai. Motto: make systems visible.">
  </picture>
</p>

<p align="center">
  <a href="README.md">PT-BR</a> · <b>EN</b>
  &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/tiagoalcan">LinkedIn</a> ·
  <a href="mailto:tiago.gomesalcan@gmail.com">tiago.gomesalcan@gmail.com</a>
</p>

I'm a software engineer at THCS in São Paulo. For over three years I've been building and running production software on a payment authorization system that handles **more than 1 million transactions a day**.

One idea ties my work together: **make systems visible**. Dashboards a client can read without knowing the query, documentation someone else can follow on their own, tests that become the quality bar.

I'm looking for roles as a **Software Engineer**, **DevOps / Cloud Architect**, **Data Engineer** or **AI Engineer**.

> Every line below is a command. Click to see its output.

<details open>
<summary><code>$ cat experience.log</code></summary>

<br>

**THCS Desenvolvimento de Software** · São Paulo, Brazil

| Period | Role | What I delivered |
|---|---|---|
| Mar 2025 → now | Software Engineer | End-to-end monitoring with Prometheus, Grafana and Alertmanager for a system handling 1M+ transactions a day. REST integrations with authentication flows. Internal tools in TypeScript, Java (Spring Boot) and Vue. Production support and change management with large financial institutions. |
| Mar 2023 → Mar 2025 | Intern | Standardized, version-controlled deployments with Git and DockerHub. Technical documentation for systems and APIs. API testing with JMeter and Postman. |

</details>

<details>
<summary><code>$ ls projects/</code></summary>

<br>

| Project | Outcome in one line | Track |
|---|---|---|
| **Observability for a payment authorizer** | From the metric in Java code to the Grafana dashboard, for a system with 1M+ transactions a day | DevOps · Data |
| **MoziCash** | Personal finance app that answers "how much can I still spend this month?", with an AI agent. Inspired by my capstone project. React, FastAPI, Supabase | Software · AI |
| **AI skill for technical documentation** | The company's manual standard encoded as a skill: anyone can generate a document in the approved format | AI |
| **[AWS infrastructure with Terraform](https://github.com/TiagoAlcan/fase1_devops_fiap_postech)** | An environment described as code, with an architecture document. Coursework for my DevOps and Cloud postgraduate program | DevOps |
| **Business credit risk with graphs** | Undergraduate research ranked in the top 30: each company's supply chain as a weight in the model | Data · AI |
| **[projeto_restart](https://github.com/TiagoAlcan/projeto_restart)** | From API consumption and scraping to an interactive dashboard | Data |

</details>

<details>
<summary><code>$ cat stack.yaml</code></summary>

<br>

| Track | Used at work | Study and projects |
|---|---|---|
| **Software** | Java, Spring Boot, TypeScript, JavaScript, Vue, SQL, REST | React, Python, FastAPI |
| **DevOps and Cloud** | Linux, Shell, Docker, Docker Compose, TeamCity, AWS (EC2, S3, MSK, CloudWatch), Proxmox | Kubernetes, Terraform, GitHub Actions |
| **Observability** | Prometheus, PromQL, Alertmanager, Grafana | OpenTelemetry |
| **Data** | SQL, Kafka, RabbitMQ | Pandas, NumPy, Scikit-learn, PySpark, graph databases |
| **AI** | Skills and automations with Claude | Agents, LLM integration in applications |
| **Quality** | JMeter, Postman, Insomnia, BDD | JUnit |

</details>

<details>
<summary><code>$ tail -f studies.log</code></summary>

<br>

- **Postgraduate program in DevOps and Cloud Architecture** (FIAP PosTech) · in progress. Kubernetes, IaC with Terraform, CI/CD and GitOps, DevSecOps, observability, SRE, FinOps and AIOps.
- **Data Science bootcamp** (TripleTen) · Dec 2025 → Dec 2026. Data analysis, machine learning, deep learning and advanced SQL. [Coursework here](https://github.com/TiagoAlcan/Triple-Ten-Data-Science).
- **B.Sc. in Information Systems** (FIAP) · 2022 → 2025.

</details>

<details>
<summary><code>$ man curiosity</code></summary>

<br>

Things running a production system taught me to see differently:

- **A million a day sounds like a lot, but it's about 12 per second.** The average is calm. Peaks are what take a system down, which is why a good dashboard shows rate over a time window instead of a daily total.
- **99.9% availability is still almost 9 hours of downtime a year.** Each extra nine divides that by ten: 99.99% is 52 minutes.
- **Averages hide who is hurting.** At 1 million requests a day, p99 means 10,000 requests every day were slower than that number. There's a person behind each one.
- **A restart is not a recovery.** After the machine comes back, services have to start in the right order. That's what got me writing scripts so applications recover on their own.
- **If a dashboard needs explaining, it's a report.** A good one answers a question in five seconds.

</details>

<details>
<summary><code>$ ./contact.sh</code></summary>

<br>

- Email: [tiago.gomesalcan@gmail.com](mailto:tiago.gomesalcan@gmail.com)
- LinkedIn: [linkedin.com/in/tiagoalcan](https://www.linkedin.com/in/tiagoalcan)
- Languages: Portuguese (native), English (advanced), Spanish (intermediate)

</details>

<br>

```console
$ uptime
in production since March 2023 · São Paulo, Brazil
```
