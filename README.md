Проект "Образовательные модули"
Этот небольшой backend-проект на Django и Django Rest Framework содержит одну модель и может использоваться в качестве 
демострации развёртывания приложения в docker-контейнерах и/или для начального шага для дальнейшего развития LMS-платформы.
Документация оформлена с помощью библиотеки drf-spectacular;
Код оформлен согласно PEP8; покрыт юнит-тестами.
Стек технологий:

python 3.11
Docker
Django

Чтобы запустить проект, необходимо

установить Docker и Docker Compose https://docs.docker.com/engine/install/

клонировать этот репозиторий git clone git@gitlab.com:study4180652/edu_app.git

перейти в корень проекта и выполнить команды
docker compose build
docker compose up