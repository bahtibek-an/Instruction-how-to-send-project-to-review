# Инструкция по отправке проекта на проверку

## Список проектов:
### Frontend
- [My Dropbox](https://github.com/bahtibek-an/Frontend-My-Dropbox)
- [My Instagram](https://github.com/bahtibek-an/frontend-my_intagram)
- [My Pokemon](https://github.com/bahtibek-an/Frontend-my_pokemon)
- [My Yelp](https://github.com/bahtibek-an/Frontend-My-Yelp)
- [React Calculator](https://github.com/bahtibek-an/Frontend-React-Calculator)

## Инструкция

У каждого проекта есть своя репозиторий. Зайдите в нужный вам проект по ссылке который перечислен наверху.
И на сайте нажмите на кнопку `Fork`.

![image](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/699d3f09-66fe-44d4-8eaa-5089d87244ee)

И после этого у вас откроется следующий окно:

![image](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/8b2a40a3-02fe-44e4-92f9-6324d6ee5ec9)

Нажмите на зеленую кнопку `Create fork`.

![image](https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/794705f1-c6b9-4d4f-b7df-9cde4c06382c)

У вас на аккаунте создастся этот репозиторий, и вы можете работать над этим проектом. Чтобы работать над этим проектом вам нужно нажать на зеленую кнопку `Code`, и в меню скопировать ссылку.
После того как скопировали ссылку надо клонировать репозиторию в ваш локальный компьютер c помощью этой команды:
```
git clone ССЫЛКА_КОТОРЫЙ_ВЫ_СКОПИРОВАЛИ
```
После выполнение команды вы можете зайти в папку, которую скачали и свободно работать над этим проектом. 
Если у вас уже готов проект, то проста скопируйте ваш проект в эту папку.

Как закончили проект, создайте новую ветку c вашим именем. Обратите внимание то, что после создания ветки не надо создавать снова новую ветку.
```
git branch ВАША_ПОЛНАЯ_ИМЯ
```
Чтобы перейти в новую ветку:
```
git checkout ВАША_ПОЛНАЯ_ИМЯ
```

И базовые команды для отправки в удаленный репозиторий:
```
git add .
git commit -m “КОММЕНТ”
git push origin ВАША_ПОЛНАЯ_ИМЯ
```

В вашей репозиторий вам надо нажать на кнопку `Pull requests`

<img width="1268" alt="image" src="https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/721cb514-2404-40db-a121-3ca8cc9124d4">

В открывшемся окне нажмите на кнопку показанный на картинке.

<img width="1280" alt="image" src="https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/f618a139-b7e2-45e4-98a6-440046dd7a23">

Измените ветку на которую вы создали и нажмите на зеленую кнопку `Create pull request`

<img width="1280" alt="image" src="https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/982e7c57-87af-4baf-b17b-9d9ee0106b9b">

В открывшемся окне нажмите еще раз на кнопку `Create pull request` и по желанию можете написать описание. 

<img width="1269" alt="image" src="https://github.com/bahtibek-an/Instruction-how-to-send-project-to-review/assets/57597976/635df8d1-88c2-4dd2-b6c0-b90745377173">

