# jenkins-login-auto
 ###### Aplicação jenkins com autentificação automatizada

1 - Realizar o clone do repositorio. Dentro do repositório, rodar o comando:

> docker image build -t jppaiva/jenkins .

Em seguida, rodar o comando:

> docker stack deploy -c jenkins.yml jenkins

Para teste, copiar e colar no navegador o endereço:

> http://localhost:8080

Aparecerá o painel do jenkins sem necessidade de login.
