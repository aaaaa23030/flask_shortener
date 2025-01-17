# Укорачиватель ссылок. Flask Shortener
Укорачиватель ссылок на Flask!

## Описание
Этот проект предназначен для укорачивания ссылок, после того как пользователь укоротит 
ссылку, она появится на главном экране. Рядом с оригинальной ссылкой показывается укороченная ссылка
и количество переходов по укороченной ссылке.

## Технологии
* Python
* Flask
* WTForms
* SQLAlchemy

## Как запустить
Убедитесь что у вас установлен Python версии 3.9
1. Склонируйте репозиторий
```commandline
git clone https://github.com/funnymonke12/flask_shortener.git
```  
2. Создайте и активируйте виртаульное окружение
```commandline
python -m venv venv

Если у вас Linux
source venv/Scripts/activate

Если у вас Windows
venv\Scripts\activate
```  
3. Установите зависимости
```commandline
pip install -r requirements.txt
```
4. Создайте файл .env и укажите настройки подключения к БД и другие параметры.
```commandline
DATABASE_URI=sqlite:///db.sqlite3
SECRET_KEY=YOUR_SECRET_KEY
```
5. Запустите flask приложение
```commandline
flask run
```

## Как использовать
####   Всего есть 2 вкладки это Главная и Ссылки. На главной странице вы сможете укоротить вашу ссылку
![img.png](images/img.png)

####  Вторая вкладка это Ссылки. На ней вы сможете посмотреть все когда-либо укороченные ссылки на этом сайте
![img_1.png](images/img_1.png)

## Автор
Максим Иванов Сергеевич
