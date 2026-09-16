# 🚀 Portfólio — Microsoft Power Platform

Bem-vindo ao meu portfólio de desenvolvimento de soluções utilizando **Microsoft Power Platform**.

Sou formado em **Gestão da Informação pela Universidade Federal do Paraná (UFPR)**, atualmente estudante de pós graduação em Cibersegurança pela PUC-PR e trabalhando como auditor de TI. Possuo experiência no desenvolvimento e implantação de soluções voltadas à **automação de processos, gestão de informações, desenvolvimento de aplicativos, documentação e testes de software**.

Este repositório reúne projetos desenvolvidos utilizando principalmente **Microsoft Power Apps, Power Automate, SharePoint e Power BI**, apresentando as soluções, tecnologias utilizadas, arquitetura, regras de negócio, testes e principais aprendizados.

---

## 👨‍💻 Sobre mim

Minha experiência combina **Tecnologia da Informação, Gestão da Informação e desenvolvimento de soluções low-code**, com atuação em projetos de automação e melhoria de processos.

Tenho experiência com:

* Desenvolvimento de aplicativos utilizando **Power Apps**
* Automação de processos utilizando **Power Automate**
* Estruturação e gerenciamento de dados no **SharePoint**
* Criação de dashboards e indicadores com **Power BI**
* Levantamento e documentação de requisitos
* Definição e implementação de regras de negócio
* Testes funcionais e validação de aplicações
* Documentação técnica e elaboração de manuais
* Suporte e implantação de soluções
* Gestão e organização de informações
* Integração entre ferramentas do ecossistema Microsoft 365

Atualmente, tenho direcionado minha carreira para áreas relacionadas a **QA/Testes de Software, Análise de Sistemas, Tecnologia e Cibersegurança**.

---

# 📱 Projetos

## 📦 Gerenciamento de Ativos

Sistema desenvolvido para auxiliar no gerenciamento de ativos, controle de disponibilidade e processos de empréstimo de equipamentos.

**Tecnologias:**

`Power Apps` `SharePoint` `Power Automate`

**Principais funcionalidades:**

* Cadastro e consulta de ativos
* Pesquisa e filtros
* Controle de status
* Controle de disponibilidade
* Solicitação de empréstimos
* Gerenciamento de empréstimos
* Consulta das solicitações do usuário
* Regras de negócio para controle dos ativos

➡️ [Ver projeto](projetos/gerenciamento-ativos/)

---

## 👥 Gestão de Colaboradores

Aplicação desenvolvida para centralizar e facilitar o gerenciamento das informações relacionadas aos colaboradores.

**Tecnologias:**

`Power Apps` `SharePoint` `Power Automate`

**Principais funcionalidades:**

* Cadastro de colaboradores
* Atualização de informações
* Consulta de registros
* Controle de status
* Automatização de notificações
* Organização centralizada das informações

➡️ [Ver projeto](projetos/gestao-colaboradores/)

---

## 💰 Gestão de Diárias, Prestação e Ressarcimentos

Solução desenvolvida para digitalização e organização do processo de solicitações relacionadas a diárias, prestações e ressarcimentos.

**Tecnologias:**

`Power Apps` `SharePoint` `Power Automate`

**Principais funcionalidades:**

* Registro de solicitações
* Controle de informações
* Acompanhamento de status
* Automatização de notificações
* Organização dos documentos
* Centralização das informações

➡️ [Ver projeto](projetos/diarias-ressarcimentos/)

---

## 📄 Controle de Ofícios

Aplicação voltada ao gerenciamento e acompanhamento de documentos e registros relacionados a ofícios.

**Tecnologias:**

`Power Apps` `SharePoint` `Power Automate`

➡️ [Ver projeto](projetos/controle-oficios/)

---

## 🎒 Gerenciamento de Kits e Periféricos

Solução para controle de kits, periféricos e disponibilidade de equipamentos.

**Tecnologias:**

`Power Apps` `SharePoint`

**Principais funcionalidades:**

* Controle de estoque
* Cadastro de itens
* Controle de disponibilidade
* Reserva de equipamentos
* Controle de retirada
* Consulta de solicitações

➡️ [Ver projeto](projetos/controle-kits-perifericos/)

---

## 🚁 Orçamento de Drone

Aplicação desenvolvida para apoiar o processo de orçamento e gerenciamento de informações relacionadas a equipamentos e operações com drones.

**Tecnologias:**

`Power Apps` `SharePoint` `Power Automate`

➡️ [Ver projeto](projetos/orcamento-drone/)

---

## 🎂 Gestão de Aniversariantes

Aplicação para centralização e consulta das informações de aniversariantes.

**Tecnologias:**

`Power Apps` `SharePoint` `Power Automate`

➡️ [Ver projeto](projetos/aniversariantes/)

---

# 🧰 Tecnologias

### Microsoft Power Platform

![Power Apps](https://img.shields.io/badge/Power%20Apps-742774?style=for-the-badge\&logo=powerapps\&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge\&logo=powerautomate\&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)

### Microsoft 365

* Microsoft SharePoint
* Microsoft Teams
* Microsoft Outlook
* OneDrive
* Microsoft Entra ID

### Desenvolvimento e Dados

* Power Fx
* Python
* SQL
* APIs
* JSON

### QA e Engenharia de Software

* Testes funcionais
* Testes de integração
* Validação de requisitos
* Casos de teste
* Análise de requisitos
* Cypress
* Postman
* JMeter
* CI/CD

### Metodologias

* Scrum
* Kanban
* ITIL
* Gestão de processos
* Documentação técnica

---

# 🏗️ Arquitetura das soluções

Grande parte das soluções apresentadas neste portfólio utiliza uma arquitetura baseada no ecossistema Microsoft:

```text
                    ┌──────────────────┐
                    │     Usuário      │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │    Power Apps    │
                    │                  │
                    │ Interface +      │
                    │ regras de negócio│
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │    SharePoint    │
                    │                  │
                    │ Dados +          │
                    │ Documentos       │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Power Automate   │
                    │                  │
                    │ Automação +      │
                    │ notificações     │
                    └────────┬─────────┘
                             │
              ┌──────────────┼──────────────┐
              ▼              ▼              ▼
         Outlook          Teams          Power BI
```

---

# 🧪 Testes e qualidade

Além do desenvolvimento das aplicações, os projetos são documentados considerando aspectos relacionados à **qualidade e validação do software**.

Entre os testes e validações realizados estão:

* Validação de requisitos
* Testes funcionais
* Testes de regras de negócio
* Testes de entrada de dados
* Testes de filtros e pesquisas
* Testes de permissões
* Testes de integração
* Testes de fluxos automatizados
* Validação de mensagens e notificações
* Testes de cenários positivos e negativos

Quando aplicável, cada projeto apresenta exemplos de casos de teste e critérios utilizados para validar o funcionamento da solução.

---

# 📚 Documentação

Além dos aplicativos, este portfólio busca demonstrar o processo de desenvolvimento e não somente o resultado final.

Cada projeto pode apresentar:

* 🎯 Objetivo
* 🔎 Problema identificado
* 💡 Solução proposta
* 🏗️ Arquitetura
* 🗃️ Estrutura dos dados
* ⚙️ Regras de negócio
* 🔄 Automações
* 💻 Fórmulas Power Fx
* 🧪 Casos de teste
* 📸 Screenshots
* 📖 Documentação técnica
* 🚧 Limitações
* 🔮 Possíveis melhorias

---

# 🔐 Segurança e privacidade

Os projetos apresentados neste repositório foram adaptados para fins de portfólio.

Informações sensíveis ou institucionais não são disponibilizadas publicamente.

Os exemplos podem utilizar:

* Dados fictícios
* Usuários anonimizados
* Screenshots adaptados
* Estruturas simplificadas
* Exemplos de código

Credenciais, tokens, chaves, informações pessoais e configurações internas não fazem parte deste repositório.

---

# 📈 Objetivo do portfólio

Este repositório tem como objetivo demonstrar minha experiência prática em:

**Gestão da Informação → Desenvolvimento → Automação → Testes → Documentação**

Busco aplicar esses conhecimentos na criação de soluções que sejam não apenas funcionais, mas também **organizadas, testáveis, documentadas e orientadas às necessidades dos usuários e processos**.

---

# 📫 Contato

**LinkedIn:** [Meu LinkedIn](COLOQUE-SEU-LINK)

**GitHub:** [Meu GitHub](COLOQUE-SEU-LINK)

---

⭐ Caso algum projeto seja interessante para você, fique à vontade para explorar sua documentação e implementação.
