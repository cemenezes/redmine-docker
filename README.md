# redmine-docker
Compose do Redmine 4.1 com MySQL

Arquivos de configuração para utilização do redmine em subdir (/redmine)

 Para utilizar basta copiar os arquivos da seguinte forma:

  docker cp configuration.yml <CONTAINER_ID>:/usr/src/redmine/config/configuration.yml

  docker cp config.ru <CONTAINER_ID>:/usr/src/redmine/config.ru

  docker cp environment.rb <CONTAINER_ID>:/usr/src/redmine/config/environment.rb
