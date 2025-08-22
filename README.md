# Dashboard de Balancetes – Power BI

Este projeto apresenta um dashboard desenvolvido em Power BI, utilizando conexão ODBC com o banco de dados do sistema contábil **Domínio** (Thomson Reuters), para estruturação e análise de balancetes por empresa, centro de custo e períodos.

## 🎯 Objetivo

Facilitar a visualização e análise de balancetes contábeis, permitindo insights contábeis e fiscais de forma dinâmica e automatizada.

## 🛠️ Tecnologias e Ferramentas

- **Power BI Desktop**
- **Power Query (M)**
- **DAX (medidas, colunas e tabelas calculadas)**
- **Conexão ODBC com sistema Domínio**
- **Modelagem contábil estruturada**

## 📊 Funcionalidades do Dashboard

- Visualização de balancetes por empresa, período e natureza (ativo, passivo, receitas, despesas etc.);
- Hierarquia contábil personalizada por níveis;
- Filtros por centro de custo e contas específicas;
- Indicadores financeiros dinâmicos e personalizáveis.

## 🔒 Segurança e Dados

> **Nota:** Por se tratar de dados contábeis confidenciais, este repositório **não contém os dados reais nem o arquivo `.pbix` completo**. Foram disponibilizados apenas trechos genéricos de código M, medidas e tabelas DAX para fins ilustrativos.

---

## ⚙️ Pré-requisitos técnicos – Conexão com o sistema Domínio

Para que o Power BI se conecte corretamente ao banco de dados via ODBC do sistema contábil **Domínio**, é necessário:

1. Criar um **usuário externo** com permissões específicas  
   🔗 [Tutorial oficial – Domínio](https://suporte.dominioatendimento.com/central/faces/solucao.html?codigo=3227)

2. Configurar uma conexão ODBC no Windows  
   🔗 [Tutorial ODBC no GitHub](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/blob/main/docs/CONEXAO_ODBC.md)

---

## 📷 Capturas de Tela

|[Exemplo 1](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/blob/main/Imagens/Exemplo%201.png) |
|[Exemplo 2](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/blob/main/Imagens/Exemplo%202.png) |

---

## 📑 Códigos Disponíveis

- 🔹 **Código M (Power Query):**  
  [Ver scripts](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/tree/main/scripts_m)

- 🔹 **Medidas DAX:**  
  [Ver medidas](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/tree/main/dax_measures)

- 🔹 **Tabelas DAX (calculadas):**  
  [Ver tabelas](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/tree/main/dax_tables)

- 🔹 **Dashboad:**  
  [Ver dashboard](https://github.com/Ylaros/Dashboard-Balancetes-Power-BI/tree/main/pbit)
---

## ✍️ Autor

**Aloyr Rezende**  
🔗 [LinkedIn](https://www.linkedin.com/in/aloyr-rezende)

