## Часть 1 

1.1 Использование команды docker pull для выкачки докера nginx   
<img src="pictures/1.png"/>   

1.2 Проверка наличия докер образа при помощи команды docker images  
<img src="pictures/2.png"/>   

1.3 Запуск докер образа при помощи команды docker run -d image_id   
<img src="pictures/3.png"  />  

1.4 Проверка запуска докера при помощи команды docker ps   
<img src="pictures/4.png"  />  

1.5 Просмотр информации о контейнере при помощи команды docker inspect container_id   
<img src="pictures/5.png"  />   
<img src="pictures/5_1.png"  />   
<img src="pictures/5_2.png"  />    
<img src="pictures/5_3.png"  />   

1.6 Остановка докер образа и проверка, что он остановился   
<img src="pictures/6.png"  />    

1.7 Запуск докера с замапленными портами 80 и 443    
<img src="pictures/7.png"  />   

1.8 Проверка на доступность стартовой страницы nginx по адресу localhost:80 в браузере   
<img src="pictures/8.png"  />   

1.9 Перезапуск докера и проверка, что он запустился   
<img src="pictures/9.png"  />

## Часть 2

2.1 Вывод содрежимого файла nginx.conf  
<img src="pictures/10.png"  />   
2.2 Создание на локальной машине файла nginx.conf. Настройка в нем по пути /status отдачу страницы статуса сервера   
<img src="pictures/img_8.png"  />          
2.3 Копирование файла nginx.conf внутрь докер образа. Перезапуск nginx внутри докер рбраза. Проверка статуса сервера   
<img src="pictures/11.png"  />  
2.4 Экспорт контейнера в файл. Остановка контейнера   
<img src="pictures/12.png"  />  
2.5 Удаление образа   
<img src="pictures/13.png"  />  
2.6 Удаление остановленного контейнера   
<img src="pictures/14.png"  />  
2.7 Импорт контейнера обратно. Запуск импортированного контейнера. Проверка работоспособности контейнера   
<img src="pictures/15.png"  />    

## Часть 3
3.1 Создание сервера на языке С   
<img src="pictures/16.png"  />  
3.2 Создание nginx.conf   
<img src="pictures/17.png"  />   
3.3 Выкачка докера nginx. Проверка, что загрузка прошла успешно. Запуск образа и проверка, что он запустился   
<img src="pictures/18.png"  />   
<img src="pictures/img.png"  />   
3.4 Копирование nginx.conf и server.c в докер-контейнер   
<img src="pictures/19.png"  />   
3.5 Вход в сам контейнер. Проверка, что файлы успешно скопировались  
<img src="pictures/20.png"  />
<img src="pictures/21.png"  />  
3.6 Обновление контейнера. Установка gcc, spawn-dcgi, libfcgi-dev  
<img src="pictures/22.png"  />   
3.7 Компиляция и запуск нашего сервера. Перезагрузка контейнера и проверка страницы в браузере   
<img src="pictures/24.png"  />
## Часть 4 
4.1 Создание докер образа.    
<img src="pictures/img_1.png"  />   
4.2 Запуск скрипта из докера     
<img src="pictures/img_2.png"  />   
4.3 Сбор написанного образа. Маппинг 81 порта на 80. Проверка доступа стрички командной localhost:81   
<img src="pictures/27.png"  />   
<img src="pictures/28.png"  />   
4.4 Проверка на корректность сборки   
<img src="pictures/29.png"  />   
4.5 Добавление в файл nginx.conf проксирование странички /status   
<img src="pictures/30.png"  />   
4.6 Проверка странички /status   
<img src="pictures/31.png"  />   

## Часть 5
5.1 Сканирование образа   
<img src="pictures/img_3.png"  />  
5.2 Проверка на отсутствие ошибок и предупреждений после исправления образа  
<img src="pictures/img_4.png"  />
## Часть 6
Написанный **docker-compose.yml** лежит в корне каталога. В директории **task5** и **task6** лежат файлы конфигурации для контейнеров. 

6.1 Сборка контейнеров   
<img src="pictures/img_5.png"  />    
6.2 Поднятие контейнеров  
<img src="pictures/img_6.png"  />    
6.3 Проверка, что все работает   
<img src="pictures/img_7.png"  />  
