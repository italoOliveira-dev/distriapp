# 🍻 DistriApp Controller

> **Sistema de gestão para distribuidoras de bebidas**, desenvolvido como projeto pessoal de aprendizado e aplicação prática.  
> O objetivo é digitalizar o processo de vendas, controle de estoque, histórico de pedidos e contas a receber, oferecendo uma plataforma moderna e intuitiva.

---

## 🧭 Visão Geral

O **DistriApp Controller** é uma aplicação **SPA (Single Page Application)** composta por:
- **Frontend:** Angular 19
- **Backend:** Spring Boot (Java 21 + Gradle)
- **Banco de Dados:** PostgreSQL

O sistema permite gerenciar **clientes, pedidos, pagamentos, estoque e entregas**, substituindo controles manuais e planilhas por uma solução integrada e escalável.

---

## ⚙️ Stack Tecnológica

| Camada | Tecnologia | Descrição |
|--------|-------------|------------|
| Frontend | Angular 19 | SPA responsiva e moderna |
| Backend | Spring Boot (Java 21, Gradle) | API RESTful modular e escalável |
| Banco de Dados | PostgreSQL | Armazenamento relacional seguro |
| ORM | Spring Data JPA / Hibernate | Mapeamento objeto-relacional |
| CI/CD | GitHub Actions (futuro) | Automação de build, testes e deploy |
| Versionamento | Git / GitHub | Controle de versões e colaboração |

---

## 🏗️ Estrutura do Projeto

```bash
distriapp-controller/
├── backend/
│   ├── src/
│   ├── build.gradle
│   ├── settings.gradle
│   └── README.md
├── frontend/
│   ├── src/
│   ├── angular.json
│   └── package.json
├── docs/
│   ├── artefatos/
│   └── diagramas/
└── README.md
```

---

## 🚀 Como Executar Localmente

### 🔧 Pré-requisitos
- **Java 21**
- **Gradle 8+**
- **Node.js 20+**
- **PostgreSQL 15+**
- **Git**

### 🗄️ Configuração do Banco
Crie o banco de dados no PostgreSQL:
```sql
CREATE DATABASE distriapp_db;
```

Configure as credenciais no arquivo `application.yml` (backend):
```yaml
spring:
  datasource:
    url: jdbc:postgresql://localhost:5432/distriapp_db
    username: postgres
    password: sua_senha
```

### ▶️ Rodando o Backend
```bash
cd backend
./gradlew bootRun
```

### 💻 Rodando o Frontend
```bash
cd frontend
npm install
npm start
```

---

## 🧩 Organização das Branches

| Branch | Descrição |
|---------|------------|
| `main` | Versão estável do projeto |
| `develop` | Desenvolvimento ativo |
| `feature/*` | Novas funcionalidades |
| `fix/*` | Correções pontuais |
| `docs/*` | Documentação e artefatos |

---

## 🧠 Boas Práticas

- Commits no padrão **Conventional Commits** (`feat:`, `fix:`, `docs:`, etc)
- Código padronizado com **ESLint** (frontend) e **Checkstyle** (backend)
- Utilizar **Pull Requests** para mergear novas features

---

## 🧾 Licença

Este projeto é de uso pessoal e educacional.  
© 2025 - Desenvolvido por **Italo Ramos de Oliveira**

---

## 📬 Contato

👤 **Autor:** Italo Ramos de Oliveira  
💼 **Organização:** DistriApp Controller  
📧 *italooliveiraxdd@gmail.com*  
🌐 [GitHub - Italo Ramos de Oliveira](#)

