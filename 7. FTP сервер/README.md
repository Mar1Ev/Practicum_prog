# Основные задания:

Посмотреть содержимое папки; Верхнее окно - клиент, нижнее - сервер.
![image](https://user-images.githubusercontent.com/90052680/146777641-0c7329c4-6b73-44aa-bdfb-2afed4d79c83.png)
![image](https://user-images.githubusercontent.com/90052680/146777677-0c11bcf2-7c5a-412d-b74b-098f39f4ec1c.png)


Создать папку;

![image](https://user-images.githubusercontent.com/90052680/146777746-ab039c4b-2cbd-4063-afc0-68df740def5e.png)
![image](https://user-images.githubusercontent.com/90052680/146777804-fee5b0a8-8958-4e2d-878e-d88895964c5f.png)



Домашняя папка пользователя

![image](https://user-images.githubusercontent.com/90052680/146777916-b89e10ac-854d-49d1-aaf7-c711e4abe821.png)


В ней созданная нами

![image](https://user-images.githubusercontent.com/90052680/146777976-777ef8d5-73bb-460b-8b2e-78060385a43a.png)


Удалить папку;

![image](https://user-images.githubusercontent.com/90052680/146778029-218c7361-22c4-4515-9d27-470c3b74b15a.png)
![image](https://user-images.githubusercontent.com/90052680/146778058-2d321fd0-2140-4a55-9619-9c5732f6d922.png)
![image](https://user-images.githubusercontent.com/90052680/146778085-0d5e925b-bd93-476e-8a12-3c8937cd326f.png)



Создание и переименование далее
Переименовать файл;

![image](https://user-images.githubusercontent.com/90052680/146782240-27cfcc50-da6b-4348-aceb-89e04004d952.png)
![image](https://user-images.githubusercontent.com/90052680/146782410-2db7c0fe-6d7c-4387-b195-5b8b17045a49.png)
![image](https://user-images.githubusercontent.com/90052680/146782489-80517bc5-f53b-4291-83c6-bfe06eb13680.png)
![image](https://user-images.githubusercontent.com/90052680/146782445-0e837b55-2d01-44e4-8023-1db986b1545d.png)

Удалить файл;

![image](https://user-images.githubusercontent.com/90052680/146782572-3d1e95e2-6e51-46ae-9f0a-df33ebaa65d3.png)
![image](https://user-images.githubusercontent.com/90052680/146782605-d4502e69-7f74-4b88-9c39-e942caddd1ae.png)
![image](https://user-images.githubusercontent.com/90052680/146782658-94b57b63-9864-43be-8382-b3c27aeb26af.png)



Скопировать файл с клиента на сервер;

![image](https://user-images.githubusercontent.com/90453727/144825466-227c4bd6-162d-4e22-8355-4e1a4752d8a1.png)
![image](https://user-images.githubusercontent.com/90453727/144825496-e637886e-10b1-46e6-ac6f-15ec8480ce83.png)


Скопировать файл с сервера на клиент;

![image](https://user-images.githubusercontent.com/90453727/144826140-8bcfacf4-5358-4e4e-b92a-d858eec412ca.png)
![image](https://user-images.githubusercontent.com/90453727/144826183-36a2f05f-0e78-4a35-8328-ff84970d9503.png)


Клиент запущен в корневой директории сервера поэтому получается, что скопировали в рабобую директорию клиент, которая является и рабочей директорией сервера

![image](https://user-images.githubusercontent.com/90453727/144826249-c57b1c06-dc83-438d-8685-c61d30d70d56.png)


Выход (отключение клиента от сервера);
командой exit закрывается клиентское приложение

Дополнительные задания:
Ограничьте возможности пользователя рамками одной определенной директории. Внутри нее он может делать все, что хочет: создавать и удалять любые файлы и папки. Нужно проследить, чтобы пользователь не мог совершить никаких действий вне пределов этой директории. Пользователь, в идеале, вообще не должен догадываться, что за пределами этой директории что-то есть. Как видно было из предыдщуих скринов выйти за пределы папки - корня не может, а это рабочая папка пользователя у admin эта папка - корень сервера.

![image](https://user-images.githubusercontent.com/90453727/144826420-e8f17e7c-a194-442a-a657-dab34af43275.png)
![image](https://user-images.githubusercontent.com/90453727/144826440-b1491810-f882-4a17-8912-ba8606153348.png)


Добавьте логирование всех действий сервера в файл. Можете использовать разные файлы для разных действий, например: подключения, авторизации, операции с файлами. Логи пишутся в файл корень сервера log.txt

![image](https://user-images.githubusercontent.com/90453727/144826508-24744e73-1d68-452f-a7f4-ba0e1b4ae3ab.png)
![image](https://user-images.githubusercontent.com/90453727/144826548-c1ae00cc-94eb-464b-8999-4594f3ec10ec.png)


Добавьте возможность авторизации пользователя на сервере.
Добавьте возможность регистрации новых пользователей на сервере. При регистрации для пользователя создается новая рабочая папка (проще всего для ее имени использовать логин пользователя) и сфера деятельности этого пользователя ограничивается этой папкой. пользоваталь вводит логин пароль, если такой пользователь не существует - то создается, если существует, то проверяется корректность введенных данных.

![image](https://user-images.githubusercontent.com/90453727/144826810-1d930081-a1cd-48b2-939b-441c9262847f.png)


Неудачная авторизация 9. Реализуете квотирование дискового пространства для каждого пользователя. По 10Мб на пользователя, пример неудачной попытки:

![image](https://user-images.githubusercontent.com/90453727/144826913-65914878-074b-4b55-9478-7f6b513d5319.png)



Папка весит уже почти 9Мб. попытаемся переместить в нее файл 1,5 Гб

![image](https://user-images.githubusercontent.com/90453727/144827594-dd608ba6-704e-4b24-9ad9-8507d1e5e579.png)

Реализуйте учётную запись администратора сервера.
log/pass = admin/admin, рабочая директория - рабочая директория сервера, то есть папка с папками пользователя 13. Напишите отладочный клиент. Клиент должен подключаться к серверу и в автоматическом режиме тестировать корректность его работы. Используйте подход, аналогичный написанию модульных тестов. Клиент должен вывести предупреждающее сообщение, если сервер работает некорректно. файл ftp-test-client log/pass = test/test
![image](https://user-images.githubusercontent.com/90453727/144827674-21d2d403-56ae-43d9-aa72-e4b8fefa96b2.png)
