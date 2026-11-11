<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <img src="assets/header-light.svg" width="840" alt="Terminal: whoami → Tiago Alcântara, Software Engineer, São Paulo. Trilhas: software, devops-cloud, data, ai. Lema: make systems visible.">
  </picture>
</p>

<p align="center">
  <b>PT-BR</b> · <a href="README.en.md">EN</a>
  &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/tiagoalcan">LinkedIn</a> ·
  <a href="mailto:tiago.gomesalcan@gmail.com">tiago.gomesalcan@gmail.com</a>
</p>

Sou engenheiro de software na THCS, em São Paulo. Há mais de três anos construo e opero software em produção em um sistema de autorização de pagamentos que processa **mais de 1 milhão de transações por dia**.

O que liga as minhas entregas é uma ideia simples: **tornar sistemas visíveis**. Painéis que o cliente entende sem ler a consulta, documentação que outra pessoa consegue executar sozinha, testes que viram parâmetro de qualidade.

Procuro oportunidades como **Software Engineer**, **DevOps / Cloud Architect**, **Data Engineer** ou **AI Engineer**.

> Cada linha abaixo é um comando. Clique para ver a saída.

<details open>
<summary><code>$ cat experiencia.log</code></summary>

<br>

**THCS Desenvolvimento de Software** · São Paulo

| Período | Cargo | O que entreguei |
|---|---|---|
| mar/2025 → hoje | Software Engineer | Monitoramento de ponta a ponta com Prometheus, Grafana e Alertmanager em um sistema com 1M+ transações/dia. Integrações REST com autenticação. Ferramentas internas em TypeScript, Java (Spring Boot) e Vue. Suporte a produção e condução de mudanças junto a grandes instituições financeiras. |
| mar/2023 → mar/2025 | Estagiário | Deploys padronizados e versionados com Git e DockerHub. Documentação técnica de sistemas e APIs. Testes de API com JMeter e Postman. |

</details>

<details>
<summary><code>$ ls projetos/</code></summary>

<br>

| Projeto | Resultado em uma linha | Trilha |
|---|---|---|
| **Observabilidade de um autorizador de pagamentos** | Da métrica no código Java ao painel no Grafana, para um sistema com 1M+ transações/dia | DevOps · Data |
| **MoziCash** | App de finanças pessoais que responde "quanto ainda posso gastar este mês?", com agente de IA. Inspirado no meu TCC. React, FastAPI, Supabase | Software · AI |
| **Skill de IA para documentação técnica** | O padrão de manuais da empresa codificado em uma skill: qualquer pessoa gera o documento no formato aprovado | AI |
| **[Infraestrutura AWS com Terraform](https://github.com/TiagoAlcan/fase1_devops_fiap_postech)** | Ambiente descrito em código, com documento de arquitetura. Entrega da pós em DevOps e Cloud | DevOps |
| **Risco de crédito PJ com grafos** | Iniciação científica entre os 30 melhores: a cadeia de suprimentos de cada empresa como peso no modelo | Data · AI |
| **[projeto_restart](https://github.com/TiagoAlcan/projeto_restart)** | Do consumo de API e scraping até o dashboard interativo | Data |

</details>

<details>
<summary><code>$ cat stack.yaml</code></summary>

<br>

| Trilha | Uso no trabalho | Estudo e projetos |
|---|---|---|
| **Software** | Java, Spring Boot, TypeScript, JavaScript, Vue, SQL, REST | React, Python, FastAPI |
| **DevOps e Cloud** | Linux, Shell, Docker, Docker Compose, TeamCity, AWS (EC2, S3, MSK, CloudWatch), Proxmox | Kubernetes, Terraform, GitHub Actions |
| **Observabilidade** | Prometheus, PromQL, Alertmanager, Grafana | OpenTelemetry |
| **Data** | SQL, Kafka, RabbitMQ | Pandas, NumPy, Scikit-learn, PySpark, bancos de grafos |
| **AI** | Skills e automações com Claude | Agentes, integração de LLMs em aplicações |
| **Qualidade** | JMeter, Postman, Insomnia, BDD | JUnit |

</details>

<details>
<summary><code>$ tail -f estudos.log</code></summary>

<br>

- **Pós-graduação em DevOps e Arquitetura Cloud** (FIAP PosTech) · em andamento. Kubernetes, IaC com Terraform, CI/CD e GitOps, DevSecOps, observabilidade, SRE, FinOps e AIOps.
- **Bootcamp de Ciência de Dados** (TripleTen) · dez/2025 → dez/2026. Análise de dados, machine learning, deep learning e SQL avançado. [Estudos aqui](https://github.com/TiagoAlcan/Triple-Ten-Data-Science).
- **Bacharelado em Sistemas de Informação** (FIAP) · 2022 → 2025.

</details>

<details>
<summary><code>$ man curiosidade</code></summary>

<br>

Coisas que operar um sistema em produção me ensinou a olhar de outro jeito:

- **1 milhão por dia parece muito, mas dá uns 12 por segundo.** A média é tranquila. O que derruba um sistema é o pico, e é por isso que um bom painel mostra taxa por janela de tempo em vez de total do dia.
- **99,9% de disponibilidade ainda são quase 9 horas fora do ar por ano.** Cada "nove" a mais divide esse tempo por dez: 99,99% são 52 minutos.
- **A média esconde quem está sofrendo.** Com 1 milhão de requisições por dia, o p99 representa 10 mil requisições diárias mais lentas que aquele valor. Alguém está do outro lado de cada uma.
- **Reiniciar não é recuperar.** Depois que a máquina volta, os serviços precisam subir na ordem certa. Foi isso que me fez escrever scripts para restabelecer aplicações sozinhas.
- **Se o painel precisa de explicação, ele é um relatório.** Um dashboard bom responde a uma pergunta em cinco segundos.

</details>

<details>
<summary><code>$ ./contato.sh</code></summary>

<br>

- E-mail: [tiago.gomesalcan@gmail.com](mailto:tiago.gomesalcan@gmail.com)
- LinkedIn: [linkedin.com/in/tiagoalcan](https://www.linkedin.com/in/tiagoalcan)
- Idiomas: português (nativo), inglês (avançado), espanhol (intermediário)

</details>

<br>

```console
$ uptime
em produção desde março de 2023 · São Paulo, Brasil
```
