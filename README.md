# Telecom X - Análise de Evasão de Clientes

## 🚀 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio de Data Science da Alura, com o objetivo de analisar a evasão de clientes (churn) na empresa fictícia Telecom X. A empresa enfrenta um alto índice de cancelamentos e, através da análise de dados, buscamos identificar os principais fatores que levam os clientes a deixarem a companhia.

A análise foi realizada utilizando Python e suas principais bibliotecas de manipulação e visualização de dados, seguindo um processo de ETL (Extração, Transformação e Carga) e Análise Exploratória de Dados (EDA).

## 🛠️ Atividades Realizadas

-   **Extração de Dados:** Os dados foram carregados diretamente de uma API em formato JSON, disponibilizada para o desafio.
-   **Transformação e Limpeza:** Os dados foram convertidos para um DataFrame do Pandas, onde foram tratados valores ausentes e normalizados para a análise.
-   **Análise Exploratória de Dados (EDA):** Foi realizada uma análise descritiva e comparativa para identificar padrões e tendências no comportamento dos clientes que evadiram em comparação com os que permaneceram.
-   **Visualização de Dados:** Foram criadas visualizações para ilustrar as descobertas e facilitar a compreensão dos insights.

## 📊 Principais Resultados e Insights

A análise dos dados de 7.267 clientes revelou que aproximadamente **25.7%** deles evadiram. As principais características dos clientes que cancelaram o serviço são:

-   **Tempo de Contrato (Tenure):** Clientes com contratos mais curtos, especialmente os mensais, têm uma probabilidade significativamente maior de evadir.
-   **Serviço de Internet:** A maioria dos clientes que evadiram utilizava o serviço de **Fibra Óptica**.
-   **Método de Pagamento:** O pagamento via **cheque eletrônico** é predominante entre os clientes que cancelaram.
-   **Serviços Adicionais:** Clientes que evadiram tendem a contratar menos serviços de proteção e suporte, como *Online Security*, *Online Backup*, *Device Protection* e *Tech Support*.
-   **Gastos:** Clientes que evadiram possuem uma média de gastos mensais ligeiramente maior, mas um gasto total consideravelmente menor, reforçando a observação sobre o menor tempo de contrato.
-   **Perfil Demográfico:** Clientes sem parceiro(a) ou dependentes apresentaram maior propensão a evadir.

## 💡 Recomendações Estratégicas

Com base nos insights gerados, as seguintes ações são recomendadas para a Telecom X reduzir a taxa de churn:

1.  **Criação de Planos de Longo Prazo:** Incentivar a adesão a contratos anuais ou bianuais com benefícios e descontos atrativos.
2.  **Oferta de Pacotes (Bundles):** Criar pacotes de serviços que agreguem valor, combinando internet com serviços de segurança, backup e suporte técnico.
3.  **Foco na Retenção de Clientes de Risco:** Desenvolver campanhas de retenção direcionadas para clientes com contratos mensais e que utilizam fibra óptica.
4.  **Incentivo a Pagamentos Automáticos:** Oferecer benefícios para clientes que optarem por formas de pagamento automáticas, como débito em conta ou cartão de crédito.
5.  **Programas de Fidelidade para Famílias:** Criar ofertas especiais para clientes com parceiros e dependentes, que se mostraram mais leais à empresa.

## 💻 Tecnologias Utilizadas
-   **Python 3.x**
-   **Pandas:** para manipulação e análise dos dados.
-   **Matplotlib / Seaborn:** para visualização de dados.
-   **Jupyter Notebook:** como ambiente de desenvolvimento para a análise.
## ⚙️ Como Rodar o Projeto
Siga os passos abaixo para executar o projeto localmente.
### Pré-requisitos
É necessário ter o Python 3 instalado em sua máquina.
### Instalação
1.  Clone o repositório:
    ```sh
    git clone [https://github.com/seu-usuario/challenge2-data-science.git](https://github.com/seu-usuario/challenge2-data-science.git)
    ```
2.  Navegue até o diretório do projeto:
    ```sh
    cd challenge2-data-science
    ```
3.  (Opcional, mas recomendado) Crie e ative um ambiente virtual:
    ```sh
    python -m venv venv
    # Windows
    .\venv\Scripts\activate
    # Linux / macOS
    source venv/bin/activate
    ```
4.  Instale as dependências necessárias:
    ```sh
    pip install pandas matplotlib seaborn jupyter
    ```
### Execução

1.  Certifique-se de que o arquivo `TelecomX_Data.json` está no mesmo diretório do seu script ou notebook.
2.  Inicie o Jupyter Notebook:
    ```sh
    jupyter notebook
    ```
3.  Abra o arquivo `.ipynb` que contém a análise e execute as células.
