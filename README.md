# GitHub Actions Lab 🚀

Repositório de estudo para praticar CI (Continuous Integration) e automação de fluxos com GitHub Actions.

---

## 🎯 Objetivo

Testar a integração de uma aplicação NestJS com pipelines automatizadas, validando builds e testes em diferentes versões de ambiente.

---

## 🛠️ O que a Pipeline faz?

Configurada em `.github/workflows/test.yml`, ela executa:

- **Trigger:** Push, Pull Request e agendamento via Cron.
- **Ambientes:** Node.js 20.x e 22.x (Ubuntu).
- **Steps:**
  1. Instalação limpa (`npm ci`).
  2. Verificação de padrões (`lint`).
  3. Testes End-to-End (`test:e2e`).

---

## 💻 Comandos rápidos
```
npm install     # Instalar
npm run lint    # Validar
npm run test:e2e # Testar
```