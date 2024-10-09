# Projeto Brasileirão API

Este projeto é uma API simples que retorna uma tabela estática do Brasileirão durante algum momento da temporada.

## Como Rodar o Projeto

1. Clone o repositório:
    ```bash
    git clone <URL_DO_REPOSITORIO>
    cd <NOME_DO_REPOSITORIO>
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Inicie a aplicação:
    ```bash
    npm start
    ```

## Deploy Automático com DigitalOcean

Este projeto possui uma automação com DigitalOcean que realiza o deploy automático sempre que a branch `main` é atualizada. Existem duas formas de deploy:

### 1. App Platform

A App Platform da DigitalOcean faz todo o processo de deploy automaticamente. Basta configurar o repositório no painel da DigitalOcean e qualquer atualização na branch `main` será automaticamente implantada.

### 2. Droplet com GitHub Actions

Neste caso, a DigitalOcean fornece uma VPS (Droplet) e o deploy é feito através do GitHub Actions. A configuração do GitHub Actions deve incluir os passos necessários para acessar a VPS e realizar o deploy da aplicação.

Certifique-se de adicionar as chaves SSH necessárias nos segredos do repositório no GitHub.

## Contribuição

Sinta-se à vontade para abrir issues e enviar pull requests. Toda contribuição é bem-vinda!
