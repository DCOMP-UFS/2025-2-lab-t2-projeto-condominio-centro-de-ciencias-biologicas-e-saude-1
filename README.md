# 2025-2-lab-t2-projeto-condominio-centro-de-ciencias-biologicas-e-saude-1
2025-2-lab-t2-projeto-condominio-centro-de-ciencias-biologicas-e-saude-1 created by GitHub Classroom

# CCBS – Projeto de Estruturação de Redes de Computadores

Este repositório contém o site institucional (landing page) desenvolvido para o **trabalho final da disciplina Laboratório de Redes de Computadores**, cujo objetivo é simular a implantação completa de uma infraestrutura de redes para o **Centro de Ciências Biológicas e da Saúde (CCBS)** da **Universidade Federal de Sergipe (UFS)**.

O projeto reproduz um cenário real de planejamento de redes, incluindo levantamento de requisitos, definição de arquitetura lógica e física, endereçamento IP, orçamento baseado em atas vigentes e conformidade com edital fictício proposto pela disciplina.

---

## 🎯 Objetivo do Projeto

- Simular a **estruturação de rede de um centro acadêmico do zero**
- Aplicar conceitos práticos de:
  - Arquitetura de redes
  - Segmentação por sub-redes
  - Orçamento público via atas de registro de preços
  - Infraestrutura multiusuária
- Desenvolver um **site institucional moderno e responsivo** para apresentação do projeto

---

## 🧩 Escopo do Site

O site apresenta, de forma organizada e visual, as seguintes informações:

- Contexto geral do projeto
- Arquitetura da rede (planta física, mapa lógico e topologia Omada)
- Endereçamento IP por laboratório
- Orçamento detalhado por tipo de equipamento
- Orçamento distribuído por laboratório
- Divisão de recursos baseada na quantidade de pesquisas
- Gráficos de visualização orçamentária (Chart.js)
- Atas de registro de preços utilizadas
- Conformidade com o edital
- Equipe responsável pelo projeto

---

## 🧱 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Chart.js** (visualização gráfica)
- **Docker**
- **Docker Hub**
- **Nginx** (reverse proxy e roteamento)
- **Docker Compose** (orquestração dos containers)

---

## 🐳 Arquitetura com Docker

O site principal do CCBS e os sites individuais de cada laboratório são executados em **containers Docker separados**.

O acesso aos laboratórios é feito por **rotas configuradas no Nginx**, conforme o exemplo:

| Laboratório | Rota |
|------------|------|
| GPEPS | `/gpeps` |
| Funcionalidade Humana | `/funcionalidade-humana` |
| GPAI/UFS | `/gpai` |
| Ensino e Serviço em Saúde | `/ensino-servico` |
| Educação Científica | `/educacao-cientifica` |

Cada rota é redirecionada para o respectivo container Docker via Nginx.

---

## 🌐 Estrutura de Navegação

- `/` → Site institucional do CCBS
- `/gpeps` → Site do laboratório GPEPS
- `/funcionalidade-humana` → Site do laboratório de Funcionalidade Humana
- `/gpai` → Site do GPAI/UFS
- `/ensino-servico` → Site de Ensino e Serviço em Saúde
- `/educacao-cientifica` → Site de Educação Científica

---

## 📊 Orçamento

- **Valor total disponível:** R$ 250.000,00
- **Valor total utilizado:** R$ 249.866,40
- **Execução do orçamento:** 99,95%

O site apresenta:
- Tabelas detalhadas de custos
- Percentual por tipo de equipamento
- Percentual por laboratório
- Gráficos de pizza para facilitar a visualização

## Planilha de orçamentos

### Tabela dos equipamentos com base nas atas registradas

| Equipamento | Quantidade | Valor Unitário | Valor Total | ID da Ata |
|-------------|------------|----------------|-------------|-----------|
| Switch Gerenciável | 6 | R$ 6.390,00 | R$ 38.340,00 | 01263896000164-1-000173/2025 |
| Servidor TECZAP | 1 | R$ 79.990,00 | R$ 79.990,00 | 10673078000120-1-000139/2024 |
| Nobreak 1500VA | 5 | R$ 530,00 | R$ 2.650,00 | 32479123000143-1-000145/2025 |
| Nobreak 600VA | 1 | R$ 320,00 | R$ 320,00 | 32479123000143-1-000145/2025 |
| Access Point | 5 | R$ 1.698,99 | R$ 8.494,95 | 10735145000194-1-000240/2025 |
| Cabo CAT6 (metros) | 400 | R$ 2,40 | R$ 960,00 | 04892707000100-1-000453/2025 |
| Ar Condicionado | 4 | R$ 9.998,00 | R$ 39.992,00 | 00497560000101-1-000203/2025 |
| Desktop | 17 | R$ 4.619,85 | R$ 78.537,45 | 00348003000110-1-000454/2025 |
| Injetor PoE | 3 | R$ 194,00 | R$ 582,00 | 45358058000140-1-000242/2025 |
| **TOTAL GERAL** | - | - | **R$ 249.866,40** | - |

---

## 📄 Atas de Registro de Preços

Foram utilizadas **sete atas vigentes**, sendo seis pertencentes ao grupo e uma compartilhada:

- Servidor: Ata 10673078000120-1-000139/2024
- Nobreaks: Ata 32479123000143-1-000145/2025
- Access Points: Ata 10735145000194-1-000240/2025
- Cabeamento: Ata 04892707000100-1-000453/2025
- Desktops: Ata 00348003000110-1-000454/2025
- Ar-condicionado: Ata 00497560000101-1-000203/2025
- Injetores PoE: Ata 45358058000140-1-000242/2025
- Switches (ata compartilhada): Ata 01263896000164-1-000173/2025

---

## 👥 Equipe do Projeto

- **Gabriel Luiz Santos Gama Barreto** – Assistente de Atas de Registro de Compras  
- **João Felipe Quentino** – Coordenador do Projeto  
- **José Henrique Souza Santana** – Contador / Tesoureiro  
- **Pablo Alves Freire** – Assistente de Coordenação  
- **Thiago Menezes Vasconcelos** – Assistente de Coordenação  

---

## 📚 Disciplina

- **Disciplina:** Laboratório de Redes de Computadores  
- **Instituição:** Universidade Federal de Sergipe (UFS)  
- **Ano:** 2026  

---

## ✅ Considerações Finais

Este projeto tem caráter **acadêmico**, mas foi desenvolvido com foco em **boas práticas profissionais**, simulando um cenário real de implantação de infraestrutura de redes em ambiente institucional público.

O site serve como ferramenta de apresentação, documentação e validação do projeto desenvolvido pelo grupo.

---
