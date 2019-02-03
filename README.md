
<img src="https://cdn1.savepice.ru/uploads/2019/2/3/50aa6328bda9132ab6e0266ac6c7dcc7-full.png" width="250"/>

# Star Android

## Разработка Android приложения (Tamagotchi)


---
> **Требование к участникам:**
> - **Знание Java Core.**

> Оптимально:
> - Курс [Base Java](http://javaops.ru/reg/basejava)
> - Бесплатный курс ["Программирование под Андроид"](https://javarush.ru/quests/QUEST_GOOGLE_ANDROID) на Java Rush
---


### Программа:

- #### Первое открытое занятие:

  - Установка Android Studio и Genymotion
  - Создание нового проекта.
  - Hello World!
  - Layout
  - ImageView
  - Button
  - Смена Activity
  - Animation
  - Домашнее задание: HW_1

- #### Занятие 2

  - Разбор HW_1
  - Создание меню
  - Lifecycle приложения на Android
  - AlertDialog
  - DataBase  SQLite
  - Shared Preferences
  - RecyclerView
  - Домашнее задание: HW_2

- #### Занятие 3

  - Разбор HW_2
  - Receiver
  - AlarmManager
  - Handler
  - Notification
  - ProgressBar
  - Домашнее задание: HW_3

- #### Занятие 4

  - Разбор HW_3
  - Рефакторинг
  - SoundPool
  - Spinner Adapter
  - No title bar
  - Добавление коммерческой рекламы Admob
  - landscape
  - Домашнее задание: HW_4

- #### Занятие 5 

  - Разбор HW_4
  - Публикация приложения в Google Play

---

## Занятие 1


### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. О проекте и установка ПО.

- [Android Studio](https://developer.android.com/studio/)
- [Genymotion](https://www.genymotion.com)
- [Что такое Git](https://drive.google.com/file/d/0B9Ye2auQ_NsFSUNrdVc0bDZuX2s/edit)
- [GIT](https://git-scm.com/downloads)
- [Установка GIT](https://www.youtube.com/watch?v=mpK_MYb38zs)
- [JDK8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Как установить JDK8](https://www.youtube.com/watch?v=D59Sd7D58F0)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. Hello World

- [Компоненты экрана](https://startandroid.ru/ru/uroki/vse-uroki-spiskom/13-urok-4-elementy-ekrana-i-ih-svojstva.html)
- [Layout](http://developer.alexanderklimov.ru/android/theory/layout.php)
- [LinearLayout](http://developer.alexanderklimov.ru/android/layout/linearlayout.php)
- [RelativeLayout](http://developer.alexanderklimov.ru/android/layout/relativelayout.php)
- [Единицы измерения](http://developer.alexanderklimov.ru/android/theory/scales.php)
- [ImageView](http://developer.alexanderklimov.ru/android/views/imageview.php)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. Смена активити.

- [Activity](http://developer.alexanderklimov.ru/android/theory/activity-theory.php#what)
- [Button](http://developer.alexanderklimov.ru/android/views/button.php)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. Анимация

- [Анимация преобразований](http://developer.alexanderklimov.ru/android/animation/tweenanimation.php)

### ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. TranslateAnimation

- [TranslateAnimation](http://developer.alexanderklimov.ru/android/animation/translateanimation.php)

---

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW_1

```
1. Установить ПО (git, JDK8, Android Studio, Genymotion)</a>
- Создать аккаунт на GitHub
- Сделать Fork **ЭТОГО** проекта
- Скачать и накатить патчи 
```
[Patch](https://drive.google.com/file/d/1THrlPwoFIGVfd7T6yWFkFR_fiCkkdBrh/view?usp=sharing)
```
Скачать ресурсы для HW_1 и разместить их в соответстующих директориях
```
[Resources](https://drive.google.com/file/d/1L9cKSTV6GMOGiAi-OzP2Hj4PlRyo3BAP/view?usp=sharing)
```

2. Создать три кнопки "Dog", "Cat", "Cthulhu", и расположить их в майн активити таким образом:
```
![buttons](https://cdn1.savepice.ru/uploads/2019/2/3/124cf95c5458fc74cab839ce0a814acb-full.jpg)
```
кнопки не должны менять свое относительное положение в зависимости от размера экрана устройства.

3. Создать новое Activity "WalkActivity", 
- в MainActivity все три кнопки должны при нажатии менять активити на WalkActivity
- расположите в нем кнопку "home", для перехода обратно к MainActivity 
- расположите в нем ImageView в котором должно отображаться изображение того животного с названием которого была нажата кнопка в MainActivity. (размер ImageView подберите исходя из здравого смысла:))
- Задайте этому ImageView бесконечную анмацию перемещения по экрану в случайном направлении и на случайное растояние. ImageView не должен заходить за края видимого экрана.


4. Optional
- Сделать так, что бы изображение животного в WalkActivity поворачивось лицом в направлении движения.
- Сделать так, что бы при нажатии на изображение животного воспроизводился соответстующий животному звук.
```

#### Замечания к HW1

- [Работа с ресурсами](https://metanit.com/java/android/2.4.php)
- [Передача данных между Activity](http://developer.alexanderklimov.ru/android/activity.php#passdata)
- [Определение начальных размеров View в Android](http://poetofcode.ru/programming/2017/06/12/kak-opredelit-nachalnyue-razmeryu-view-v-android.html)
- для вычисления угла поворота используйте класс Math.
- Почитайте про класс [ObjectAnimator](https://developer.android.com/reference/android/animation/ObjectAnimator)

---

### Дополнительные материалы:

[Анимации в Android по полочкам](https://habr.com/ru/post/347918/)

[Animation и Transition](http://developer.alexanderklimov.ru/android/animation/)

[Анимации c помощью Transitions API](https://habr.com/ru/post/243363/)