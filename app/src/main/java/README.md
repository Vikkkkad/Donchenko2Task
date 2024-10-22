# Лабораторная работа №2. Основы верстки
## Выполнила: Донченко Вика, ИСП-211о
## Язык программирования: Java

### 1. Функции приложения
Приложение состоит из 4 экранов:
- "Меню" (MainActivity).
![1activity.png](..%2F..%2F..%2F..%2F1activity.png)
- "Экран 2" (MainActivity2).
![activity2.png](..%2F..%2F..%2F..%2Factivity2.png)
- "Экран 3" (MainActivity3).
![activity3.png](..%2F..%2F..%2F..%2Factivity3.png)
- "Экран 4" (MainActivity4).
![activity4_1.png](..%2F..%2F..%2F..%2Factivity4_1.png)

### 2. Меню
Меню состоит из 4х кнопок:
- "Перейти к экрану 2" (при нажатии открывается MainActivity2).
- "Перейти к экрану 3" (при нажатии открывается MainActivity3).
- "Перейти к экрану 4"(при нажатии открывается MainActivity4).
- "Выйти" (при нажатии происходит выход из приложения).
![1activity.png](..%2F..%2F..%2F..%2F1activity.png)

### 3. Второй экран
Второй экран сверстан с использованием `LinearLayout`.
Он состоит из 7 кнопок:
- 3 расположены в верхней части экрана 
`android:layout_gravity="top"`
- 2 расположены по центру 
`android:layout_gravity="center"`
- 3 расположены в нижней части экрана 
`android:layout_gravity="bottom"`
![activity2.png](..%2F..%2F..%2F..%2Factivity2.png)

### 4. Третий экран
Третий экран сверстан с использованием `RelativeLayout`.
Он состоит из 6 кнопок:
- 2 расположены в верхней части экрана и занимают по половине экрана
`android:layout_toLeftOf = "@+id/view"`
- `android:layout_toRightOf="@+id/view"`
- 3 расположены по центру
`android:layout_centerInParent="true"`
`android:layout_toLeftOf="@+id/button15"`
`android:layout_toRightOf="@+id/button15"`
- 1 расположена в нижней части экрана
![activity3.png](..%2F..%2F..%2F..%2Factivity3.png)

### Четвертый экран
На четвертом экране расположена 1 темно-зеленая кнопка, на кодорой изображена иконка приложения. Так как я родилась в августе, то толщина обводки `8px`. При нажатии на кнопку ее цвет изменяется на светло-зеленый. 
![activity4_1.png](..%2F..%2F..%2F..%2Factivity4_1.png)
![activity4_2.png](..%2F..%2F..%2F..%2Factivity4_2.png)
Внутри папки `drawable` был создан файл `my_button` для того, чтобы кнопка приобрела данные функции.
