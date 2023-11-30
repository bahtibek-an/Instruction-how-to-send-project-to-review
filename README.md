# **Руководство по Отправке Проекта на Проверку**

## **Список Проектов**

- Frontend
  - [My Dropbox](https://github.com/bahtibek-an/Frontend-My-Dropbox)
  - [My Instagram](https://github.com/bahtibek-an/frontend-my_intagram)
  - [My Pokemon](https://github.com/bahtibek-an/Frontend-my_pokemon)
  - [My Yelp](https://github.com/bahtibek-an/Frontend-My-Yelp)
  - [React Calculator](https://github.com/bahtibek-an/Frontend-React-Calculator)

## **Шаги Отправки Проекта**

### **Шаг 1: Форкните Репозиторий**
1. Перейдите по ссылке выбранного проекта.
2. Нажмите на кнопку `Fork`.

   ![Пример кнопки Fork](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/699d3f09-66fe-44d4-8eaa-5089d87244ee)

### **Шаг 2: Клонирование Репозитория**
1. В вашем новом форке нажмите `Create fork`.
2. Скопируйте URL для клонирования репозитория.
3. В терминале выполните команду:
   ```
   git clone ССЫЛКА_КОТОРЫЙ_ВЫ_СКОПИРОВАЛИ
   ```

### **Шаг 3: Работа над Проектом**
1. Откройте скачанную папку и начните работу над проектом. Если уже закончен проект то скопируйте ваш проект в эту папку.
   
### **Шаг 4: Создание и Отправка Ветки**
1. Создайте новую ветку с вашим именем:
   ```
   git branch ВАША_ПОЛНАЯ_ИМЯ
   ```
2. Переключитесь на новую ветку:
   ```
   git checkout ВАША_ПОЛНАЯ_ИМЯ
   ```
3. Отправьте изменения:
   ```
   git add .
   git commit -m “КОММЕНТ”
   git push origin ВАША_ПОЛНАЯ_ИМЯ
   ```

### **Шаг 5: Создание Pull Request**
1. В вашем репозитории на GitHub нажмите `Pull requests`.
2. Нажмите `Create pull request`.

   ![Создание Pull Request](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/721cb514-2404-40db-a121-3ca8cc9124d4)

3. Выберите вашу ветку и нажмите `Create pull request` еще раз.

   ![Выбор ветки](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/982e7c57-87af-4baf-b17b-9d9ee0106b9b)
