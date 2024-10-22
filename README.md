# Лабораторная работа №2. Основы верстки
## Выполнила: Донченко Вика, ИСП-211о
## Язык программирования: Java

### 1. Функции приложения
Приложение состоит из 4 экранов:
- "Меню" (MainActivity).

![1activity](https://github.com/user-attachments/assets/695ed1f6-8b41-4a5d-940b-6ac52b3740bb)

- "Экран 2" (MainActivity2).

![activity2](https://github.com/user-attachments/assets/bd61166b-ef54-4440-80a3-4e978227ec83)

- "Экран 3" (MainActivity3).

![activity3](https://github.com/user-attachments/assets/d66a4469-c1fd-4c60-9906-45d8768dcb4b)

- "Экран 4" (MainActivity4).

![activity4_1](https://github.com/user-attachments/assets/8117b134-462e-4d6e-a2b1-02680161cc54)


### 2. Меню
Меню состоит из 4х кнопок:
- "Перейти к экрану 2" (при нажатии открывается MainActivity2).
- "Перейти к экрану 3" (при нажатии открывается MainActivity3).
- "Перейти к экрану 4"(при нажатии открывается MainActivity4).
- "Выйти" (при нажатии происходит выход из приложения).

![1activity](https://github.com/user-attachments/assets/00ab473b-9539-4299-9206-67285949a730)


### 3. Второй экран
Второй экран сверстан с использованием `LinearLayout`.
Он состоит из 7 кнопок:
- 3 расположены в верхней части экрана 
`android:layout_gravity="top"`
- 2 расположены по центру 
`android:layout_gravity="center"`
- 3 расположены в нижней части экрана 
`android:layout_gravity="bottom"`

![activity2](https://github.com/user-attachments/assets/54ec7dfc-3b2c-49f9-91c7-7b15aa07bae1)


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

![activity3](https://github.com/user-attachments/assets/a5839dd6-f640-475f-9ed4-4509ef33f976)


### 5. Четвертый экран
На четвертом экране расположена 1 темно-зеленая кнопка, на кодорой изображена иконка приложения. Так как я родилась в августе, то толщина обводки `8px`. При нажатии на кнопку ее цвет изменяется на светло-зеленый. Внутри папки `drawable` был создан файл `my_button` для того, чтобы кнопка приобрела данные функции.

![activity4_1](https://github.com/user-attachments/assets/675c78ff-2209-4771-af6e-5bffd740513c)

![activity4_2](https://github.com/user-attachments/assets/7fae4b16-94af-42ab-bec3-8974e9337aa8)

