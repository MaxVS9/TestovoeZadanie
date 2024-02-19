Для запуска приложения требуется скопировать проект, перейти по пути /project-dir/src и выполнить следующие действия:<br />
переименовать .env.exapmle на .env
docker-compose ud -d <br />
docker-compose run composer install <br />
docker-compose run php npm install <br />
docker-compose run artisan key:generate <br />
Перейти в браузере по адресу localhost:8000 <br />
