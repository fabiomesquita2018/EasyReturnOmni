# 🚚 EasyReturn Omni

## 📌 Sobre o Projeto

O **EasyReturn Omni** é uma plataforma omnichannel desenvolvida para centralizar e automatizar o processo de devoluções no varejo, proporcionando uma experiência mais eficiente para clientes, equipes de SAC e operações logísticas.

O projeto foi concebido utilizando a metodologia **Lean Inception**, permitindo definir rapidamente o MVP (Minimum Viable Product), priorizar funcionalidades e estruturar o Product Backlog utilizando práticas ágeis.

---

## 🎯 Objetivo

O objetivo do EasyReturn Omni é reduzir o tempo operacional das devoluções, aumentar a satisfação dos clientes e integrar diferentes canais de venda e operação em um único fluxo de devolução.

---

## 🚩 Problema

Atualmente, muitos processos de devolução são realizados manualmente, utilizando diversos sistemas e canais de atendimento, causando:

- Alto tempo de atendimento;
- Retrabalho operacional;
- Baixa rastreabilidade;
- Falta de padronização;
- Insatisfação dos clientes.

---

## 💡 Solução Proposta

O EasyReturn Omni disponibiliza:

- Portal do Cliente;
- Portal Operacional (SAC);
- API de Integração;
- Gestão centralizada de devoluções;
- Rastreamento completo do processo;
- Integração com ERP e operadores logísticos.

---

# 👥 Personas

## Persona 1 — Cliente E-commerce

### Perfil
- Cliente do varejo online;
- Realiza compras frequentemente;
- Busca rapidez e praticidade.

### Necessidades
- Solicitar devoluções facilmente;
- Acompanhar status;
- Receber notificações;
- Gerar etiquetas.

---

## Persona 2 — Analista de SAC

### Perfil
- Responsável pelo atendimento e acompanhamento das devoluções;
- Atua diretamente na resolução dos problemas dos clientes.

### Comportamentos
- Analisa solicitações;
- Consulta pedidos;
- Atualiza status;
- Interage com clientes;
- Monitora SLAs.

### Necessidades
- Visualizar devoluções centralizadas;
- Atualizar status rapidamente;
- Emitir etiquetas;
- Gerar vale-compra;
- Integrar sistemas.

---

# 🚀 MVP

O MVP definido contempla:

- Consulta de pedidos;
- Solicitação de devolução;
- Geração de protocolo;
- Consulta de status;
- Confirmação de recebimento;
- Geração de etiqueta;
- Notificações.

---

# 🏗 Arquitetura

```text
Cliente
    │
    ▼
Portal Web
    │
    ▼
API Gateway
    │
    ▼
EasyReturn API
    ├── Pedidos
    ├── Devoluções
    ├── Notificações
    ├── Etiquetas
    └── Usuários
            │
            ├── ERP
            ├── Correios
            └── Banco de Dados
