# Banco de dados 
![Captura de tela 2023-12-04 171914](https://github.com/sejaumbu/bancoDeDados/assets/119820823/2844dd97-268f-4b70-901a-c02fc117e556)

# UmSite

## Descrição

O projeto umsite(Umbu) é um sistema de gerenciamento para um site de jardinagem. Este repositório contém o banco de dados MySQL com 8 tabelas e uma API que oferece operações CRUD para interagir com esses dados.

## Requisitos

1. **Servidor MySQL:**
   - Versão 5.7 ou superior.

2. **Cliente MySQL:**
   - MySQL Command-Line Client versão 5.7 ou superior.

3. **Sistema Operacional:**
   - Compatível com Windows, Linux e macOS.

4. **Dependências:**
   - [Lista de dependências, se aplicável]

5. **Configuração do Ambiente:**
   - Antes de iniciar, certifique-se de configurar as seguintes variáveis de ambiente:
     - `MYSQL_HOST`: Endereço do servidor MySQL.
     - `MYSQL_USER`: Nome de usuário do MySQL.
     - `MYSQL_PASSWORD`: Senha do usuário do MySQL.
     - ...

## Uso

1. **Conectar ao Servidor MySQL:**
   - Utilize o comando abaixo para se conectar ao servidor MySQL, substituindo `username` por umsite.

   ```sql
   mysql -u username -p
   
## Exemplo de uso

CREATE TABLE usuario (
  idusuario INTEGER UNSIGNED NOT NULL AUTO_INCREMENT,
  nome VARCHAR(150) NULL,
  endereco INTEGER UNSIGNED NULL,
  numeroimovel INTEGER UNSIGNED NULL,
  cep VARCHAR(10) NULL,
  telefone VARCHAR(50) NULL,
  email VARCHAR(25) NULL,
  data_nascimento DATE NULL,
  cpf VARCHAR(15) NULL,
  data_registro DATE NULL,
  historico VARCHAR(150) NULL,
  preferencias VARCHAR(150) NULL,
  senha VARCHAR(255) NULL,
  PRIMARY KEY(idusuario)
);

