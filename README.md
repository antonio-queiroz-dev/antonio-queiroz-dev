# Antonio Queiroz — Backend Java

Engenheiro de Software com foco em APIs REST com Spring Boot, do design ao deploy em produção. Construo projetos pessoais completos: autenticação, cache, testes, CI/CD e infraestrutura em cloud. Buscando oportunidade de estágio em desenvolvimento backend.

---

## PDV-API — SaaS Multitenant de Ponto de Venda `Em desenvolvimento`

API REST multitenant para ponto de venda, com isolamento de dados por tenant em banco compartilhado (shared-database). Projetada para atender diversos segmentos de pequenos negócios com uma única instância.

**Stack:** `Java 21` · `Spring Boot 4` · `Spring Security + JWT` · `PostgreSQL` · `Flyway` · `Docker` · `GitHub Actions` · `SpringDoc OpenAPI`

### Destaques técnicos

- **27 endpoints** documentados com Swagger UI (100% de cobertura da API)
- **Arquitetura multitenant** shared-database com isolamento por tenant
- **2 estratégias de identificação**: UUID global + código sequencial por tenant
- **2 níveis de controle de acesso**: roles + contexto de tenant
- **5 migrações Flyway** versionando o schema incremental

**[Ver repositório](https://github.com/antonio-queiroz-dev/pdv-api)**

---

## PawsManager — API REST para Gestão de Petshops `Em produção`

API REST completa para gestão de petshop, rodando em produção na Oracle Cloud. Cobre o ciclo completo de um backend: autenticação JWT, cache com Redis, migrations com Flyway, testes de integração com Testcontainers, CI/CD com GitHub Actions e deploy automatizado via Docker.

**Stack:** `Java 21` · `Spring Boot 3` · `Spring Security + JWT` · `MySQL 8` · `Redis` · `Flyway` · `Testcontainers` · `Docker` · `GitHub Actions` · `JaCoCo`

### Destaques técnicos

- **Deploy real** na Oracle Cloud (ARM VM, Ubuntu, Docker Compose com 4 containers)
- **78% de cobertura** de testes com 41 testes automatizados (JUnit 5, Mockito, Testcontainers)
- **18 endpoints** documentados com Swagger UI via SpringDoc OpenAPI
- **Cache Redis** com TTL de 30 min e invalidação via `@CacheEvict`
- **CI/CD em 3 jobs**: testes → build Docker multi-plataforma (amd64/arm64) → deploy via SSH

**[Testar os endpoints em produção](https://pawsapi.antonioqueiroz.dev/swagger-ui/index.html) · [Ver repositório](https://github.com/antonio-queiroz-dev/paws-manager)**

---

## Formação

- **Pós-graduação em Projetos de Cloud Computing** — Descomplica Faculdade (2026 – em andamento)
- **Bacharelado em Engenharia de Software** — Unicesumar (2020 – 2023)

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-queiroz-dev/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/antonio-queiroz-dev)
[![Site](https://img.shields.io/badge/Site-antonioqueiroz.dev-2563eb?style=flat&logo=google-chrome&logoColor=white)](https://antonioqueiroz.dev)
[![Email](https://img.shields.io/badge/Email-juniorqueirozaa@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:juniorqueirozaa@gmail.com)
