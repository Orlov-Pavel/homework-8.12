# Домашнее задание к занятию "12.Gitlab"
Файлы:  
[gitlab-CI](./files/.gitlab-ci.yml)  
[Dockerfile](./files/Dockerfile)

## DevOps
Выполненный pipeline:  
![devops-pipeline](./pictures/devops-pipeline.PNG)  
build stage:  
![devops-buildStage](./pictures/devops-buildStage.png)  
deploy stage:  
![devops-deployStage](./pictures/devops-deployStage.png)  
Отрабатывающий curl запрос к серверу:  
![devops-curl](./pictures/devops-curl.PNG)

## Product Owner
Issue создан:  
![productOwner-issue](./pictures/productOwner-issue.PNG)

## Developer
Ветка под issue создана:  
![developer-issue](./pictures/developer-issue.PNG)
Необходимые изменения внесены:  
![developer-changes](./pictures/developer-changes.PNG)  
Merge request создан, сборка прошла успешно:  
![developer-merge](./pictures/developer-merge.PNG)  

## Tester
Контейнер запущен, запрос выполняется успешно:  
![tester-docker](./pictures/tester-docker.PNG)  
Issue закрыта с соответствующим комментарием:  
![tester-issue](./pictures/tester-issue.PNG)

## Необязательная часть
Добавил в [CI](./files/.gitlab-ci.yml) test stage в котором запускает контейнер с собранным образом и выполняется curl к нему.