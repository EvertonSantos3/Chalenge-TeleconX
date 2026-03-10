## Telecon X
📊 Análise de Evasão de Clientes (Churn) – Telecom X
📌 Descrição do Projeto

Este projeto tem como objetivo analisar o fenômeno de evasão de clientes (Churn) em uma empresa fictícia de telecomunicações chamada Telecom X.

A análise busca identificar padrões e fatores associados ao cancelamento de clientes, utilizando técnicas de limpeza de dados, análise exploratória e visualização de dados com Python.

Os insights obtidos podem ajudar a empresa a desenvolver estratégias para melhorar a retenção de clientes e reduzir a taxa de cancelamento.

🎯 Objetivos da Análise

Compreender a distribuição de clientes que cancelaram o serviço.

Identificar variáveis associadas ao churn.

Analisar padrões em variáveis categóricas e numéricas.

Gerar insights que possam auxiliar na redução da evasão de clientes.

🗂 Estrutura do Projeto
telecom-churn-analysis
│
├── notebooks/
│   └── TelecomX_BR.ipynb
└── README.md

Descrição:

notebooks/ → Notebook contendo todo o processo de análise

README.md → Documentação do projeto

⚙️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes ferramentas:

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📥 Instalação

Para executar este projeto em sua máquina, siga os passos abaixo.

1️⃣ Clone o repositório
git clone https://github.com/EvertonSantos3/Chalenge-TeleconX
2️⃣ Acesse a pasta do projeto
cd TelecomX_BR.ipynb
3️⃣ Instale as dependências
pip install pandas numpy matplotlib seaborn jupyter
▶️ Como Executar o Projeto

Abra o Jupyter Notebook

jupyter notebook

Navegue até a pasta notebooks

Abra o arquivo

TelecomX_BR.ipynb

Execute as células do notebook para reproduzir toda a análise.

🧹 Limpeza e Tratamento de Dados

Durante a preparação dos dados foram realizadas as seguintes etapas:

Importação de dados em formato JSON

Conversão para DataFrame

Normalização de estruturas JSON aninhadas

Verificação de valores ausentes

Verificação de duplicidades

Conversão de variáveis para tipos adequados

Criação de novas variáveis derivadas (como Contas_Diarias)

Padronização de dados categóricos

Essas etapas garantem que os dados estejam consistentes e adequados para análise.

📊 Análise Exploratória de Dados

Foram realizadas diversas análises para entender o comportamento dos clientes.

Principais análises realizadas:

Distribuição do Churn

Visualização da proporção de clientes que permaneceram e dos que cancelaram.

Análise por Variáveis Categóricas

Exploração da relação entre churn e variáveis como:

Gênero

Tipo de contrato

Método de pagamento

Tipo de serviço

Análise por Variáveis Numéricas

Comparação de métricas como:

Tempo de permanência do cliente

Valor mensal pago

Total gasto pelo cliente

Gráficos como boxplots e histogramas foram utilizados para identificar padrões.

🔎 Principais Insights

A análise revelou alguns padrões importantes:

Clientes com contratos mensais apresentam maior taxa de cancelamento.

Cancelamentos ocorrem com maior frequência nos primeiros meses de contrato.

Clientes que utilizam menos serviços adicionais apresentam maior probabilidade de churn.

Clientes com maior tempo de relacionamento tendem a permanecer na empresa.

Esses fatores indicam que engajamento e fidelização do cliente são determinantes para retenção.

💡 Recomendações

Com base nos resultados da análise, algumas estratégias podem ajudar a reduzir a evasão:

Incentivar contratos de longo prazo

Melhorar a experiência inicial do cliente

Oferecer pacotes de serviços adicionais

Implementar modelos preditivos de churn

Fortalecer suporte técnico e atendimento

Essas ações podem contribuir para aumentar a retenção e melhorar a satisfação dos clientes.

🚀 Possíveis Melhorias Futuras

Este projeto pode ser expandido com:

Criação de modelos de Machine Learning para previsão de churn

Construção de dashboards interativos em Power BI ou Tableau

Implementação de pipeline de dados automatizado

Deploy do modelo em ambiente de nuvem (Azure ou AWS)

👨‍💻 Autor

Projeto desenvolvido por Everton como parte de estudos em Análise de Dados e Ciência de Dados.
