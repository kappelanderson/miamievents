# Miami Events

O Miami Events é um projeto desenvolvido em Laravel e PHP com o objetivo de informar os eventos próximos de Miami. Os usuários cadastrados podem confirmar presença em eventos existentes e também criar novos eventos.

## LIVE: 

## Requisitos

- PHP 7.4 ou superior
- Composer
- Laravel 8.x

## Instalação

1. Clone o repositório do projeto do GitHub:

   ```bash
   git clone https://github.com/seu-usuario/miami-events.git
   
2. Acesse o diretório do projeto:

cd miami-events

3. Instale as dependências do projeto via Composer:

composer install

4. Crie o arquivo de ambiente:

cp .env.example .env

5. Gere a chave de criptografia do Laravel:

php artisan key:generate

6. Configure as informações de conexão do banco de dados no arquivo .env.

7. Execute as migrações do banco de dados para criar as tabelas necessárias:

php artisan migrate

8. Inicie o servidor de desenvolvimento:

php artisan serve


## Configuração

O projeto "Miami Events" possui algumas configurações adicionais que você pode personalizar. Para isso, abra o arquivo .env no diretório raiz do projeto e faça as alterações necessárias.

## Guia do Usuário

- Faça o cadastro no sistema ou faça login com suas credenciais existentes.
- Na página inicial, você verá uma lista de eventos próximos de Miami.
- Para confirmar presença em um evento, clique no botão "Confirmar Presença".
- Para criar um novo evento, acesse a página de criação de eventos e preencha as informações necessárias.

## Referências

- Laravel Documentation
- PHP Documentation
- GitHub Repository



