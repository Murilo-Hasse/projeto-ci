# TECH_STACK.md - Guia Tecnológico (Padrão "Modinha de Mercado")

Este documento define a stack oficial da SPA. O objetivo é utilizar as ferramentas mais modernas, limpas e produtivas do ecossistema front-end atual (React + ecossistema moderno).

---

## 1. Core e Ferramental de Build

- **Framework:** **React 18+** (utilizando Functional Components e Hooks).
- **Build Tool / Bundler:** **Vite** (configuração rápida, HMR instantâneo e otimização de assets).
- **Linguagem:** **TypeScript** (tipagem estática para evitar bugs bobos de props e dados mockados).

---

## 2. Estilização e Design System

- **Estilização:** **Tailwind CSS** (utility-first CSS para prototipagem rápida e visual limpo/corporativo escuro/claro).
- **Componentes de UI:** **Shadcn UI** (Primitivos acessíveis construídos sobre Radix UI, copiados diretamente para o projeto, permitindo customização total).
- **Ícones:** **Lucide React** (o padrão moderno para ícones limpos e consistentes).

---

## 3. Gerenciamento de Estado e Dados

- **Estado Local:** React Hooks nativos (`useState`, `useEffect`, `useMemo`).
- **Dados Mockados (`/src/data/mockFunds.ts`):** Arquivos JSON estáticos tipados com os dados dos fundos e da linha do tempo satírica.

---

## 4. Estrutura de Pastas Sugerida

```text
src/
├── assets/          # Imagens, logos falsas e SVGs
├── components/      # Componentes reutilizáveis (Header, Banner, etc.)
│   └── ui/          # Componentes vindos do Shadcn UI (Button, Card, Tabs, etc.)
├── data/            # Mock data (fundos, timeline, simulador)
├── hooks/           # Custom hooks se necessário
├── lib/             # Utilitários (ex: cn helper do tailwind/shadcn)
├── pages/           # Seções principais da SPA (Dashboard, Timeline, Simulador)
├── App.tsx          # Componente raiz
└── main.tsx         # Ponto de entrada
```

## Pipelines

- **Syntaxe github_actions, para funcionar com github actions**
- **Package Maneger** use o pnpm
