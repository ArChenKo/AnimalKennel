# Итоговая контрольная работа по специальности Разработчик-Программист

## Информация о проекте
Необходимо организовать систему учета для питомника, в котором живут
домашние и вьючные животные.

## Задание
1. Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослами, а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека).
![Task 1](images/1-1.png)

2. Создать директорию, переместить файл туда.
![Task 2](images/2-1.png)

3. Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.
![Task 3-1](images/3-1.png)
![Task 3-2](images/3-2.png)
![Task 3-3](images/3-3.png)

4. Установить и удалить deb-пакет с помощью dpkg.
![Task 4-1](images/4-1.png)
![Task 4-2](images/4-2.png)

5. Выложить [историю команд](images/5-1.png) в терминале ubuntu
6. Нарисовать [диаграмму](images/Class-diagram.drawio.png), в которой есть класс родительский класс, домашние животные и вьючные животные, в составы которых в случае домашних животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные войдут: Лошади, верблюды и ослы.
![UML](images/6-1.png)

7. В подключенном MySQL репозитории создать базу данных “Друзья человека”
![Task 7-1](images/7-1.png)

8. Создать таблицы с иерархией из диаграммы в БД
![Task 8-1](images/8-1.png)
![Task 8-2](images/8-2.png)

9. Заполнить низкоуровневые таблицы именами(животных), командами которые они выполняют и датами рождения
![Task 9-1](images/9-1.png)
![Task 9-2](images/9-2.png)
![Task 9-3](images/9-3.png)
![Task 9-4](images/9-4.png)

10. Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой питомник на зимовку. Объединить таблицы лошади, и ослы в одну таблицу.
![Task 10-1](images/10-1.png)

11. Создать новую таблицу “молодые животные” в которую попадут все животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью до месяца подсчитать возраст животных в новой таблице.
![Task 11-1](images/11-1.png)

12. Объединить все таблицы в одну, при этом сохраняя поля, указывающие на прошлую принадлежность к старым таблицам.
![Task 12-1](images/12-1.png)

13. Создать [класс с Инкапсуляцией методов и наследованием по диаграмме](https://github.com/ArChenKo/AnimalKennel/tree/main/Program/Model).

14. Написать [программу, имитирующую работу реестра домашних животных](https://github.com/ArChenKo/AnimalKennel/tree/main/Program).
В программе должен быть реализован следующий функционал:    
	14.1 Завести новое животное    
	14.2 определять животное в правильный класс    
	14.3 увидеть список команд, которое выполняет животное    
	14.4 обучить животное новым командам    
	14.5 Реализовать навигацию по меню

15. Создайте [класс Счетчик](https://github.com/ArChenKo/AnimalKennel/blob/main/Program/Controller/Counter.java), у которого есть метод add(), увеличивающий̆
значение внутренней̆ int переменной̆ на 1 при нажатии “Завести новое животное”. Сделайте так, чтобы с объектом такого типа можно было работать в блоке try-with-resources. Нужно бросить исключение, если работа с объектом типа счетчик была не в ресурсном try и/или ресурс остался открыт. Значение считать в ресурсе try, если при заведении животного заполнены все поля.
![Program](images/15-1.png)
