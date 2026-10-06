# Luca Casanova

**Desenvolvedor Backend Sênior** · Node.js · TypeScript · PHP/Laravel · Python

Desenvolvo backend há mais de 6 anos (comecei programando sozinho aos 16). Trabalho principalmente com Node.js/TypeScript e PHP/Laravel, sobre PostgreSQL, MySQL e Redis. A maior parte do que construí envolve integração entre sistemas: APIs REST, webhooks, filas, gateways de pagamento, ERPs, CRMs e mensageria. Também cuido da infraestrutura: servidores Linux, Docker, Traefik, Nginx e CI/CD.

A maior parte do meu código está em repositórios privados de clientes e produtos. Abaixo, um resumo do que tenho feito.

---

## Projetos

### WaveAI: SaaS multi-tenant de reservas e atendimento via WhatsApp
Plataforma para empresas de turismo e eventos, construída do modelo de dados ao deploy.

- **Backend:** Laravel 12 (PHP 8.3, Octane/FrankenPHP), com camadas de domínio, repositórios e serviços
- **Frontend:** Next.js 16, React 19, TypeScript
- **Dados:** PostgreSQL com Row Level Security por tenant, RBAC, Redis para filas e cache
- **Integrações:** WhatsApp Cloud API (Meta Tech Provider) com webhooks e inbox em tempo real; billing recorrente com Stripe
- **Qualidade e entrega:** testes automatizados (PHPUnit, Vitest), deploy contínuo com GitHub Actions e rollout sem downtime
- **IA:** agentes, RAG com pgvector e MCP servers próprios para diagnóstico e operação

### Plataforma de atendimento e chatbot para WhatsApp (AE Digital)
Node.js, TypeScript, Express, Sequelize, Socket.IO, PostgreSQL/MySQL, React. Filas de atendimento em tempo real, autenticação JWT, documentação Swagger e análise estática no SonarCloud.

### Sistema de gestão de projetos (AE Digital)
Express + TypeScript, Next.js, Supabase (Auth/Realtime), Redis, MinIO/S3. Controle de horas, custo por projeto, automações de faturamento e integração com Google Calendar/Sheets. Deploy em Docker Swarm com Traefik e testes de integração com Jest.

### Integrações e automações (AE Digital)
- Pagamentos: Stripe, Mercado Pago, Pagar.me, PayPal, InfinitePay
- ERPs e CRMs: Bling, Omie, HubSpot, Bitrix24, RD Station
- Mensageria e dados: WhatsApp Business Cloud, Meta Graph API, Google APIs
- Scraping e rotinas agendadas: Puppeteer, Cheerio, node-cron, serviços systemd em VPS Linux

---

## Stack

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.3-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel_12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

[LinkedIn](https://www.linkedin.com/in/luca-casanova-dev)
