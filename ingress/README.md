# Ingress NGINX

В Kubernetes-кластере используется ingress-nginx в качестве ingress-контроллера.

Ingress-контроллер установлен в namespace `ingress-nginx` стандартным способом (через официальный манифест / Helm chart).

В рамках дипломного проекта ingress-nginx используется для:
- маршрутизации HTTP-трафика к приложениям
- работы Ingress-ресурсов приложений

