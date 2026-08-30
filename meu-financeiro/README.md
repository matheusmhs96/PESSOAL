# Meu Financeiro

Aplicativo pessoal de controle financeiro — extrato mensal, despesas por categoria, investimentos e relatórios, tudo em um único arquivo HTML, sem servidor e sem dependências de backend.

## Como usar

Abra o arquivo `index.html` em qualquer navegador (celular ou computador). Não precisa instalar nada.

**Para usar como app no celular:**
1. Abra `index.html` no navegador do celular (Safari no iPhone, Chrome no Android)
2. Toque em **Compartilhar** (iPhone) ou no menu **⋮** (Android)
3. Escolha **"Adicionar à Tela de Início"**

O app ganha um ícone próprio e abre em tela cheia, como um aplicativo nativo.

## Funcionalidades

- **Ganhos, Despesas e Investimentos** organizados por categoria (com categorias personalizadas)
- **Vários meses e anos** — histórico completo, navegável
- **Resumo anual** com gráfico de barras, linha de saldo e gastos por categoria em anel
- **Exportação em imagem (JPEG)**: extrato mensal detalhado, relação mensal resumida e relação anual
- Interface pensada para toque, com seletor de categoria, folha de seleção de mês/ano e menu inferior fixo
- Os dados ficam salvos localmente no navegador do próprio usuário (não saem do dispositivo)

## Estrutura do repositório

```
meu-financeiro/
├── index.html              → o aplicativo (abrir este arquivo)
├── docs/
│   └── historico-do-projeto.html   → histórico completo de desenvolvimento + código-fonte
└── README.md
```

## Histórico de desenvolvimento

O arquivo `docs/historico-do-projeto.html` documenta todas as etapas de construção do projeto, do pedido inicial até a versão atual.
