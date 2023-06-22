# Motivação do Projeto / Desafio da Full Cycle: Subir a Imagem Docker para o Docker Hub
Neste projeto/desafio da Full Cycle, o objetivo é subir uma imagem Docker para o Docker Hub. Essa tarefa é fundamental para permitir que outros desenvolvedores e membros da comunidade tenham acesso e possam utilizar a imagem em seus projetos.

A motivação por trás dessa atividade está na necessidade de compartilhar soluções de software de maneira eficiente e escalável. O Docker é uma ferramenta poderosa que permite criar e compartilhar containers isolados, contendo todas as dependências necessárias para a execução de um aplicativo. Ao disponibilizar uma imagem Docker no Docker Hub, é possível fornecer uma solução pronta para uso, reduzindo a complexidade de configuração e instalação para outros desenvolvedores.

## Desafio
O desafio consiste em criar uma imagem Docker contendo uma aplicação ou serviço específico e, em seguida, fazer o upload dessa imagem para o Docker Hub. Para isso, é necessário seguir os seguintes passos:

1. Criar um arquivo de configuração Dockerfile que defina como construir a imagem Docker.
2. Configurar corretamente o ambiente e as dependências necessárias dentro do Dockerfile.
3. Construir a imagem Docker localmente utilizando o comando docker build.
4. Verificar se a imagem está funcionando corretamente executando-a localmente com o comando docker run.
5. Fazer o login no Docker Hub utilizando o comando docker login.
6. Fazer o upload da imagem para o Docker Hub utilizando o comando docker push.

Ao concluir esses passos, a imagem estará disponível no Docker Hub, pronta para ser utilizada por outras pessoas. Isso facilita a distribuição e utilização de soluções baseadas em containers, além de promover a colaboração e o compartilhamento de conhecimento na comunidade de desenvolvedores.

O projeto/desafio da Full Cycle de subir a imagem Docker para o Docker Hub é uma oportunidade valiosa para aprender e praticar habilidades relacionadas ao uso do Docker e à distribuição de software em containers. Essa atividade permite explorar as vantagens oferecidas pelo Docker Hub, que é uma plataforma centralizada para armazenar, gerenciar e compartilhar imagens Docker.

Com isso, os participantes têm a oportunidade de aprimorar suas habilidades em Docker e contribuir para a disseminação de soluções de software inovadoras, tornando-se parte de uma comunidade ativa e colaborativa de desenvolvedores.

## Como Usar

1. Primeiro é necessário baixar e/ou da o pull na imagem

   ```bash
        docker pull sport129/fullcycle-desafio-docker:1.0.0 ou
        docker run sport129/fullcycle-desafio-docker:1.0.0
   ```

2. Como executar
   2.1. Caso tenha dado o comando docker run, o que é retornado já é o resultado esperado
   2.2. Caso só tenha dado o pull é necessário rodar o comando abaixo

     ```bash
         docker run sport129/fullcycle-desafio-docker:1.0.0
      ```

## Docker Hub Link

Link [dockerhub](https://hub.docker.com/layers/sport129/fullcycle-desafio-docker/1.0.0/images/sha256-79f7ef249c912c5836c76bb2279a36746334513628d8fdb5e502785eee4e66a1?context=repo)