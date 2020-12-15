# Сетевая игра Go с графическим интерфейсом

сборка для [**ветви**](https://github.com/vasiliykadikov/go_game/tree/Go_forCI)

[![Build Status](https://travis-ci.com/vasiliykadikov/go_game.svg?branch=main)](https://travis-ci.com/vasiliykadikov/go_game)

Отличия из-за того, что сборка для **linux**

## Хронология
- 30.10.2020 
```
готово главное меню, реализованы методы создания игрального стола, игральных камней
```
- 31.10.2020 
```
добавлен класс MainMenu с методами добавления камней на доску по местоположению курсора
```
- 06.11.2020
```
обновлён класс MainMenu. Добавлен метод печати главного экрана (меню или доски)
```
- 14.11.2020 
```
добавлен в класс MainMenu создание камня по клику мышки и по местоположению курсора
(показывается камень, который создатся по клику мыши)
```
- 15.11.2020 
```
добавлены наброски для методов, удаляющих камни
```
- 16.11.2020
```
исключена возможность ставить на одну клетку несколько камней
почти завершен метод удаления камней
```
- 19.11.2020
```
доделан метод удаления камней
сделана возможность ставить камень перед пушем
+добавлена кнопка пуша
+исключена возможность суицида камней
```
- 02.12.2020 
```
добавлены различные кнопки главного меню, необходимые для подготовки к сетевому соединению
```
- 04.12.2020 
```
добавлены все кнопки главного меню, необходимые для сетевого соединения
в папку server_for_go добавлен сервер для этого приложения
```
- 06.12.2020
```
доделан сервер. почти налажено общение клиента с сервером
```
- 07.12.2020
```
налажено рабочее "общение" клиент-сервер
```
- 09.12.2020
```
Добавлена многопоточность в программу для одновременной работы интерфейса и сетевой части
```
- 10.12.2020
```
добавлен счет, возможность выйти из игры в главное меню, сервер отсеивает отсоиденившихся пользователей
```
- 11.12.2020
```
пользователя автоматически отсоединяется в случае, если противник покинул игру
сервер автоматически удаляет лобби, в которые никто не зашел в течение 10(20) минут
```
