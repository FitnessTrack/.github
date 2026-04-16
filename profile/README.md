# FitTrack Pro - Ecossistema SaaS para Profissionais de Saúde 🚀

O **FitTrack Pro** é uma plataforma completa (Web & Mobile) desenvolvida para profissionais de Educação Física e Nutrição, permitindo uma gestão 360º de seus clientes, desde a avaliação física até a prescrição técnica e controle financeiro.

## 🌟 O que o sistema já é capaz de fazer:

### 🛡️ Segurança & Arquitetura
- **Isolamento Multi-tenant:** Cada profissional possui seu workspace blindado. Implementamos **Security Hardening** com extração de `tenantId` direto do JWT, garantindo isolamento absoluto de dados.
- **Autenticação Robusta:** Sistema de Login/Registro com **MFA (Autenticação de Dois Fatores)** nativa.
- **Infraestrutura:** Dockerizado com PostgreSQL, Redis e isolamento de banco por Tenant.

### 📅 Gestão de Agenda & Leads
- **Agendamento Inteligente:** Definição de disponibilidade semanal e motor de busca de slots livres.
- **Portal Público de Agendamento:** Landing page personalizada para captação de novos clientes (Link na Bio) com fluxo multi-step.
- **Controle de Sessões:** Histórico completo de presenças, cancelamentos e reagendamentos.

### 📊 Avaliações & Evolução
- **Avaliação Física Profissional:** Suporte aos protocolos **Pollock (7 dobras)** e **Faulkner (4 dobras)** com cálculos automáticos de % Gordura, Massa Magra e IMC.
- **Dashboards de Histórico:** Gráficos interativos (`recharts`) de evolução antropométrica ao longo do tempo.
- **Galeria Antes & Depois:** Visualizador premium de fotos de evolução com slider interativo para o aluno e o profissional.

### 🏋️ Treinamento & Prescrição
- **Construtor de Treinos:** Editor modular de fichas de treino (Treinos A, B, C...) com controle de séries, repetições, carga e tempo de descanso.
- **Biblioteca de Exercícios:** Base de dados pré-cadastrada com grupos musculares e suporte a vídeos de execução.
- **Modo Treino (Mobile):** Cronômetro de descanso nativo e registro de carga real utilizada pelo aluno.

### 🍏 Nutrição & Metabolismo
- **Cálculo Metabólico:** Sugestão de meta calórica usando as fórmulas de **Harris-Benedict** e **Mifflin-St Jeor**.
- **Prescritor de Dietas:** Montagem de cardápios com soma automática de macronutrientes baseada na **Tabela TACO/USDA**.

### 💳 Financeiro & Crescimento
- **Gestão de Assinaturas:** Controle de planos de serviço e vencimentos por aluno.
- **Integração Pagar.me:** Motor financeiro pronto para processar pagamentos via Cartão e PIX com suporte a Webhooks.
- **Relatórios de Faturamento:** Visualização de receita mensal (MRR) e inadimplência no Dashboard do profissional.

### 💬 Comunicação
- **Central de Mensagens:** Chat interno (Inbox) para comunicação direta professor-aluno, eliminando a dependência do WhatsApp.

### 👑 Gestão do Negócio (Super Admin)
- **Painel de Controle do SaaS:** Interface exclusiva para os donos da plataforma monitorarem a saúde do negócio.
- **Gestão de Tenants:** Controle granular sobre todos os profissionais cadastrados, com funções de auditoria, suspensão e ativação.
- **Faturamento Global:** Visão consolidada da receita do SaaS e crescimento da base de assinantes (profissionais).
- **Política de Hard Block:** Sistema automático que bloqueia o acesso técnico (Treinos/Dietas) de profissionais inadimplentes e seus respectivos alunos, incentivando a adimplência.

---

> [!IMPORTANT]
> **Status Atual:** ✅ **Projeto Concluído (MVP 1.0)**
> - **Progresso Global:** 100%
> - **Ambiente:** Pronto para Deploy e Escala Comercial.

Para mais detalhes técnicos, consulte os repositórios individuais:
- [Backend (NestJS)](https://github.com/FitnessTrack/Backend)
- [Web (Next.js)](https://github.com/FitnessTrack/Web)
- [Docs & Planejamento](https://github.com/FitnessTrack/Docs)
