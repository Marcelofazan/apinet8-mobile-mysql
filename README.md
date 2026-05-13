## WebAPI-Mobile-MySQL
Exemplo de criação CRUD WebAPI com banco de dados MySQL utilizando Dapper.

### O que você vai encontrar neste projeto
- **Dapper** - Utilização de mapeamento rápido de resultados de consultas SQL diretas pela aplicação.
- **Resource** - Armazenar dados de maneira estruturada

### Execução da aplicação
Para executar a aplicação é necessário a execução do Script do MySQL em Hospedagem Online.  

### String de conexão do banco
Modifique a string de conexão no arquivo appsettings.json, no trecho indicado:

```json 
 "server=[SEUSERVIDOR];userid=[SEUUSUARIO];password=[SUASENHA];database=[SEUBANCO];persistsecurityinfo=True;"
 ```
 
O script para criação da tabela do exemplo encontra-se na pasta Database.

Obs: Vinculado ao exemplo 
Executa a aplicação Frontend **AppMobile-MAUI-Login-Pessoa** que se encontra no Github.

  - [AppMobile-MAUI-Login-Pessoa](https://github.com/Marcelofazan/appmob-maui-login-pessoa)
