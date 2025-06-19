# Projeto Telecom X: Análise de Evasão de Clientes

Este projeto tem como objetivo analisar os dados de clientes da Telecom X para identificar os principais fatores que levam à evasão de clientes (churn). Através da análise exploratória dos dados e visualizações, buscamos compreender o comportamento dos clientes e propor sugestões para reduzir a taxa de evasão.

## Estrutura do Projeto e Organização dos Arquivos

A estrutura do repositório está organizada da seguinte forma:
```
.
├── .git/
├── .gitattributes
├── analise_telecon_x
├── LICENSE
└── README
```

Descrição dos Itens:

`.git/`: Este diretório oculto é essencial para o Git. Ele contém todo o histórico do seu projeto, incluindo commits, branches e tags. É onde o Git armazena todas as informações necessárias para gerenciar as versões do seu código.

`.gitattributes`: Um arquivo de configuração do Git que permite definir atributos para caminhos específicos. Ele pode ser usado para coisas como normalização de line endings, definição de drivers de merge ou para marcar arquivos binários.

`analise_telecon_x`: Parece ser um arquivo específico do seu projeto, possivelmente contendo dados ou scripts relacionados a uma análise de telecomunicações. O nome sugere que ele pode ser um arquivo de dados, um notebook (como Jupyter), ou um script.

`LICENSE`: Este arquivo especifica os termos sob os quais seu projeto pode ser usado, modificado e distribuído. É crucial para projetos de código aberto, pois informa aos usuários e colaboradores sobre seus direitos e responsabilidades.

`README`: Um arquivo de documentação fundamental. Ele geralmente fornece uma visão geral do projeto, instruções de instalação, exemplos de uso, informações de contribuição e quaisquer outros detalhes importantes que novos usuários ou colaboradores precisam saber para começar.

## Exemplos de Gráficos e Insights Obtidos

Durante a análise, foram gerados diversos gráficos para visualizar a relação entre diferentes variáveis e a evasão de clientes. Alguns dos insights obtidos incluem:

- **Senioridade:** Clientes idosos possuem uma taxa de evasão superior à média.
- **Tempo de Contrato (Tenure):** Clientes com menor tempo de contrato apresentam maior propensão à evasão.
- **Serviço de Internet:** Clientes que utilizam Fibra Ótica demonstram uma taxa de evasão maior.
- **Tipo de Contrato:** Contratos mensais estão associados a uma maior taxa de evasão.
- **Método de Pagamento:** O método de pagamento "Cheque Eletrônico" apresenta uma taxa de evasão superior.
- **Gasto Mensal:** Clientes com gastos mensais mais altos tendem a evadir mais.

A análise detalhada e os gráficos correspondentes podem ser encontrados no notebook principal.

## Estrutura do notebook
O notebook `analise_telecon_x.ipynb` está estruturado nas seguintes seções:

1.  **Extração:** Carregamento dos dados a partir de uma URL e normalização da estrutura JSON.
2.  **Transformação:** Limpeza e tratamento dos dados, incluindo a conversão de tipos, padronização de strings, tratamento de valores ausentes/vazios, renomeamento e tradução de colunas e termos, e a criação da coluna `contas_diarias`.
3.  **Carga e Análise:** Realização de análises estatísticas descritivas e criação de visualizações utilizando a biblioteca Plotly para explorar a relação entre diversas variáveis e a evasão de clientes.
4.  **Relatório Final:** Resumo das descobertas, insights e sugestões baseadas na análise.

## Instruções para Executar o Notebook

Para replicar a análise e visualizar os resultados, siga os passos abaixo:

1. **Clone o repositório:**
`git clone https://github.com/LucasEstevesCosta/challenge-telecom_x-analise_evasao_clientes.git`

2. Navegue até o diretório do projeto:
`cd challenge-telecom_x-analise_evasao_clientes`

3. Instale as dependências:
`pip install pandas numpy requests plotly`

4. Abra o notebook: Abra o arquivo analise_telecon_x.ipynb em um ambiente compatível com Jupyter Notebooks (como Google Colab, Jupyter Notebook, JupyterLab, etc.).

5. Execute as células: Execute as células do notebook sequencialmente para carregar os dados, realizar as transformações e gerar as visualizações.
