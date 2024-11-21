# Домашнее задание к занятию «Что такое DevOps. CI/CD»

## Информация
- **Имя и фамилия**: Иван Иванов
- **Репозиторий GitHub**: [git-homework](https://github.com/kozlovvs212/git-homework)

---

## Задание 1: Установка Jenkins, настройка проекта и сборка с Go

### Описание задания:
1. Установите Jenkins по инструкции из лекции или другим способом из официальной документации (без использования Docker).
2. Установите на машину с Jenkins Golang.
3. Сделайте форк репозитория и подключите его к Jenkins.
4. Создайте проект Freestyle в Jenkins, подключите репозиторий и произведите запуск тестов и сборку проекта с помощью команд `go test .` и `docker build .`.
   
### Скриншоты:
- Все скриншоты можно найти в [Google Документе с отчетом](https://docs.google.com/document/d/19etJQjT3vnVpEUP7-x8utFwq9A688qCaIEZPt4V0kh0/edit?usp=sharing).

---

## Задание 2: Создание проекта Pipeline

### Описание задания:
1. Создайте новый проект Pipeline в Jenkins.
2. Перепишите сборку из задания 1 в виде Declarative Pipeline.
3. Добавьте код и скриншоты с настройками.

### Скриншоты:
- Все скриншоты можно найти в [Google Документе с отчетом](https://docs.google.com/document/d/19etJQjT3vnVpEUP7-x8utFwq9A688qCaIEZPt4V0kh0/edit?usp=sharing).

---

## Задание 3: Работа с Nexus

### Описание задания:
1. Установите Nexus и создайте репозиторий типа `raw-hosted`.
2. Измените Pipeline, чтобы вместо Docker-образа собирался бинарный Go-файл. Используйте команду из Dockerfile.
3. Загрузите файл в Nexus через Jenkins.

### Скриншоты:
- Все скриншоты можно найти в [Google Документе с отчетом](https://docs.google.com/document/d/19etJQjT3vnVpEUP7-x8utFwq9A688qCaIEZPt4V0kh0/edit?usp=sharing).
