# Olá, sou o Antonio Queiroz 👋

Desenvolvedor backend Java focado em construir APIs que vão do primeiro endpoint até o deploy em produção.

---

## 🐾 PawsManager — Em produção

API REST para gestão de petshop, rodando em produção na Oracle Cloud.

O projeto cobre o ciclo completo de um backend: autenticação JWT, cache com Redis, migrations com Flyway, testes de integração com Testcontainers, CI/CD com GitHub Actions e deploy automatizado via Docker.

**🔗 [Testar os endpoints em produção](https://pawsapi.antonioqueiroz.dev/swagger-ui/index.html) · [Ver repositório](https://github.com/antonio-queiroz-dev/paws-manager)**

### Stack

`Java 21` · `Spring Boot 3` · `Spring Security + JWT` · `MySQL 8` · `Redis` · `Flyway` · `Testcontainers` · `Docker` · `GitHub Actions` · `JaCoCo`

### Destaques técnicos

- **Deploy real** na Oracle Cloud Free Tier (ARM VM, Ubuntu, Docker Compose)
- **78% de cobertura** de testes (85% em tutor, 82% em pet), monitorada via JaCoCo no pipeline de CI
- **Cache Redis** com TTL de 30 min e invalidação via `@CacheEvict`
- **CI/CD em 3 jobs**: testes → build da imagem Docker → deploy na Oracle Cloud
- **Imagem publicada no GHCR**: `ghcr.io/antonio-queiroz-dev/paws-manager:latest`

---

## Tecnologias

**Backend:** Java · Spring Boot · Spring Security · REST APIs · Maven  
**Banco & Cache:** MySQL · PostgreSQL · Redis  
**DevOps:** Docker · GitHub Actions · Oracle Cloud · Caddy  
**Testes:** JUnit · Testcontainers · JaCoCo · Flyway

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-queiroz-dev/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/antonio-queiroz-dev)
