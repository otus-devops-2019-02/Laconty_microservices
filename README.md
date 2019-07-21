# Laconty_microservices
Laconty microservices repository

## Задание 12
#### Docker-1

- Познакомился с докер
- Познакомился основными командами докера

## Задание 13
#### Docker-2

- Создал проект в GCP
- Собрал docker image для reddit приложения
- Запустил docker container в облаке
- Использовал gcp провайдер для docker-machine
- Залил собственный docker-image на docker-hub registry

## Задание 14
#### Docker-3

- Собрал reddit app из разных образов
- Запустил разные образы reddit как микросервисы
- Использовал docker bridge-network

## Задание 15
#### Docker-4

- Запустил разные docker images из прошлого урока с помощью docker-compose.yml
- Использовал environment variables для кастомизации docker-compose
- Задал имя(COMPOSE_PROJECT_NAME)
- Поработал с разными docker network
Ответ на вопрос дз:
Префикс по умолчанию является директория в которой находится файл docker-compose.yml
Чтобы изменить префикс необходимо указать env variable COMPOSE_PROJECT_NAME или аргументов -p при вызове docker-compose


## Задание 16
#### Gitlab-1

- Запустил gcp инстанс,
- На инстансе скачал докер
- Запустил gitlab с помощью docker-compose
- Настроил CI скрипты на каждый коммит в гитлабе
- Создал CI pipeline

## Задание 17
#### Monitoring-1

Ссылка на мой докер хаб https://hub.docker.com/u/laconty
- Запустил prometheus в docker container
- Собирал логи из запущенных сервисов с помощью Prometheus

## Задание 18
#### Monitoring-2

Ссылка на мой докер хаб https://hub.docker.com/u/laconty

- Запустил node-exporter для мониторинга host
- Запустил cadvisor для мониторинга запущенных контейнеров на хосте
- Запустил grafana для отображения логов из prometheus
- Создал dashboard grafana для отображения системных логов, состояния сервисов, и метрики бизнес приложений
- Создал несколько panel для dashboard в grafana для отображения нужных метрик
- Запустил alertmanager для prometheus
- Настроил правило для алертов в alertmanager
- Интегрировал оповещения в слаке для alertmanager

## Задание 19
#### Logging-1

Ссылка на мой докер хаб https://hub.docker.com/u/laconty

- Запустил через docker fluentd для агрегации логов
- Запустил через docker kibana и elasticsearch поиска логов
- Использовал zipking для трейсинга

## Задание 21
#### Kubernetes-2

- Развернуть локальное окружение для работы с Kubernetes
- Развернуть Kubernetes в GKE
- Запустить reddit приложение в Kubernetes

## Задание 22
#### Kubernetes-3

- Создал и использовал PersistentVoumes, PersistentVolumeClaims, StorageClass, Ingress kubernetes объекты
- Управлял Ingress сетью, добавил ssl для балансировщика
