# 🧭 Meta Specs — Context Engineering  
**Versão:** 1.0  
**Última atualização:** YYYY-MM-DD  
**Domínio:** [Defina o domínio do sistema]  
**Tags:** business, technical, architecture, rules, specs, context-engineering  

---

## 📘 Visão Geral
Este repositório contém as **Meta Specs** oficiais utilizadas para orientar agentes de IA no desenvolvimento, análise e manutenção do projeto.

A proposta é fornecer **contexto estável, estruturado e versionado**, garantindo que a IA produza código, documentação e análises que estejam **alinhadas ao core do negócio e às diretrizes técnicas oficiais**.

---

## 🗂 Estrutura
- **Business/** – O que o produto é, para quem existe e por quê.
- **Technical/** – Como o sistema deve ser construído, padrões, arquitetura e diretrizes de engenharia.

---

## 🧠 Regras para IA
1. Sempre respeitar as regras de negócio definidas em `/Business/business-rules.md`.  
2. Nunca inferir funcionalidades não documentadas.  
3. Utilizar somente a stack autorizada (`/Technical/stack.md`).  
4. Seguir decisões arquiteturais registradas em ADRs (`/Technical/architecture-decisions.md`).  
5. Evitar soluções que violem padrões de desenvolvimento (`/Technical/development-standards.md`).  

---

## 📎 Índice
### Business
- [Visão Geral de Negócio](./Business/index.md)
- [Visão de Produto](./Business/product-vision.md)
- [Atores](./Business/actors.md)
- [Regras de Negócio](./Business/business-rules.md)

### Technical
- [Visão Técnica](./Technical/index.md)
- [Stack Oficial](./Technical/stack.md)
- [ADRs](./Technical/architecture-decisions.md)
- [Estratégia de Testes](./Technical/testing-strategy.md)
- [Pontos de Integração](./Technical/integration-points.md)
- [Padrões de Desenvolvimento](./Technical/development-standards.md)
- [Problemas Conhecidos](./Technical/known-issues.md)
