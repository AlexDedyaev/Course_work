[![Java CI with Gradle](https://github.com/AlexDedyaev/Course_work/actions/workflows/gradle-publish.yml/badge.svg)](https://github.com/AlexDedyaev/Course_work/actions/workflows/gradle-publish.yml)
### Курсовой проект по модулю «Автоматизация тестирования» для профессии «Инженер по тестированию»
![img.png](docs/img.png)

[Ссылка на задание ](https://github.com/netology-code/aqa-qamid-diplom)

Задача автоматизировать позитивные и негативные сценарии покупки тура.

#### [План](https://github.com/AlexDedyaev/Course_work/blob/main/docs/Plan.md)

#### [Итоги тестирования](https://github.com/AlexDedyaev/Course_work/blob/main/docs/Report.md)

#### [Итоги автоматизации](https://github.com/AlexDedyaev/Course_work/blob/main/docs/Summary.md)

#### Шаги воспроизведения

**Предусловие**

На ПК необходимо установить ```IntelliJ IDEA Community Edition```, ```Google Chrome```, ```Docker Desktop```

**Установка и запуск**

1. Скачать проект с репозитория на ```GitHub``` с помощью команды в консоли:
```
git clone 
```

2. Запустить Docker Desktop.

3. Открыть проект в IntelliJ IDEA.

4. Запустить контейнер с помощью команды в консоли:

```
docker compose up
```
5. Запустить приложение:

```
java -jar .\artifacts\aqa-shop.jar 
```

6. Откройте браузер и перейдите по адресу http://localhost:8080, чтобы увидеть работающий проект. Теперь проект должен работать на вашем локальном компьютере.


7. Запуск тестов осуществляется с помощью команды в консоли:

```
./gradlew clean test 
```

8. Запустите генерацию отчета Allure и их автоматического открытия в браузере командой в терминале:

```
./gradlew allureServe
```
9. Закрыть отчёт Allure:

```CTRL + C -> y -> Enter``` 


**Завершение работы**

1. Завершение работы ```SUT``` осуществляется с помощью команды в консоли ```Ctrl + C```
2. Остановка контейнеров в ```IntelliJ IDEA``` осуществляется с помощью команды:

```
docker compose down
```
