# Docker com centos 7
docker elaborado com crawler do https://br.investing.com/

valores com tabelas em real e dolar

comando inicial 

docker-compose up -d

# Elastic
instalado dentro do docker
necessario entrar dentro do docker

docker -it "codigo do conatiner" /bin/bash

systemctl start elasticsearch

crontab -e
*/2 * * * * /bin/bash /home/luis.filho/bin/init.sh

necessario alterar as configurações no elasticsearch.yml

cp elasticsearch.yml /etc/elasticsearch/elasticsearch.yml

*substituir

# Kibana
imagem rpm 7.6.2

para acessar localhost:5601

# Logstash
imagem rpm 7.6.2
