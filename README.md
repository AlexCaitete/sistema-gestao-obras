# 🏢 Sistema de Gestão de Obras e Cronogramas

Análise de Caminho Crítico, Curva S e Gestão de Módulos para Empresas de Engenharia. Projeto desenvolvido como parte prática da disciplina de **Engenharia de Requisitos** (2º Período - ADS).

---

## 📌 Sobre o Projeto

Este sistema foi concebido para centralizar e otimizar o fluxo de gerenciamento de projetos de construção civil. A plataforma resolve dores reais de comunicação e planejamento entre engenheiros de campo, gerentes de projetos e clientes finais, mapeando requisitos complexos em uma interface fluida, consistente e navegável.

O desenvolvimento foi totalmente guiado por **Metodologias Ágeis (Scrum)**, com o escopo monitorado através de *User Stories* detalhadas em quadros Kanban.

---

## 📱 Módulos do Sistema

O ecossistema do projeto está dividido nas seguintes interfaces de controle:

* **📊 Dashboard Gerente:** Visão macro de todos os projetos ativos, trazendo KPIs consolidados de performance.
* **📅 Cronograma Inteligente:** Ferramenta com visualização de Gráfico de Gantt, Caminho Crítico e **Curva S** (Gráfico SVG nativo que compara o progresso *Planejado* vs. *Executado*).
* **📝 Painel de Campo:** Interface de ponta para o engenheiro registrar relatórios diários e anexar evidências.
* **⚡ Painel de Aprovações:** Fluxo gerencial para validar planos de ação, mitigar riscos climáticos/financeiros e homologar novas datas.
* **👷 Portal do Cliente:** Área de transparência total para o cliente acompanhar o andamento da sua obra.

---

## 🛠️ Tecnologias e Arquitetura

Para garantir performance e componentização escalável, a interface foi desenvolvida utilizando:

* **HTML5 / CSS3 Semântico:** Estruturação limpa voltada para acessibilidade e SEO.
* **CSS Global & Classes Utilitárias (`global.css`):** Arquitetura moderna com reset unificado, padronização de paleta de cores (Tokens baseados em escalas Zinc) e centralização de componentes globais (como `.badge`, `.btn`).
* **SVG Nativo:** Renderização matemática e leve dos gráficos de performance (Curva S).
* **Git:** Controle de versão rigoroso focado em histórico limpo e organização de branches.

---

## ⚙️ Como Executar o Projeto Localmente
1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/AlexCaitete/sistema-gestao-obras.git](https://github.com/AlexCaitete/sistema-gestao-obras.git)

2. navegue até a pagina front

Bash
cd sistema-gestao-obras/front
Abra o projeto:
Você pode rodar os arquivos HTML diretamente no navegador ou utilizar a extensão Live Server no VS Code (rodando por padrão na porta 5500) para visualizar as atualizações em tempo real.

📈 Histórico de Engenharia e Refatoração
O repositório demonstra uma evolução contínua de boas práticas de código. Recentemente, o projeto passou por uma refatoração estrutural focada no princípio DRY (Don't Repeat Yourself):

Remoção de códigos repetidos de reset de margens e fontes em múltiplos arquivos CSS.

Unificação da identidade visual (UX/UI) das páginas através do arquivo utilitário global.

Padronização do espaçamento e grid das tabelas de Gantt e cards de aprovação.

👤 Desenvolvedor
Alex Roberto Alves Caitete - Desenvolvimento Front-end & Engenharia de Requisitos
linkedin: https://www.linkedin.com/in/alex-roberto-alves-90b99a37b/
link prototipo navegavel: : https://alexcaitete.github.io/sistema-gestao-obras/welcome.html

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/AlexCaitete/sistema-gestao-obras.git](https://github.com/AlexCaitete/sistema-gestao-obras.git)
