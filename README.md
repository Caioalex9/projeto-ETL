Projeto ETL com Arquitetura Medalhão

Este projeto foi desenvolvido para praticar o conceito de ETL (Extract, Transform, Load) aplicado à Arquitetura Medalhão — dividindo os dados nas camadas Bronze, Silver e Gold.

O objetivo é mostrar todo o processo de extração de APIs, limpeza dos dados e criação de análises de negócio com Python e Pandas. 🚀

🎯 Objetivo do Projeto

Construir um pipeline completo de ETL que:

🔹 Extrai dados de 3 APIs (usuários, produtos e carrinhos)

🔹 Organiza os dados em camadas (Bronze → Silver → Gold)

🔹 Realiza transformações e limpezas

🔹 Gera análises e métricas de negócio

🔹 Deixa os dados prontos para dashboards e relatórios

⚙️ Tecnologias Utilizadas

🐍 Python 3

🧮 Pandas

☁️ Requests

📊 Jupyter Notebook

💾 CSV / JSON

🧱 Estrutura da Arquitetura Medalhão
Camada	Nome	Descrição
🥉	Bronze (Raw)	Dados brutos, extraídos diretamente das APIs
🥈	Silver (Clean)	Dados limpos e padronizados (textos, tipos, duplicatas)
🥇	Gold (Analytics)	Dados agregados e prontos para análise de negócio

Fluxo: API → Bronze → Silver → Gold

📊 Principais Métricas Calculadas

💰 Total de vendas

🧾 Ticket médio

📦 Produtos vendidos

👥 Usuários ativos

🏆 Top produtos e categorias

📁 Estrutura de Pastas
dados/
├── bronze/
│   ├── products.json
│   ├── users.json
│   └── carts.json
├── silver/
│   ├── produtos.csv
│   ├── usuarios.csv
│   └── carrinhos.csv
└── gold/
    ├── resumo_negocio.csv
    └── analises.csv

🚀 Como Rodar o Projeto

Clone o repositório:


Instale as dependências:

pip install pandas requests jupyter


Execute o notebook no Jupyter:

jupyter notebook


Rode todas as células do notebook e veja os resultados na pasta gold/.

💡 Aprendizados

Durante o projeto, aprendi sobre:

O conceito de Arquitetura Medalhão

Como estruturar camadas de dados (bruto, limpo e analisado)

Manipulação e transformação de dados com Pandas

Organização de código e documentação em Notebooks

✨ Resultado Final

✅ Projeto ETL completo com 3 APIs
✅ Dados limpos e padronizados
✅ 8+ análises de negócio
✅ Documentação em notebook
