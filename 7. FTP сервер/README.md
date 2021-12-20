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

![image](https://user-images.githubusercontent.com/90052680/146790747-b3e52986-a37e-4a1b-8ab3-a7dc332b026a.png)
![image](https://user-images.githubusercontent.com/90052680/146790785-e6650284-1108-4759-b564-156a584e600a.png)
![image](https://user-images.githubusercontent.com/90052680/146790835-0ace0c76-60c9-4ad0-aedf-8361bac7f70f.png)



Скопировать файл с сервера на клиент;
![image](https://user-images.githubusercontent.com/90052680/146791161-9ed98c62-18ad-41eb-b0d5-90998215d303.png)
![image](https://user-images.githubusercontent.com/90052680/146791189-13b11b36-9ab1-412b-9537-a4b13989f58c.png)



Клиент запущен в корневой директории сервера поэтому получается, что скопировали в рабобую директорию клиент, которая является и рабочей директорией сервера

![image](https://user-images.githubusercontent.com/90052680/146791244-0808063b-2319-4c01-accf-b53fb7429c0b.png)


Выход (отключение клиента от сервера);
командой exit закрывается клиентское приложение

Дополнительные задания:
Ограничьте возможности пользователя рамками одной определенной директории. Внутри нее он может делать все, что хочет: создавать и удалять любые файлы и папки. Нужно проследить, чтобы пользователь не мог совершить никаких действий вне пределов этой директории. Пользователь, в идеале, вообще не должен догадываться, что за пределами этой директории что-то есть. Как видно было из предыдщуих скринов выйти за пределы папки - корня не может, а это рабочая папка пользователя у admin эта папка - корень сервера.

![image](https://user-images.githubusercontent.com/90052680/146791920-b2046b60-0c69-4f5d-b7a1-95c65a850704.png)
![image](https://user-images.githubusercontent.com/90052680/146791958-374a1cd3-7465-475a-8fe1-8a042899624f.png)



Добавьте логирование всех действий сервера в файл. Можете использовать разные файлы для разных действий, например: подключения, авторизации, операции с файлами. Логи пишутся в файл корень сервера log.txt
![image](https://user-images.githubusercontent.com/90052680/146789753-566bf421-6ad1-4701-be40-2517aaadae22.png)
![image](https://user-images.githubusercontent.com/90052680/146789800-fe1e6b98-3b7d-46e2-9952-d46a78933264.png)


Добавьте возможность авторизации пользователя на сервере.
Добавьте возможность регистрации новых пользователей на сервере. При регистрации для пользователя создается новая рабочая папка (проще всего для ее имени использовать логин пользователя) и сфера деятельности этого пользователя ограничивается этой папкой. пользоваталь вводит логин пароль, если такой пользователь не существует - то создается, если существует, то проверяется корректность введенных данных.

![image](https://user-images.githubusercontent.com/90052680/146792223-6d89014b-7a6f-480d-8778-9e42ad5aad1c.png)


Неудачная авторизация 9. Реализуете квотирование дискового пространства для каждого пользователя. По 10Мб на пользователя, пример неудачной попытки:

![image](https://user-images.githubusercontent.com/90453727/144826913-65914878-074b-4b55-9478-7f6b513d5319.png)



Папка весит уже почти 9Мб. попытаемся переместить в нее файл 1,5 Гб

![image](https://user-images.githubusercontent.com/90052680/146792377-f8587eae-cbc9-49a7-af39-0f264da73dc2.png)


