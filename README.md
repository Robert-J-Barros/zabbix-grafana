# aws-zabbix
# Projeto de Monitoramento com Grafana e Zabbix

Este repositório contém arquivos de configuração e scripts para construir imagens Docker para Grafana e Zabbix.

![painel grafana](https://bcri-logo.s3.sa-east-1.amazonaws.com/paine-grafana.png)

## Pré-requisitos

Certifique-se de ter o Docker instalado na sua máquina. Você pode verificar a instalação do Docker com o comando:

```sh
docker --version

```
```sh
cd granfana.conf && docker build -t grafana:1.0 .
cd zabbix.conf && docker build -t zabbix:1.3 .
````
````sh
cd zabbix.conf/ && touch aws-config aws-credentials
````

