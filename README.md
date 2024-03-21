# Lab Quarkus - Desenvolvimento de Aplicações com Quarkus

O Lab Quarkus é uma série de vídeos e interações que abordam o desenvolvimento de uma aplicação utilizando o framework Quarkus. Este projeto tem como objetivo oferecer um guia passo a passo para o desenvolvimento de aplicações modernas e eficientes com Quarkus, cobrindo desde a configuração inicial do ambiente até tópicos avançados como arquitetura de software, integração de sistemas e desafios do mundo real.

## Visão Geral

O Lab Quarkus é dividido em vários vídeos e interações, cada um abordando diferentes aspectos do desenvolvimento de aplicações utilizando Quarkus. Os principais tópicos cobertos incluem:

- Configuração do ambiente de desenvolvimento com SDKMAN! e Docker Compose.
- Discussão sobre arquiteturas de software como Hexagonal, Limpa e Cebola.
- Desenvolvimento de APIs RESTful utilizando Quarkus e padrões de projeto como Domain Model, Service Layer e Repository.
- Utilização de ferramentas e técnicas de testabilidade, incluindo Testcontainers, Test Driven Development (TDD) e Mocking.
- Migração de dados com Flyway e utilização do Hibernate ORM como Data Mapper.
- Implementação de arquiteturas orientadas a eventos com Redis e conceitos como Pub/Sub e Reactive Programming.
- Desafios práticos para explorar diferentes aspectos da aplicação e aprofundar o conhecimento em áreas como métricas, escalabilidade, segurança e modelagem de dados.

## Estrutura do Projeto

- `config/`: Arquivos de configuração da aplicação.
- `src/`: Código-fonte da aplicação.
  - `main/`: Código-fonte principal da aplicação.
    - `java/`: Pacotes Java da aplicação.
    - `resources/`: Recursos da aplicação, como arquivos de configuração.
  - `test/`: Código-fonte de testes da aplicação.
- `docker-compose.yml`: Arquivo de configuração do Docker Compose para gerenciar contêineres de infraestrutura necessários para o ambiente de desenvolvimento.
- `README.md`: Este arquivo, contendo informações sobre o projeto.

## Requisitos de Ambiente

Para executar a aplicação e acompanhar os exemplos do Lab Quarkus, você precisará ter instalado:

- Java JDK (versão especificada no ambiente de desenvolvimento)
- Docker e Docker Compose

Recomenda-se também o uso de uma IDE como IntelliJ para facilitar o desenvolvimento e depuração do código.

## Executando a Aplicação

Para executar a aplicação, siga estes passos:

1. Clone o repositório do Lab Quarkus para sua máquina local.
2. Certifique-se de ter o Docker e Docker Compose instalados.
3. Navegue até o diretório raiz do projeto.
4. Execute `docker-compose up` para iniciar os contêineres de infraestrutura necessários.
5. Importe o projeto em sua IDE preferida.
6. Execute a aplicação a partir da IDE ou utilizando os comandos do Maven/Gradle, conforme descrito nos vídeos do Lab Quarkus.

## Contribuindo

Se você encontrar problemas ou tiver sugestões para melhorar o Lab Quarkus, sinta-se à vontade para abrir uma issue ou enviar um pull request. A contribuição de todos é bem-vinda!

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

---

**Autor:** [Seu Nome/Autor](https://github.com/seu-usuario)

**LinkedIn:** [Seu Perfil no LinkedIn](https://www.linkedin.com/in/seu-perfil)
