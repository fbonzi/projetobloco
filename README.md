# Projeto de bloco - Deploy GLPI com docker na infraestrutura Amazon AWS

Repositório criado para orientar os estudos, de implementação de uma aplicação web chamada GLPI. Esta ferramenta servirá para gerenciar os chamado de suporte da empresa hipotética, Terra Média LTDA. 

Este repositório contém alguns arquivos que foram utilizados ao longo do processo de conclusão do Projeto de Bloco.


Informações sobre o repositório utilizado para instalação do container GLPI

https://github.com/DiouxX/docker-glpi/edit/master/README.md

Deploy GLPI utilizado 
docker run --name glpi --link yourdatabase:mysql -p 80:80 -d diouxx/glpi

