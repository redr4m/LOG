# Лабораторная работа по логированию и мониторингу

Пользователь: red21  
Сервер: 178.154.195.14

## Что сделано
- запущен Prometheus
- подключен node_exporter
- запущено приложение demo-prometeus-app
- приложение добавлено в Prometheus как target
- настроены alerts
- запущены Grafana, Loki и Promtail
- добавлены источники данных в Grafana
- импортирован dashboard Node Exporter Full
- добавлены панели с метриками и логами

## Файлы
- prometheus.yml
- alerts.yml
- grafana-docker-compose.yml
- loki-config.yaml
- promtail-config.yaml
- app-docker-compose.yml


Для приложения использован внешний порт 8121, так как порт 8021 был занят, и мне преподаватель разрешил спользовать этот
