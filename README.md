# Elixir PlayBook

## Índice

* [Sobre o projeto](#sobre-o-projeto)
* [Tecnologias utilizadas](#tecnologia-utilizada)
* [Pré-requisitos](#pré-requisitos)
* [Configuração do ambiente](#configuração-do-ambiente)
* [Como executar](#como-executar)

## Sobre o projeto

Este guia tem como objetivo apresentar as melhores práticas e convenções utilizadas no desenvolvimento de projetos em Elixir com a Arquitetura Phoenix. Através deste material, buscamos padronizar e melhorar a qualidade do código, facilitar a compreensão e colaboração entre os desenvolvedores e, consequentemente, aumentar a eficiência no processo de desenvolvimento.

O guia abrange tópicos como Code Style, estrutura de projetos na Arquitetura Phoenix, nomenclaturas, funções no Repo, uso do "alias", integração com APIs externas e considerações finais. Cada seção detalha as práticas recomendadas e exemplos de código para facilitar a compreensão e aplicação desses conceitos no dia a dia.

Ao seguir as orientações propostas neste guia, você estará contribuindo para a criação de um ambiente de desenvolvimento mais organizado e colaborativo, onde todos os membros da equipe poderão trabalhar de maneira eficiente e consistente.

## Tecnologia utilizada

* [LiveBook](https://livebook.dev/)

## Pré-requisitos

* Ter instalado a o LiveBook ou docker e docker compose
    - [LiveBook](https://livebook.dev/#install)
    - [Docker](https://docs.docker.com/compose/install/)

## Como executar

Depois de configurar o ambiente, siga os passos abaixo para executar o projeto:

Caso tenha optado por instalar o LiveBook em sua máquina siga com essa agordagem, se não pule para a próxima etapa.

```bash
livebook server /notebooks/guia_para_os_devs_elixir_phoenix.livemd
```

Caso tenha optado por utilizar o docker compose siga com estes passos

```bash
docker-compose up -d
```

Depois acesse localhost:8080

autentique com a senha padrão no arquivo `docker-compose.yml`

Aperte em `Open` e selecione o nosso arquivo, em seguida aperte 
`open` novamente e já terá acesso ao nosso PlayBook e poderá utilizar como referência ou até mesmo contribuir com ideias.

