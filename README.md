# Запрос на получение списка фактов о кошках
## Описание
По адресу https://raw.githubusercontent.com/netology-code/jd-homeworks/master/http/task1/cats находится список фактов о кошках. 
Наша задача - сделать запрос к этому ресурсу и отфильтровать факты, за которые никто не проголосовал (поле upvotes). 
Формат каждой записи следующий:

{
 "id": "5b4910ae0508220014ccfe91",  
 "text": "Кошки могуть создавать более 100 разных звуков, тогда как собаки только около 10.",  
 "type": "cat",  
 "user": "Alex Petrov",  
 "upvotes": null  
},  

id - уникальный идентификатор записи  
text - сообщение  
type - тип животного  
user - имя пользователя  
upvotes - голоса  

### Что нужно сделать
1. Прочитать весь список и вернуть только те факты, у которых поле upvotes не равно null.
