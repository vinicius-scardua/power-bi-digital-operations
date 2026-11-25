# Digital Operations BI – Portfolio

Projeto de Business Intelligence desenvolvido com Power BI para análise de operações digitais, utilizando uma base de dados totalmente fictícia.

## Sobre o projeto

O objetivo deste projeto é desenvolver um dashboard interativo para acompanhar indicadores operacionais e apoiar análises relacionadas a produtos digitais, matrículas, receita, suporte ao cliente, engajamento em comunidades e mentorias.

O projeto simula um cenário de uma empresa de educação digital com múltiplos produtos e permite explorar diferentes perspectivas da operação por meio de indicadores e filtros.

## Dashboard

![Digital Operations BI Dashboard](images/dashboard-overview.png)

## Indicadores (KPIs)

O dashboard apresenta seis indicadores principais:

- **Total de matrículas:** quantidade de matrículas registradas.
- **Estudantes com matrículas:** quantidade de estudantes únicos com pelo menos uma matrícula.
- **Receita total:** soma dos valores das matrículas.
- **Total de tickets:** quantidade de chamados de suporte registrados.
- **Tempo médio de resolução:** média de horas necessárias para resolver os tickets.
- **Satisfação média:** média das avaliações de satisfação dos atendimentos.

## Análises disponíveis

O relatório apresenta seis visualizações:

- Matrículas por produto.
- Receita por produto.
- Distribuição de matrículas por status.
- Tickets de suporte por categoria.
- Atividades nas comunidades por tipo.
- Distribuição das sessões de mentoria.

## Interatividade

O dashboard possui filtros interativos para explorar os dados por:

- **Produto:** permite selecionar um ou mais produtos.
- **Período:** permite analisar diferentes datas e períodos.

Os filtros interagem com os indicadores e gráficos, permitindo comparar resultados e observar mudanças nos dados conforme os critérios selecionados.

## Base de dados

O projeto utiliza sete arquivos CSV com dados sintéticos:

| Arquivo | Descrição |
|---|---|
| `dim_products.csv` | Cadastro de produtos digitais |
| `dim_students.csv` | Cadastro de estudantes |
| `dim_date.csv` | Dimensão de datas |
| `fact_enrollments.csv` | Dados de matrículas e receita |
| `fact_community_activity.csv` | Atividades nas comunidades |
| `fact_support_tickets.csv` | Tickets de suporte |
| `fact_mentorship_sessions.csv` | Sessões de mentoria |

**Importante:** todos os dados utilizados são fictícios, criados exclusivamente para fins educacionais e de demonstração de habilidades analíticas. Não representam clientes, estudantes ou resultados de uma empresa real.

## Tecnologias e ferramentas

- Power BI
- Power Query
- DAX
- CSV
- Modelagem de dados

## Estrutura do projeto

```text
power-bi-digital-operations/
│
├── digital-operations-bi.pbix
├── README.md
│
├── data/
│   ├── dim_products.csv
│   ├── dim_students.csv
│   ├── dim_date.csv
│   ├── fact_enrollments.csv
│   ├── fact_community_activity.csv
│   ├── fact_support_tickets.csv
│   └── fact_mentorship_sessions.csv
│
└── images/
    └── dashboard-overview.png
```

## Objetivo profissional

Este projeto faz parte do meu portfólio de análise de dados e operações digitais, demonstrando conhecimentos em organização e modelagem de dados, construção de indicadores, análise de desempenho operacional e desenvolvimento de dashboards interativos.

