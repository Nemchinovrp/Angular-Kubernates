Скомпилировать проект - ng build --prod
Готовый файлы попадут в папку /dist

Собрать образ = "docker build -t angular_kubernates ."

docker tag <IMAGE ID> nemchinovrp/angular_kubernates:0.0.1

docker push nemchinovrp/angular_kubernates:0.0.1

Удаление всех образов - "docker system prune -a"
Удаление конкретного образа - docker image rm -f <IMAGE_ID>
