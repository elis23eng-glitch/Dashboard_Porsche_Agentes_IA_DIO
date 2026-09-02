# Porsche Sales Intelligence — Dashboard com Agentes de IA

![Status](https://img.shields.io/badge/status-concluído-1f883d)
![DIO](https://img.shields.io/badge/projeto-DIO-d5001c)
![React](https://img.shields.io/badge/React-19-20232a?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178c6?logo=typescript)

Dashboard interativo desenvolvido para o desafio **“Criando uma Dashboard da Porsche com Agentes de IA”**, da [DIO](https://www.dio.me/). A solução transforma uma base de vendas em indicadores executivos, análises por cidade e insights comerciais atualizados automaticamente pelos filtros.

> **Demonstração:** [Porsche Sales Intelligence](https://porsche-sales-intelligence-dio.elis23-eng.chatgpt.site)

![Visão geral do Porsche Sales Intelligence](assets/dashboard-porsche-sales-intelligence.jpg)

## Objetivo

Criar uma experiência analítica elegante e funcional, inspirada na linguagem visual da Porsche, capaz de responder perguntas de negócio sobre modelos, cidades, períodos, pagamentos, eficiência operacional e oportunidades comerciais.

## Principais funcionalidades

### Filtros interativos

- Modelo Porsche
- Ano do modelo
- Cidade
- Método de pagamento
- Status da operação
- Data inicial e final da venda

Todos os componentes são recalculados de forma integrada quando um filtro é alterado.

### KPIs

- Receita total
- Volume de vendas
- Ticket médio
- Ano de modelo líder
- Taxa de entrega e cancelamento
- Operações em aberto e receita pendente
- Comparação com o período anterior

### Visualizações e inteligência comercial

- Ranking dos modelos mais vendidos
- Evolução mensal da receita
- Evolução acumulada das cinco cidades com maior receita
- Ranking de receita e modelo mais popular por cidade
- Participação por família Porsche
- Receita por método de pagamento
- Eletrificados versus combustão
- Insights executivos e alertas automáticos

## Base de dados

A análise utiliza **100 registros de vendas**, cobrindo o período de **fevereiro de 2024 a outubro de 2027**.

| Característica | Descrição |
|---|---|
| Registros | 100 vendas |
| Localização | Cidades e estados dos Estados Unidos |
| Moeda | Dólar americano — USD |
| Receita total | US$ 12.827.800,50 |
| Ano de modelo líder | 2024 |
| Dimensões | Modelo, ano, cidade, pagamento, status e data |

Os dados foram disponibilizados para fins educacionais. Datas, cidades e valores foram preservados conforme a base fornecida.

## Perguntas de negócio respondidas

1. Quais são os principais modelos vendidos por cidade?
2. Qual ano de modelo teve maior volume de vendas?
3. Como a receita das principais cidades evoluiu no período?
4. Quais modelos e cidades geram maior receita?
5. Quanto da receita permanece em operações não entregues?
6. Quais métodos de pagamento concentram maior valor?
7. Qual é a participação dos modelos eletrificados?
8. Quais cidades apresentam maior risco operacional?
9. Qual família Porsche possui maior participação?

## Tecnologias utilizadas

- HTML e CSS responsivo
- React e TypeScript
- Recharts
- Lucide Icons
- Agentes de IA para análise, implementação e documentação

## Estrutura principal

```text
.
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   ├── page.tsx
│   └── sales-data.ts
├── assets/
│   └── dashboard-porsche-sales-intelligence.jpg
├── docs/
│   ├── ARTIGO_DIO.md
│   ├── ENTREGA_DIO.md
│   └── POST_LINKEDIN.md
├── package.json
└── README.md
```

## Como executar localmente

### Pré-requisitos

- Node.js 22 ou superior
- npm

```bash
git clone https://github.com/elis23eng-glitch/Dashboard_Porsche_Agentes_IA_DIO.git
cd Dashboard_Porsche_Agentes_IA_DIO
npm install
npm run dev
```

Depois, abra o endereço apresentado no terminal.

## Como acessar

- **Código e documentação:** neste repositório público do GitHub.
- **Dashboard interativo:** pelo link de demonstração no início deste README.
- **Execução local:** seguindo as instruções acima.

## UI/UX

O dashboard utiliza contraste entre preto, branco e vermelho, tipografia editorial, hierarquia orientada à decisão, componentes responsivos e estados para filtros sem resultados. A referência visual foi o [site oficial da Porsche Brasil](https://www.porsche.com/brazil/pt/).

Este é um projeto acadêmico independente, sem vínculo oficial com a Porsche.

## Aprendizados

- Tradução de perguntas de negócio em KPIs
- Preparação e modelagem de dados
- Visualização e storytelling analítico
- Desenvolvimento de interfaces responsivas
- Uso de agentes de IA no ciclo de produto
- Documentação técnica e comunicação de resultados

## Autora

**Elisângela Alves Vieira**  
Engenheira Civil | Dados, Tecnologia e Gestão

[LinkedIn](https://www.linkedin.com/in/elisangelavieira-engcivil/) · [GitHub](https://github.com/elis23eng-glitch)

---

Projeto desenvolvido para fins educacionais como parte da formação na **DIO**.
