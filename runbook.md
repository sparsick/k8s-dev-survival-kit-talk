# Runbook for Demo

## Demo 1 - Local Application Testing with Docker Compose

```shell
cd sample-app
bat docker-compose.yml
docker compose up
browser http://localhost/hero
docker compose up database

# new terminal
bat pom.xml
mvn spring-boot:run
browser http://localhost:8080/hero
```

## Demo 2 - Spring Boot Docker Compose Support
```shell
cd sample-app
bat pom.xml
mvn spring-boot:run -Pspring31
browser http://localhost:8080/hero
```

## Demo 3 - Develop Helm Charts Locally
```shell
minikube start --nodes=2 --addons=ingress,dashboard
minikube dashboard

# new terminal
cd sample-app/deployment/helm-charts
tree
bat local-values.yaml
helm upgrade -i spring-boot-demo-instance spring-boot-demo -f local-values.yaml
minikube ip
cat /etc/hosts
browser http://spring-boot-demo.local/hero
```

## Demo 4 - kubectl
```shell
kubectl get po
kubectl logs <pod name>
```

## Demo 5 - k9s
