# jenkins-login-auto
aplicação jenkins com autentificação automatizada

Realizar o clone do repositorio.

Dentro do repositório, rodar o comando:

docker image build -t jppaiva/jenkins .

Em seguida, rodar o comando:

docker stack deploy -c jenkins.yml jenkins
