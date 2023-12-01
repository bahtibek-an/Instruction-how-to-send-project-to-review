# **Руководство по Отправке Проекта на Проверку**

## **Список Проектов**

- Frontend
  - [My Dropbox](https://github.com/bahtibek-an/Frontend-My-Dropbox)
  - [My Instagram](https://github.com/bahtibek-an/frontend-my_intagram)
  - [My Pokemon](https://github.com/bahtibek-an/Frontend-my_pokemon)
  - [My Yelp](https://github.com/bahtibek-an/Frontend-My-Yelp)
  - [React Calculator](https://github.com/bahtibek-an/Frontend-React-Calculator)
- Backend

- ARC 01

- ARC 02

- Software engineering

- Data Science

- Machine Learning


## **Шаги Отправки Проекта**

### **Шаг 1: Форкните Репозиторий**
1. Перейдите по ссылке выбранного проекта.
2. Нажмите на кнопку `Fork`.

   ![Пример кнопки Fork](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/699d3f09-66fe-44d4-8eaa-5089d87244ee)

### **Шаг 2: Клонирование Репозитория**
1. В вашем новом форке нажмите `Create fork`.
2. Скопируйте URL для клонирования репозитория. **Добавь сюда скриншот форкнутого проекта**
3. В терминале выполните команду:
   ```
   git clone ССЫЛКА_КОТОРУЮ_ВЫ_СКОПИРОВАЛИ
   ```

### **Шаг 3: Работа над Проектом**
1. Откройте скачанную папку и начните работу над проектом. 
   
### **Шаг 4: Создание и Отправка Ветки**
1. Создайте новую ветку с вашим именем:
   ```
   git branch ВАШЕ_ИМЯ_И_ФАМИЛИЯ
   ```
2. Переключитесь на новую ветку:
   ```
   git checkout ВАШЕ_ИМЯ_И_ФАМИЛИЯ
   ```
3. Отправьте изменения:
   ```
   git add .
   git commit -m “КОММЕНТ”
   git push origin ВАШЕ_ИМЯ_И_ФАМИЛИЯ
   ```

### **Шаг 5: Создание Pull Request**
1. В вашем репозитории на GitHub нажмите `Pull requests`.
2. Нажмите `Create pull request`.
**Добавь скриншот где выбирают ветку**

   ![Создание Pull Request](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/721cb514-2404-40db-a121-3ca8cc9124d4)

3. Выберите вашу ветку и нажмите `Create pull request`.

   ![Выбор ветки](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/982e7c57-87af-4baf-b17b-9d9ee0106b9b)

4. В открывшемся окне нажмите еще раз на кнопку `Create pull request` и по желанию можете написать описание. 

   ![Отправка Pull Request](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/635df8d1-88c2-4dd2-b6c0-b90745377173)



<!-- В конец улучшенной документации можно добавить раздел, объясняющий, как проверить и выполнить запрошенные изменения. Вот обновленный текст с этим разделом: -->

### **Шаг 6: Проверка и Выполнение Запрошенных Изменений**

После создания Pull Request, ваш проект будет проверен. Если будут запрошены изменения, следуйте этим шагам:

1. **Проверка Запроса на Изменения**:
   - В разделе Pull Request вашего проекта найдите раздел "Запрошены изменения" (Requested changes).
   - Внимательно прочитайте комментарии и запросы на изменения.

2. **Выполнение Изменений**:
   - Вернитесь к локальной версии вашего проекта и внесите необходимые изменения.
   - После внесения изменений, сохраните их и следуйте командам Git для добавления, коммита и пуша изменений.
     ```
     git add .
     git commit -m “Исправление запрошенных изменений”
     git push origin ВАШЕ_ИМЯ_И_ФАМИЛИЯ
     ```

3. **Обновление Pull Request**:
   - После пуша изменений, возвращайтесь к Pull Request на GitHub.
   - Оставьте комментарий, что изменения были сделаны, и укажите на любые конкретные исправления, если это необходимо.

4. **Дальнейший Отклик**:
   - Дождитесь повторной проверки вашего Pull Request.
   - Если будут новые запросы на изменения, повторите шаги 1-3.

