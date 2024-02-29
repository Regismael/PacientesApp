# API de Controle de Pacientes

Esta é uma API ASP.NET para o controle CRUD de pacientes. A API utiliza as bibliotecas Dapper e SqlServer para interação com o banco de dados.

## Funcionalidades

- **CRUD de Pacientes:** A API permite a criação, leitura, atualização e exclusão de registros de pacientes.

## Configuração

### Banco de Dados

Certifique-se de configurar a conexão com o banco de dados SQL Server. Edite o arquivo `appsettings.json` e substitua a chave `ConnectionString` pelo seu valor correspondente.

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "sua_connection_string_aqui"
  },
  // outras configurações...
}
