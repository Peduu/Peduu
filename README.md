<div align="center">

# Pedro Forlin

**Engenheiro de Sistemas · Logística Operacional · Mercado Financeiro · Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:pedrohfg020@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedroforlin)

</div>

---

## Sobre mim

Engenheiro de sistemas com atuação prática em operações logísticas de alto volume — projeto, publico e mantenho infraestrutura completa, do banco de dados ao deploy.

- **7 sistemas live** — hub operacional, rastreamento B2B, frota, comunicados, bipagem, cargo aéreo e integração e-commerce
- **+143.000 pedidos** processados no portal de bipagem de franquias
- **38 franquias** integradas em tempo real via TMS
- **Plataforma B2B multi-tenant** com portais white-label para Tribanco, BRB, PinBank, Panini e Inter
- **Zero custo de infraestrutura** — tudo rodando em VPS Linux único

Em transição para mercado financeiro e Machine Learning — preparando certificação ANBIMA (C-Pro R).

---

## Sistemas Live

| Projeto | Descrição | Stack |
|---------|-----------|-------|
| **AgyLog Operations Hub** | Painel administrativo central com 13 ferramentas: emissão, reimpressão e importação em lote de HAWB/CAOA, separação e devolução de agências por bipagem, expedição e romaneios, unificação de etiquetas de rastreio em PDF, controle de qualidade (acareação), blocagem, gestão de usuários e permissões, auditoria de acessos e console de banco. CI/CD automático via GitHub Actions | Python · Flask · SQLite · nginx |
| **Portal de Rastreio B2B** | Plataforma multi-tenant com CAPTCHA server-side, rate limiting e portais white-label por parceiro (5 clientes enterprise) | Python · Flask · SSL · nginx |
| **Rastreio Aéreo** | Tracking de cargas aéreas com mapa interativo em tempo real | Leaflet.js · Flask |
| **Central de Rotas** | Frota de 9 veículos em tempo real, atualização a cada 10s via API Positron | Leaflet.js · Flask |
| **Card Notifier** | Engine de e-mails: templates dinâmicos, múltiplos remetentes SMTP e histórico completo de envios | Python · FastAPI · PostgreSQL |
| **Bipagem de Franquia** | +143.000 pedidos processados em 38 franquias com sync TMS e detecção de divergências em tempo real | Python · SQLite |
| **Integração E-commerce** | Nuvemshop → TMS: intake de webhooks, roteamento automático, sync bidirecional de rastreamento | TypeScript · Node.js · Express · PostgreSQL · Prisma |

---

## Stack

- **Backend** → Python · Flask · FastAPI · Gunicorn · Node.js · TypeScript · Express
- **Frontend** → HTML · CSS · JavaScript · Leaflet.js
- **Dados / ML** → PostgreSQL · SQLite · Pandas · scikit-learn · integrações TMS e e-commerce (Nuvemshop)
- **Infraestrutura** → nginx · VPS Linux · Let's Encrypt · systemd · GitHub Actions
