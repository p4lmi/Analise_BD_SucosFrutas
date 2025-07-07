# Analise_BD_SucosFrutas,

# 🧃 Projeto de Análise de Vendas – SucoFrutas

## 💡 Descrição

Este projeto tem como objetivo explorar e analisar um banco de dados fictício de uma empresa de sucos chamada **SucoFrutas**. Através de comandos SQL, realizei investigações profundas sobre vendas, clientes, produtos e desempenho de vendedores, buscando padrões e oportunidades de melhoria.

O estudo foca em responder questões estratégicas como:

- 👤 Quem são os melhores clientes?
- 🧭 Como os vendedores estão distribuídos geograficamente?
- 💰 Quais produtos têm maior valor ou volume de vendas?
- 🚫 Existem vendas além do volume permitido?
- 🍓 Quais sabores lideram as vendas em cada ano?

---

## 🧠 Técnicas e Conceitos Aplicados

Durante a construção deste projeto, foram aplicadas técnicas fundamentais em SQL, incluindo:

- ✅ Inserção de dados com `INSERT INTO`
- 🔗 Junções de tabelas com `JOIN`, `LEFT JOIN`, `FULL JOIN`, `INNER JOIN`
- 🧠 Segmentações com `CASE WHEN`
- 🕒 Conversão e manipulação de datas com `CONVERT`, `YEAR`, `VARCHAR`
- 🧮 Funções agregadas como `AVG()`, `COUNT()`, `SUM()`, `ROUND()`
- 🔄 Subqueries e expressões com `WITH (CTE)`
- 📊 Agrupamentos com `GROUP BY` e ordenações com `ORDER BY`
- ❓ Filtros e condições com `WHERE`, `IS NULL`, `IN`

---

## 🗂️ Estrutura do Banco de Dados

As principais tabelas envolvidas na análise são:

- `TABELA_DE_CLIENTES`
- `TABELA_DE_VENDEDORES`
- `TABELA_DE_PRODUTOS`
- `NOTAS_FISCAIS`
- `ITENS_NOTAS_FISCAIS`

---

## 🧾 Exemplos de Consultas

Aqui estão algumas das análises realizadas no projeto:

- 🔶 **Clientes sem compras**: Identificação de clientes cadastrados que nunca efetuaram compras.
- 🔶 **Segmentação de clientes por limite de crédito**: Classificação como "pequeno", "médio" ou "grande".
- 🔶 **Desempenho de vendedores por bairro**: Comparação entre localização dos vendedores e clientes.
- 🔶 **Volume de compras excedido**: Verificação de vendas acima do volume permitido por cliente.
- 🔶 **Segmentação de produtos por preço**: Agrupamento em categorias "baixo", "médio" e "alto valor".
- 🔶 **Vendas por sabor ao longo dos anos**: Análise com CTE e cálculo de percentuais anuais.

---

## 🧪 Como Executar

1. Faça o download ou clone este repositório.
2. Importe o arquivo `ANALISE_DB_SUCOSFRUTAS.sql` no seu banco de dados (recomendado: SQL Server).
3. Execute os blocos de consulta diretamente no ambiente de sua escolha.
4. Explore e edite as queries para realizar outras análises.

---

## 📎 Arquivo

- [`ANALISE_DB_SUCOSFRUTAS.sql`](./ANALISE_DB_SUCOSFRUTAS.sql): Contém todas as queries utilizadas no projeto, incluindo extrações, análises e segmentações.

---

## Tecnologias utilizadas

- SQL (Microsoft SQL Server)

---

## 🚀 Objetivo Final

Este projeto tem como foco demonstrar habilidades práticas em SQL para análise de dados, segmentações, lógica condicional, uso de subqueries e CTEs. Ideal para compor um portfólio de projetos de análise de dados.

---

## 📫 Contato

Caso queira trocar ideias sobre SQL ou projetos de análise de dados, me chame no https://www.linkedin.com/in/56b49515b/

