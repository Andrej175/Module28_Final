# Module28_Final
Финальный проект Skillfactory


Необходимо протестировать новый интерфейс авторизации в личном кабинете от заказчика Ростелеком.

→ Объект тестирования: https://b2c.passport.rt.ru


📑 В корневом каталоге проекта содержатся:

config.py - содержит переменные используемые в проекте;
README.md - содержит информацию в целом о проекте;
requirements.txt - содержит все библиотеки и зависимости проекта.
 
📑 Директория tests содержит:

test_authorization_interface.py - файл автотестов;
conftest.py - условия для выполнения тестовых задач.
📑 Директория pages содержит:

locators.py - содержит описание локаторов проекта;
base_page.py - содержит базовые функции и методы.
 

При разработке тест-кейсов были применены следующие техники тест-дизайна:

эквивалентное разбиение
анализ граничных значений
 
Инструменты, которые применялись для тестирования.

Для тестирования сайта был использован инструмент Selenium;
Для определения локаторов использовались следующие инструменты: DevTools, ChroPath.
Запуск тестов:

установить все библиотеки и зависимости:  Pytest, Pytest-selenium,Faker
загрузить ChromeDriver (выберите версию, совместимую с вашим браузером) и прописать путь к драйверу в переменную PATH в файле config.py;
запустить тест: файл test_authorization_interface.py.
