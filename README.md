# Weather application

![bigscreen.jpg](static/icon/bigscreen.jpg)

Цей проект розроблено з метою ознайомлення із роботою API, принципом отримання даних від віддаленого серверу, вмінням їх обробляти, структурувати та застосовувати у своємо проєкті. А саме застосовувалось API такого веб-ресурсу як [OpenWeatherMap](https://openweathermap.org). Проєкт допоможе розібратися із роботою файлів JSON, як правильно отримувати та зберігати дані у файлах з типом .json. Та познайомити користувача з інтерфейсом застосунку розробленим за допомогою пакету [CustomTkinter](https://customtkinter.tomschimansky.com)

### Зміст репозиторія:

1. [Основні модулі проєкту](#all-modules)
2. [Розгортання проєкту](#download-project)
3. [Створення віртуального оточення проєкту](#create-venv)
4. [Завантаження модулів до віртуального оточення](#download-modules-venv)
5. [Старт проєкту](#start-project)
6. [Основні механіки проєкту](#all-mechanics)
7. [Висновок по проєкту](#result) 
___
<h4 id= 'all-modules'>Основні модулі проєкту:</h4>
All modules

- [customtkinter](https://customtkinter.tomschimansky.com/)
- [json](https://docs.python.org/3/library/json.html)
- [requests](https://pypi.org/project/requests/)
- [pillow](https://pillow.readthedocs.io/en/stable/)
- [os](https://docs.python.org/uk/3.13/library/os.html)
- [colorama](https://pypi.org/project/colorama/)
- [datetime](https://docs.python.org/uk/3.9/library/datetime.html)
___
<h4 id= 'download-project'>Розгортання проєкту:</h4>
Download project

1. Склонувати з Git Hub репозиторію
    - git clone <посилання на репозиторій>
    - cd <назва_папки_проєкту>

2. Завантажити за допомогою zip-архіву
    - завантажити zip-архів
___
<h4 id= 'create-venv'>Створення віртуального оточення проєкту:</h4>
Сreate venv

1. Windows
    - 1. python -m venv venv
    - 2. venv\Scripts\activate

2. Mac OS або Linux
    - 1. python3 -m venv venv
    - 2. source venv/bin/activate
___
<h4 id= 'download-modules-venv'>Завантаження модулів до віртуального оточення:</h4>
Download modules venv

1. Окремими модулями
    - через (pip install) встановити усі необхідні модулі
2. За допомогою файлу requirements.txt
    - pip install -r requirements.txt
___
<h4 id= 'start-project'>Старт проєкту:</h4>
Start project

зробіть запуск програми через команду 
  - python main.py
___
<h4 id= 'all-mechanics'>Основні механіки проєкту:</h4>

___
<h4 id= 'result'>Висновок проєкту:</h4>
У цьому проєкті я навчилась користуватися офіційними данними про погоду та використовуваати їх у своєму проєкті завдяки API. Також я навчалася користуватися файлами JSON. Якби була можливість і більше часу хотілося б додати також карту опадів, напрям вітрів і тиск.
