**README**

# API em PHP Puro

Este projeto consiste em uma API desenvolvida em PHP puro para manipulação de dados de usuários. A API utiliza um banco de dados em formato JSON para armazenamento e recuperação de informações.

## Estrutura do Projeto

O projeto possui a seguinte estrutura de diretórios e arquivos:

- **config**: Pasta contendo o arquivo de configurações gerais.
  - **config.php**: Arquivo de configurações gerais da API.

- **controller**: Pasta contendo os arquivos de controle da API.
  - **BaseController.php**: Arquivo contendo funções básicas de controle.
  - **UserController.php**: Arquivo contendo funções específicas para manipulação de usuários.

- **model**: Pasta contendo os modelos do banco de dados.
  - **UserModel.php**: Arquivo contendo o modelo de dados para usuários.

- **database.json**: Arquivo contendo os dados do banco de dados em formato JSON.

## Configurações

As configurações gerais da API estão definidas no arquivo `config/config.php`. Neste arquivo, é possível definir parâmetros como o nome do banco de dados, credenciais de acesso e outras configurações relevantes para o funcionamento da API.

## Funcionalidades

A API oferece as seguintes funcionalidades básicas:

- **Cadastro de Usuário**: Permite cadastrar novos usuários no sistema.
- **Consulta de Usuário**: Permite buscar informações de usuários cadastrados.
- **Atualização de Usuário**: Permite atualizar informações de usuários existentes.
- **Remoção de Usuário**: Permite remover usuários do sistema.

## Utilização

Para utilizar a API, siga os seguintes passos:

1. Clone ou baixe este repositório para o seu ambiente de desenvolvimento.
2. Configure as opções necessárias no arquivo `config/config.php`.
3. Execute a API em um servidor web que suporte PHP.
4. Utilize as rotas e métodos disponibilizados pela API para interagir com os dados de usuário conforme necessário.

## Contribuição

Este projeto está aberto a contribuições. Se deseja contribuir, sinta-se à vontade para abrir pull requests ou reportar problemas através das issues.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).