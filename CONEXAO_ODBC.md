# Tutorial – Conexão ODBC com o sistema Domínio (Thomson Reuters)

Este guia explica como configurar uma fonte de dados ODBC para se conectar ao banco de dados do sistema Domínio e utilizá-lo em ferramentas como Power BI, Excel ou Python.

## 🔧 Pré-requisitos

- Sistema Domínio instalado
- Usuário externo criado (veja o [tutorial oficial](https://suporte.dominioatendimento.com/central/faces/solucao.html?codigo=3227))
- Permissões administrativas no Windows

## 🛠️ Passo a passo

### 1. Acesse o Gerenciador ODBC
- No Windows, pesquise por **“Fonte de Dados ODBC (64 bits)”** e abra.

### 2. Crie uma nova fonte de dados (DSN)
- Vá na aba **“DSN de Sistema”**
- Clique em **Adicionar**
- Selecione o driver **SQL Anywhere 17** (ou similar)

### 3. Preencha os dados da conexão

| Campo             | Exemplo                  |
|------------------|--------------------------|
| DSN              | DominioDB                |
| User ID          | usuario_externo          |
| Password         | ********                 |
| Server Name      | DOMINIO                  |
| Database Name    | DOMINIO.db               |

> ⚠️ A linha de comando de inicialização pode ser necessária em alguns ambientes (ex: `dbsrv17 -n DOMINIO "C:\Domínio\Banco\DOMINIO.db"`)

### 4. Teste a conexão
- Clique em **Test Connection**
- Se aparecer “Connection successful”, está pronto!

### 5. Usar no Power BI
- Vá em **Obter Dados > ODBC**
- Escolha o DSN criado (ex: `DominioDB`)
- Navegue pelas tabelas do banco (como `eflancam`, `efbalancete`, etc.)

## 📂 Sugestão de tabelas úteis

| Tabela              | Descrição                                    |
|---------------------|-----------------------------------------------|
| `eflancam`          | Lançamentos contábeis                        |
| `efplancon`         | Plano de contas                              |
| `efempresas`        | Dados cadastrais das empresas                |
| `efbalancete`       | Balancetes e saldos por conta/período        |
| `audados`           | Informações auxiliares                       |

## 📥 Drivers ODBC

Se o driver **SQL Anywhere** não estiver disponível, baixe e instale pelo site oficial da SAP:

🔗 [Download do SQL Anywhere Client – SAP](https://support.sap.com/sap/support/knowledge/en/2181084)

## 🧠 Observações

- Evite expor usuários/senhas em repositórios públicos
- Use conexões apenas para **leitura de dados**
- Testado com Power BI Desktop e Excel

---

📌 Criado por **Aloyr Rezende**
