# Arquitetura baseada em microsserviços usando Spring Cloud
#### Santander Bootcamp Fullstack Developer
 Aprenda na prática como funciona uma arquitetura de software baseada em microsserviços, os seus benefícios e desafios, assim como faremos um projeto em Java com Spring Cloud para você desenvolver o seu portfólio de projetos.
### Pré requisito
Para executar este aplicativo, você precisa instalar duas ferramentas: Docker e Docker Compose.

Instruções de como instalar o Docker no [Ubuntu](https://docs.docker.com/engine/install/ubuntu/), [Windows](https://docs.docker.com/docker-for-windows/install/), [Mac](https://docs.docker.com/docker-for-mac/install/).

Docker Compose já está incluído nos pacotes de instalação para Windows e Mac, portanto, apenas usuários do Ubuntu precisam seguir estas [instruções](https://docs.docker.com/compose/install/).
### Executando Prod
Pode ser executado um único comando no terminal:
~~~
$ docker-compose up -d
~~~
Se você quiser pará-lo, execute o seguinte comando:
~~~
$ docker-compose down
~~~

Irá subir duas instâncias do Elasticsearch e do Redis e em seguida execute o comando abaixo de cada projeto no terminal ou na sua IDE de preferencia:

~~~
$ mvn clean spring-boot:run
~~~

@willyms