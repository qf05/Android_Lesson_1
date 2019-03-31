
<img src="https://lh3.googleusercontent.com/cnijMiTRifrSs4HwbEX-AtN--QxP8KwW1GB22yE62aulw1Yfyin1u9xSIDVsTk3ViZKqEzDPoSt8LivslSVT0LHjTZGP4imV6qeZ-jcV-dCwIuwyDYUdt-HOTX_nk79iuhvMuFKFqQ=w1075-h246-no"/>

# Star Android & JAVA Online Projects  представляют:

## Курс по разработке приложения для Android: Tamagotchi


---
> **Требование к участникам:**
> - **Знание Java Core**
>
> Оптимально:
> - Курс [BaseJava](http://javaops.ru/reg/basejava)
> - Бесплатный курс ["Программирование под Андроид"](https://javarush.ru/quests/QUEST_GOOGLE_ANDROID) на Java Rush
---


### Программа курса:

- #### Первое открытое занятие:

  - Установка Android Studio и Genymotion
  - Создание нового проекта
  - Hello World!
  - Layout
  - ImageView
  - Button
  - ClickListener
  - Смена Activity
  - Animation
  - AnimationListener
  - AnimationSet
  - Домашнее задание: HW_1
      - Добавление ресурсов
      - Создание и расположение кнопок
      - Создание нового Активити
      - Создание анимации 
          - TranslateAnimation
          - RotateAnimation
          - ObjectAnimator, AnimatorSet
      - SoundPool
      - TouchListener

- #### Занятие 2

  - Разбор HW_1
  - Lifecycle приложения на Android
  - Сохранение состояния Activity
  - Создание меню
  - AlertDialog
  - DataBase  SQLite
  - Shared Preferences
  - RecyclerView
  - Домашнее задание: HW_2
      - Shared Preferences
      - AlertDialog
      - Create DAO
      - RecyclerView
      - LifeCycle

- #### Занятие 3

  - Разбор HW_2
  - Receiver
  - AlarmManager
  - Handler
  - Notification
  - BootReceiver
  - ProgressBar
  - Домашнее задание: HW_3
      - ProgressBar
      - AlarmManager
      - Notification
      - ImageView

- #### Занятие 4

  - Разбор HW_3
  - DelegateAdapter
  - Title Bar
  - Spinner Adapter
  - Checkbox Selector
  - ExpandableListView
  - Context Menu
  - View Model
  - Live Data
  - AsyncTask
  - Executor
  - Landscape
  - Домашнее задание: HW_4
      - ListView
      - 
      - 

- #### Занятие 5 

  - Разбор HW_4
  - Локализация
  - Добавление коммерческой рекламы Admob
  - Публикация приложения в Google Play

---

# Занятие 1

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 1. [О проекте и установка ПО](https://drive.google.com/open?id=1_rCSROQjSxQ8dqpNgOKuAsQacN59KGf_)

- Установить ПО ([JDK8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html), [Git](https://git-scm.com/downloads), [**Android Studio**](https://developer.android.com/studio/), [**Genymotion**](https://www.genymotion.com))
- Создать аккаунт на [GitHub](https://github.com)
- **Прочитать [Wiki по ведению проекта в Git](https://github.com/JavaOPs/topjava/wiki/Git) !**

+ [Как установить JDK8](https://www.youtube.com/watch?v=D59Sd7D58F0) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>
+ [Установка GIT](https://www.youtube.com/watch?v=mpK_MYb38zs) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>

- [Установка Java 8 в Linux](https://www.youtube.com/watch?v=RgJQKZhD210) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>
- [Установка GIT в Linux](https://www.youtube.com/watch?v=f6b5p5ss1nA) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>
- [Установка Android Studio и Genymotion в Linux](https://www.youtube.com/watch?v=qgfiA7cEGmI) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>

#### Материалы:

- [Что такое Git](https://drive.google.com/file/d/0B9Ye2auQ_NsFSUNrdVc0bDZuX2s/edit) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>
- [Видео по обучению Git](https://www.youtube.com/playlist?list=PLIU76b8Cjem5B3sufBJ_KFTpKkMEvaTQR) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>
- [Основы Git за 20 минут](https://www.youtube.com/watch?v=TMeZGvtQnT8) <img src="https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png" width="15"/>

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 2. Hello World

- Сделать Fork **[ЭТОГО](https://github.com/qf05/Android_Lesson_1)** проекта
- **[Скачать патчи](https://drive.google.com/open?id=1WPWIwHDHmeuf93dWTtaHloWpvX1Xkb9s)**
- Применить 1_0_hello_world.patch (apply + commit)

#### Материалы:

- [Компоненты экрана](https://startandroid.ru/ru/uroki/vse-uroki-spiskom/13-urok-4-elementy-ekrana-i-ih-svojstva.html)
- [Layout](http://developer.alexanderklimov.ru/android/theory/layout.php)
- [LinearLayout](http://developer.alexanderklimov.ru/android/layout/linearlayout.php)
- [RelativeLayout](http://developer.alexanderklimov.ru/android/layout/relativelayout.php)
- [Единицы измерения](http://developer.alexanderklimov.ru/android/theory/scales.php)
- [ImageView](http://developer.alexanderklimov.ru/android/views/imageview.php)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 3. Смена активити

- Применить 1_1_other_activity.patch (apply + commit)

#### Материалы:

- [Activity](http://developer.alexanderklimov.ru/android/theory/activity-theory.php#what)
- [Button](http://developer.alexanderklimov.ru/android/views/button.php)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 4. Анимация

- Применить 1_2_animation.patch (apply + commit)

#### Материалы:

- [Анимация преобразований](http://developer.alexanderklimov.ru/android/animation/tweenanimation.php)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) 5. TranslateAnimation

- Применить 1_3_translate_animation.patch (apply + commit + **push**)

#### Материалы:

- [TranslateAnimation](http://developer.alexanderklimov.ru/android/animation/translateanimation.php)
- [Определение начальных размеров View в Android](http://poetofcode.ru/programming/2017/06/12/kak-opredelit-nachalnyue-razmeryu-view-v-android.html)

---

## ![hw](https://cloud.githubusercontent.com/assets/13649199/13672719/09593080-e6e7-11e5-81d1-5cb629c438ca.png) Домашнее задание HW_1

```
1. В git сделать ветку домашнего задания "HW_1".
2. Скачать ресурсы для HW_1 и разместить их в соответстующих директориях. 
Сделать commit.
```
[Ресурсы для HW_1](https://drive.google.com/drive/folders/1l4zY8PCY528RgwevUaoaclhuJDCrPasJ?usp=sharing)
```

3. Создать три кнопки "Dog", "Cat", "Cthulhu", и расположить их в activity_main таким образом:
```
<img src="https://lh3.googleusercontent.com/oRrkR0aRU-Yp9K5zDLVo2o6rkCKmhO8R8ZVyjIPvIBOyE9FQE1E1lIt7dwO4_HrNJynZfuGaUoSW0ZOGHwW-_NhXL-ChIS1oEoXBm_RdGMWQYsBKK4MO_iiTFModPWZ6KihWEJ6qy9rLQGQzkR4muRbDIlf3pFiCb7qMeoCYi_zx_6XfhoeI7kmI2OqLQFjubGuAqC_QZYW5oquMdob9ohIu_giQ6g4stK8HoiPEwJh94jynOa8vOUXtJgOAz9fFz5VSmuR73dCX47S-2p7fwYKoCvSBXjOKyyjWVObBPxcLOW3Ncxd8s59K29wVu38hzlqWRU3KRPwICg1mF_cg8883gkL7KPq4mGX8APbD2Utt1l1DMmggFwQYinhRa2GeEzM76lh84KEjrnvsinLp8DB-XGsHaqyIk0H_SX8vjM21Mi_SWzX3SG_YtESgmZV_ATUDpkCLHRXmsS6baM2d5oo7067PBCKewh5JCAESVbHpdOlbHg7CI-ezkz36xRxZuxW6KKYLr8cR2nHdaeKWFl3o4aUdzT4_X0UUgKk9Q5FZpZypWm8k3v7vYC-0qxtNvci8cd7XbPk6bjdGwtkA6WxzVfVx8YMxI9BT2BCi08mDAV7_z5N4sis4lBOUDFrkPeXBptpMiu99mkSEraGNNwuTBFAWmPM=w274-h460-no" width="250"/>

```
кнопки не должны менять свое относительное положение в зависимости от параметров экрана устройства. 
Сделать commit.

4. Создать новое Activity "WalkActivity", 
- создать layout файл для WalkActivity, в нем добавить ImageView с изображением fon_walk.jpg так же,
как это сделано в activity_other
- в MainActivity все три кнопки должны при нажатии менять активити на WalkActivity
- расположите в WalkActivity кнопку "home", для перехода обратно к MainActivity, дизайн кнопки 
сделайте такой же, как в activity_other
- расположите в WalkActivity ImageView в котором должно отображаться изображение того животного с 
названием которого была нажата кнопка в MainActivity. (размер ImageView подберите исходя из 
здравого смысла:))
- Примените к этому ImageView бесконечную анимацию перемещения по экрану в случайном направлении и 
на случайное расстояние. ImageView не должен заходить за края видимого экрана.
Сделать commit + push.
Отправить на проверку ДЗ. (для тех, кто оплатил проверку ДЗ)

5. Optional
- Сделать так, чтобы изображение животного в WalkActivity поворачивалось "лицом" в направлении 
движения.
Сделать commit.

6. Optional 2 (Задание со звёздочкой)
- Сделать так, что бы при нажатии на изображение животного воспроизводился соответствующий 
животному звук.
Сделать commit + push.

Отправить на проверку ДЗ. (для тех, кто оплатил проверку ДЗ)
```

<img src="https://i.yapx.ru/DWyV7.gif" width="250"/>

#### Подсказки к HW1

- [Работа с ресурсами](https://metanit.com/java/android/2.4.php)
- [Передача данных между Activity](http://developer.alexanderklimov.ru/android/activity.php#passdata)
- Для вычисления угла поворота используйте класс [Math](https://docs.oracle.com/javase/7/docs/api/java/lang/Math.html)
- [Play sound using SoundPool](https://stackoverflow.com/questions/17069955/play-sound-using-soundpool-example/27552576#27552576)
- [Класс SoundPool](http://developer.alexanderklimov.ru/android/theory/soundpool.php#builder)
- [Кто сказал Мяу? - работаем со звуками](http://developer.alexanderklimov.ru/android/whosaidmeow.php)
- Почитайте про класс [ObjectAnimator](https://developer.android.com/reference/android/animation/ObjectAnimator)
- [Коснись меня нежно](http://developer.alexanderklimov.ru/android/views/button.php#noborder)
- [PerformClick](https://stackoverflow.com/questions/47107105/android-button-has-setontouchlistener-called-on-it-but-does-not-override-perform)

---



### Дополнительные материалы:

[Анимация в Android](https://android-tools.ru/coding/animaciya-v-android/)

[Анимации в Android по полочкам](https://habr.com/ru/post/347918/)

[Animation и Transition](http://developer.alexanderklimov.ru/android/animation/)

[Анимации c помощью Transitions API](https://habr.com/ru/post/243363/)