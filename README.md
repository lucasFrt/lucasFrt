# Olá, sou o Lucas Frota 👋

**Engenheiro de Software Backend | Arquitetura de APIs & Integração de Sistemas**  
📍 Niterói, RJ • [LinkedIn](https://linkedin.com/in/lucas-miguel-frota) • [Email](mailto:lucasmigfrota03@gmail.com)

Atuo com foco no desenvolvimento de APIs RESTful de alta disponibilidade, automação de processos operacionais e modelagem de bancos de dados no ecossistema **Node.js, TypeScript e React**. Tenho experiência corporativa na arquitetura de plataformas do zero, automação de dados fiscais/financeiros e gestão de infraestrutura de servidores.

---

### 🛠️ Tech Stack & Competências

* **Back-end & Arquitetura:** Node.js, TypeScript, JavaScript, APIs RESTful, Padrão Controller-Service-Repository, Filas/Workers (BullMQ), JWT, Helmet.
* **Bancos de Dados & ORM:** SQL Server, Prisma ORM, MySQL, MariaDB, Redis, PocketBase.
* **Front-end:** React 19, Tailwind CSS 4.0, TanStack Query v5, Vite.
* **Infraestrutura & DevOps:** Windows Server, IIS (Reverse Proxy), NSSM, PM2, Cloudflare Workers, Git.
* **Automação & Integrações:** Parsing de XML/PDF, Consumo de APIs públicas/governamentais, Web Scraping.

---

### 📌 PoCs & Arquiteturas de Demonstração (Showcase)

*Como o código do meu dia a dia profissional reside em repositórios privados corporativos, criei as PoCs abaixo para demonstrar os padrões de arquitetura e soluções técnicas que utilizo:*

#### ⚡ 1. [enterprise-node-boilerplate](https://github.com/lucasFrt/enterprise-node-boilerplate)
> **Arquitetura Base para APIs RESTful de Alta Disponibilidade**  
> Modelo demonstrativo de arquitetura corporativa em camadas (*Controller-Service-Repository*), pronta para produção.
* **Techs:** Node.js, TypeScript, Prisma ORM, SQL Server, Redis, JWT, Zod/Joi.
* **Destaques:** Tratamento global de exceções, autenticação JWT, validação rigorosa de schemas e rotas documentadas via Swagger.

#### 📄 2. [nfe-xml-parser-stream](https://github.com/lucasFrt/nfe-xml-parser-stream)
> **Engine de Parsing & Automação de Documentos Fiscais**  
> Demonstração de leitura, parsing e conversão de arquivos XML complexos (NF-e) utilizando processamento em memória.
* **Techs:** Node.js, TypeScript, Stream Processors.
* **Destaques:** Conversão eficiente sem dependências pagas de terceiros, validação de campos obrigatórios e preparação de payload estruturado para persistência em banco.

#### 📈 3. [bcb-rate-fetcher-service](https://github.com/lucasFrt/bcb-rate-fetcher-service)
> **Worker de Extração e Polling de Dados Cambiais em Tempo Real**  
> Serviço em segundo plano para consumo resiliente de dados financeiros (API do Banco Central do Brasil).
* **Techs:** Node.js, TypeScript, Axios, Redis.
* **Destaques:** Resiliência a oscilações de rede, estratégia de cache com Redis para evitar *rate limit* e disponibilidade de endpoints leves para consumo de dashboards.

---

📬 **Contato Profissional:**
- LinkedIn: [linkedin.com/in/lucas-miguel-frota](https://linkedin.com/in/lucas-miguel-frota)
- E-mail: lucasmigfrota03@gmail.com
