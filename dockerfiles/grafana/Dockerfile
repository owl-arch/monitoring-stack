FROM grafana/grafana-enterprise
#FROM grafana/grafana
# Linux Alpine 3.17.3 with Grafana

LABEL maintainer="marcos.antonio.carvalho@gmail.com"
LABEL version="1.0"

## ENV grafana_version 0.x.x

# Setting para Grafana
ENV GF_SECURITY_ADMIN_USER     admin
ENV GF_SECURITY_ADMIN_PASSWORD owl
ENV GF_INSTALL_PLUGINS         grafana-piechart-panel,agenty-flowcharting-panel,grafana-clock-panel,grafana-simple-json-datasource,grafana-worldmap-panel,percona-percona-app,camptocamp-prometheus-alertmanager-datasource,vonage-status-panel

#,rabbitmq_prometheus

# Configure o ponto de entrada, isso garante que o pyenv seja inicializado quando um contêiner é iniciado
# e que quaisquer arquivos compilados de etapas anteriores ou de montagens sejam removidos para evitar
# pytest falhando com um ImportMismatchError
#ENTRYPOINT [ "./run.sh" ] 



