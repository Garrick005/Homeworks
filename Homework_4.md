# Домашнее задание к занятию 4 «Оркестрация группой Docker контейнеров на примере Docker Compose»

## Задание 1.

1. https://hub.docker.com/repository/docker/garrick005/custom-nginx/general
При загрузке образа в публичный репозиторий появляется ошибка:
denied: requested access to the resource is denied

## Задание 2.

1. https://github.com/Garrick005/Homeworks/blob/c20d5dc683e4f379bc79e9cfe3d41131c3dadcf4/task2-1.PNG
2. https://github.com/Garrick005/Homeworks/blob/c20d5dc683e4f379bc79e9cfe3d41131c3dadcf4/task2-2.PNG
3. https://github.com/Garrick005/Homeworks/blob/c20d5dc683e4f379bc79e9cfe3d41131c3dadcf4/task2-3.PNG
4. https://github.com/Garrick005/Homeworks/blob/c20d5dc683e4f379bc79e9cfe3d41131c3dadcf4/task2-4.PNG

## Задание 3.

1. https://github.com/Garrick005/Homeworks/blob/main/task3-1.PNG
2. https://github.com/Garrick005/Homeworks/blob/main/task3-2.PNG
3. Комбинация клавиш Ctrl-C после команды docker attach отправляет сигнал SIGINT (interrupt) процессу, запущенному в контейнере, что приводит к завершению процесса и остановке всего контейнера.
4. https://github.com/Garrick005/Homeworks/blob/main/task3-4.PNG
5. https://github.com/Garrick005/Homeworks/blob/main/task3-5.PNG
6. https://github.com/Garrick005/Homeworks/blob/main/task3-6.PNG
7. https://github.com/Garrick005/Homeworks/blob/main/task3-7.PNG
8. https://github.com/Garrick005/Homeworks/blob/main/task3-8.PNG
10. https://github.com/Garrick005/Homeworks/blob/main/task3-10.PNG

Проблема в том, что для работы nginx хостовая машина по умолчанию пробрасывает порт 80 для взаимодействия с контейнером. Если поменять в настройках конфигурации внутри контейнера порт на 81, тогда nginx будет сбрасывать соединение по порту 80.

12. https://github.com/Garrick005/Homeworks/blob/main/task3-11.PNG

## Задание 4.

1. https://github.com/Garrick005/Homeworks/blob/Garrick005-patch-1/task4-1.PNG
2. https://github.com/Garrick005/Homeworks/blob/Garrick005-patch-1/task4-2.PNG
3. https://github.com/Garrick005/Homeworks/blob/Garrick005-patch-1/task4-3-1.PNG
4. https://github.com/Garrick005/Homeworks/blob/Garrick005-patch-1/task4-3-1-1.PNG
5. https://github.com/Garrick005/Homeworks/blob/Garrick005-patch-1/task4-4-1.PNG
6. https://github.com/Garrick005/Homeworks/blob/Garrick005-patch-1/task4-4-1-1.PNG
7. https://github.com/Garrick005/Homeworks/blob/Garrick005-patch-1/task4-5.PNG

