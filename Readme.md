# Guia para Iniciar a Aplicação

Este arquivo fornece instruções sobre como configurar e executar a aplicação de forma rápida e simples usando Docker e um arquivo de ambiente.

## Pré-Requisitos

- Docker instalado no seu sistema: [Instruções de Instalação do Docker](https://docs.docker.com/get-docker/)
- Docker-compose: [Instruções de Instalação do Docker compose](https://docs.docker.com/compose/install/)
- Arquivo `.env.example` fornecido pela equipe de desenvolvimento.

## Passos para Iniciar a Aplicação

1. **Clonar o Repositório:**

   Clone o repositório da aplicação do GitHub:

   ```bash
   git clone <URL_DO_REPOSITÓRIO>
   cd <NOME_DO_DIRETÓRIO>
   ```

2. **Copiar o Arquivo de Ambiente:**

   Copie o arquivo de ambiente de exemplo `.env.example` para `.env`:

   ```bash
   cp .env.example .env
   ```

3. **Modificar Variáveis de Ambiente (Opcional):**

   Se necessário, modifique as variáveis de ambiente no arquivo `.env` de acordo com os requisitos do seu ambiente.

4. **Executar o Docker Compose:**

   Use o Docker Compose para construir e executar a aplicação:

   ```bash
   docker-compose up -d
   ```

   Isso irá construir as imagens necessárias e iniciar os contêineres da aplicação em segundo plano (`-d`).

5. **Acessar a Aplicação:**

   Uma vez que todos os contêineres estejam em execução, você pode acessar a aplicação a partir do seu navegador web, inserindo a URL apropriada.

6. **Parar a Aplicação (Opcional):**

   Quando terminar de trabalhar com a aplicação, você pode pará-la executando:

   ```bash
   docker-compose down
   ```

   Isso irá parar e remover os contêineres relacionados.

## Contribuição

Se desejar contribuir para este projeto, siga estes passos:

1. Faça um fork do projeto.
2. Crie uma nova branch (`git checkout -b feature/nova-caracteristica`).
3. Faça suas alterações e comite (`git commit -am 'Adiciona uma nova funcionalidade'`).
4. Faça push para a branch (`git push origin feature/nova-caracteristica`).
5. Abra um Pull Request.

## Problemas

Se encontrar algum problema com a configuração ou execução da aplicação, abra um issue no repositório para que possamos ajudá-lo.

Obrigado por utilizar nossa aplicação!
