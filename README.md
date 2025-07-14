# Dashboard de Balancetes – Power BI

Este projeto apresenta um dashboard desenvolvido em Power BI, utilizando conexão ODBC com o banco de dados do sistema contábil **Domínio** (Thomson Reuters), para estruturação e análise de balancetes por empresa, centro de custo e períodos.

## 🎯 Objetivo

Facilitar a visualização e análise de balancetes contábeis, permitindo insights contábeis e fiscais de forma dinâmica e automatizada.

## 🛠️ Tecnologias e Ferramentas

- **Power BI Desktop**
- **Power Query (M)**
- **DAX**
- **Conexão ODBC com banco Domínio**
- **Modelagem contábil estruturada**

## 📊 Funcionalidades do Dashboard

- Visualização de balancetes por empresa, período e natureza (ativo, passivo, receitas, despesas etc.);
- Hierarquia contábil personalizada por níveis;
- Filtros por centro de custo e contas específicas;
- Indicadores financeiros dinâmicos e personalizáveis.

## 🔒 Segurança e Dados

> **Nota:** Por se tratar de dados contábeis confidenciais, este repositório **não contém os dados reais nem o arquivo `.pbix` completo**. Foram disponibilizados apenas trechos de código M e fórmulas DAX genéricas para fins ilustrativos.

## ⚙️ Pré-requisitos técnicos – Conexão com o sistema Domínio

Para que o Power BI se conecte corretamente ao banco de dados via ODBC do sistema contábil **Domínio (Thomson Reuters)**, é necessário criar um **usuário externo com permissão de acesso à base de dados**.

O passo a passo completo pode ser encontrado neste artigo oficial da Domínio:

👉 [Como criar usuário externo no sistema Domínio](https://suporte.dominioatendimento.com/central/faces/solucao.html?codigo=3227)

> Importante: este procedimento deve ser feito por um administrador do sistema Domínio, com atenção às permissões de acesso à base de dados utilizadas nas consultas.

Após a criação do usuário, é necessário fazer uma conexão ODBC com o banco de dados.
Siga abaixo como fazer

👉 [https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/blob/main/CONEXAO_ODBC.md]



## 📂 Estrutura deste repositório

Dashboard-Balancetes-Power-BI/
├── README.md
├── docs/
│   ├── CONEXAO_ODBC.md
│   ├── Código M
│   └── medidas_dax.txt
├── imagens/
│   └── Exemplos.png


## 📷 Capturas de tela

![Exemplo de visualização](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/blob/main/Exemplo%201.png)
![Exemplo de visualização](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/blob/main/Exemplo%202.png)


## Códigos 

👉 [https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/tree/main/C%C3%B3digo%20M]



## ✍️ Autor

Aloyr Rezende – [LinkedIn](https://www.linkedin.com/in/aloyr-rezende)



