## Проект "Дом Питомца"
<details>
<summary><b>Тестирование функционала веб-приложения «Дом Питомца»</b> </summary>
 <p><blockquote>Данный сайт предназначен для размещения объявлений о бездомных животных</blockquote></p>
</details>
<hr>
<details>
<summary><b>Условия заказчика</b> </summary>
 <p><blockquote>1. Выполнить тестирование в соответствии с требованиями.<br>
   2. Предоставить следующие артефакты тестирования: Чек-листы, Тест-кейсы, Список багов.<br>
   3. Тест-кейсы и баги должны быть оформлены по внутренним стандартам заказчика</blockquote></p>
</details>

Дата проведения тестирования: 29.01.23 – 13.02.23

#### **Виды тестирования:**

Для всего сайта:
- Функциональное тестирование
- UI тестирование
  
Для критического функционала сайта:
- Кроссбраузерное и кроссплатформенное тестирование

Для полей ввода (текстовых, числовых, e-mail):
- Позитивное тестирование (введение корректных данных)
- Негативное тестирование (введение некорректных данных)

По степени автоматизации:
- ручное (мануальное) тестирование 

Для поиска технических проблем веб-страниц использованы _инструменты_ [_SEO_](https://pingler.com/seo-tools/)

При разработке тест-кейсов применены следующие **техники тест-дизайна**:
- разбиение на классы эквивалентности;
- анализ граничных значений;
- pairwise;
- предугадывание ошибок
<hr>

### Тестовая документация:
&#8594; [Функциональное тестирование Чек-лист № 1, Чек-лист № 2](https://github.com/Elena-Belova/Project-Pet-Home/blob/5ba15168b492b1020f5b115408d9bb52955acce5/1.%20%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82.%20%D0%94%D0%BE%D0%BC%20%D0%9F%D0%B8%D1%82%D0%BE%D0%BC%D1%86%D0%B0%20%D0%A7%D0%B5%D0%BA-%D0%BB%D0%B8%D1%81%D1%82%20%E2%84%961%2C%202.pdf)<br>
&#8594; [Кроссбраузерность / Кроссплатформенность / Адаптивность критического функционала Чек-лист №3](https://github.com/Elena-Belova/Project-Pet-Home/blob/5ba15168b492b1020f5b115408d9bb52955acce5/2.%20%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82.%20%D0%94%D0%BE%D0%BC%20%D0%9F%D0%B8%D1%82%D0%BE%D0%BC%D1%86%D0%B0%20%D0%A7%D0%B5%D0%BA-%D0%BB%D0%B8%D1%81%D1%82%20%E2%84%963.pdf)<br>
&#8594; [Тестирование веб-страниц Чек-лист № 4](https://github.com/Elena-Belova/Project-Pet-Home/blob/5ba15168b492b1020f5b115408d9bb52955acce5/3.%20%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82.%20%D0%94%D0%BE%D0%BC%20%D0%9F%D0%B8%D1%82%D0%BE%D0%BC%D1%86%D0%B0%20%D0%A7%D0%B5%D0%BA-%D0%BB%D0%B8%D1%81%D1%82%20%E2%84%964.pdf)<br>
&#8594; [Описание дефектов (баг-репорты)](https://github.com/Elena-Belova/Project-Pet-Home/blob/5ba15168b492b1020f5b115408d9bb52955acce5/4.%20%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82.%20%D0%94%D0%BE%D0%BC%20%D0%9F%D0%B8%D1%82%D0%BE%D0%BC%D1%86%D0%B0%20%D0%91%D0%B0%D0%B3-%D1%80%D0%B5%D0%BF%D0%BE%D1%80%D1%82%D1%8B.pdf)<br>
&#8594; [Примеры Тест-кейсов](https://github.com/Elena-Belova/Project-Pet-Home/blob/5ba15168b492b1020f5b115408d9bb52955acce5/5.%20%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82.%20%D0%94%D0%BE%D0%BC%20%D0%9F%D0%B8%D1%82%D0%BE%D0%BC%D1%86%D0%B0%20%D0%A2%D0%B5%D1%81%D1%82-%D0%BA%D0%B5%D0%B9%D1%81%D1%8B.pdf)
<hr>

### API "Дом Питомца"

&#8594; [Коллекция Postman "API PetHome GET запросы"(JSON)](https://github.com/Elena-Belova/Project-Pet-Home/blob/3ecf66a2c97d58333eb6c244f83921931319fda5/API%20PetHome/API%20PetHome%20GET%20%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D1%8B.postman_collection.json)

&#8594; [Коллекция Postman "API PetHome Функция фильтрации"(JSON)](https://github.com/Elena-Belova/Project-Pet-Home/blob/3ecf66a2c97d58333eb6c244f83921931319fda5/API%20PetHome/API%20PetHome%20%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F%20%D1%84%D0%B8%D0%BB%D1%8C%D1%82%D1%80%D0%B0%D1%86%D0%B8%D0%B8.postman_collection.json) &#8594; Функция фильтрации-тестовые данные-[Pairwise(csv)](https://github.com/Elena-Belova/Project-Pet-Home/blob/3ecf66a2c97d58333eb6c244f83921931319fda5/API%20PetHome/DataPH(pairwise).csv)

&#8594; [Окружение Pet Home (JSON)](https://github.com/Elena-Belova/Project-Pet-Home/blob/3ecf66a2c97d58333eb6c244f83921931319fda5/API%20PetHome/Pet%20Home.postman_environment.json)

Запросы составлены с использованием ***DevTools***
<hr>

**Интеллект-карта «Дом питомца»** [в pdf](https://github.com/Elena-Belova/Project-Pet-Home/blob/5ba15168b492b1020f5b115408d9bb52955acce5/%D0%98%D0%9A%D0%B0%D1%80%D1%82%D0%B0.%20%D0%94%D0%BE%D0%BC%20%D0%9F%D0%B8%D1%82%D0%BE%D0%BC%D1%86%D0%B0.pdf)

![ИКарта ДОМ ПИТОМЦА Вар 2](https://github.com/Elena-Belova/Project-Pet-Home/assets/148638077/a557708a-f00e-4340-9382-ca7431fd16dd)

<hr>
