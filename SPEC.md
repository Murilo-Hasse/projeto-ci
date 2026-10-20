# SPEC.md - Especificação Base do Produto

## Nome Provisório: MasterPlan Simulator & Timeline (Sátira Faria Limer)

---

## 1. Visão Geral do Produto

O **MasterPlan** é uma Single Page Application (SPA) web com foco humorístico e satírico, simulando um portal financeiro corporativo de fundos de investimento e previdência ligados ao "Caso Master". A aplicação cumpre o requisito acadêmico de oferecer um **serviço útil/interativo (simulador financeiro e comparador)**, ao mesmo tempo em que utiliza dados mockados, nomenclaturas corporativas vazias ("lero-lero") e uma linha do tempo alternativa para entreter os avaliadores.

---

## 2. Público-Alvo e Monetização (Simulada)

- **Público:** Estudantes de tecnologia, entusiastas de finanças, curiosos e bancas avaliadoras de trabalhos acadêmicos.
- **Modelo de Monetização (Mock):** Espaços publicitários e banners falsos na interface (ex: _"Curso de Faria Limer: Como falar 40 minutos sem dizer nada"_).

---

## 3. Requisitos Funcionais (RF)

### RF01: Dashboard de Fundos Envolvidos (Cards / Kanban)

- Listagem de fundos de previdência e investimentos icônicos do caso.
- Cada card deve conter:
  - Nome do fundo (ex: _Fundo de Previdência Água de Março S.A._).
  - Rentabilidade declarada vs. Realidade (ex: "+450% ao mês (Teórico) / -99.8% (Contábil)").
  - Descrição em "lero-lero" corporativo gerado por IA/pirotecnia.
  - Status de saúde do fundo (ex: _"Esmaecendo com elegância", "Sob intervenção mística"_).

### RF02: Linha do Tempo Histórica (Timeline Sátira)

- Componente visual interativo exibindo marcos temporais fictícios/exagerados da trajetória do Banco Master e seus parceiros.
- Cada marco possui título, ano/data fictícia e uma descrição cômica dos bastidores.

### RF03: Simulador de Investimentos Imaginários

- Ferramenta interativa onde o usuário simula um aporte financeiro (ex: R$ 10.000).
- Gráficos e indicadores de retorno que simulam o comportamento de investimentos de alto risco com finais cômicos (gráfico que some, fogos de artifício seguidos de aviso de bloqueio judicial).

---

## 4. Requisitos Não Funcionais (RNF)

- **RNF01:** Aplicação SPA responsiva (Mobile First, com forte foco em Desktop pela natureza corporativa).
- **RNF02:** Experiência de usuário fluida, com micro-interações via Tailwind CSS.
- **RNF03:** Componentes acessíveis e limpos com base no ecossistema Shadcn UI.
