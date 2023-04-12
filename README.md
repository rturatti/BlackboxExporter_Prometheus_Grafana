# Observabilidade_BlackBox_Exporter
Repositório do Blackbock junto com Prometheus e Grafana

## Instruções de uso

Para iniciar os containers utilize o comando abaixo. \n
`docker-compose up -d`

Será inicializado os containers, para acessar o Grafana acesso via `http://localhost:3000` com usuário **admin** e a senha **Grafana123**.

Para acessar o Prometheus acesse `http://localhost:9090`.
Para acessar o BlackBox acesse `http://localhost:9115`.

## Configuração do BlackBox
A configuração fica dentro da pasta `blackbox_exporter` e as urls de consulta dentro da pasta `prometheus/etc/`.

