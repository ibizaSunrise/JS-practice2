# JS practis2

### 48. Задачи на работу с JSON на JavaScript
1. Дана JSON строка '["Коля", "Вася", "Петя"]'. Преобразуйте ее в массив JavaScript и выведите на экран элемент "Петя".

2. Дан объект {a: 'aaa', b: 'bbb'}. Преобразуйте его в JSON

### 49. Задачи на работу с куки (cookie) на JavaScript

Основы работы

1. Установите куку с именем 'name' и значением 'Иван'. Выведите содержимое этой куки на экран. 

2. Установите куку с вашем именем и вашим возрастом. Выведите на экран содержимое этих двух кук. 

Практика

3. Дан инпут. Ведите в него город, например, Минск. Сохраните его в куки. Зайдя на другую страницу сайта вы должны увидеть фразу 'ваш город - Минск'.

4. При заходе на страницу спросите с помощью инпута день рождения пользователя. Когда он зайдет с следующий раз - напишите сколько месяцев, дней, часов, минут и секунд осталось до его дня рождения. И пусть по этим числам запуститься обратный отсчет (то есть они будут тикать).

5. Дана форма с инпутами. Пользователь вводит какие-то данные и закрывает страницу (не факт, что он заполнил всю форму). Сделайте так, чтобы при следующем заходе на страницу введенные им ранее данные стояли на своих местах.

6. Даны чекбоксы. Пользователь произвольно отмечает их и закрывает страницу. Сделайте так, чтобы при следующем заходе на страницу чекбоксы стали отмеченными так, как это сделал пользователь ранее. 

7. При заходе на страницу появляется счетчик обратного отсчета. Когда он доходит до нуля, на странице пишется - 'отсчет закончен'. При обновлении страницы счетчик не должен начинать идти заново. 

8. Дан тектареа. Пользователь может потянуть за его угол и изменить его размер. Сделайте так, чтобы при следующем заходе на страницу, текстареа был заданного размера.

9. Дан инпут. В него можно ввести данные, затем поредактировать их, затем еще поредактировать. Пусть инпут хранит историю своих изменений (даже после перезагрузки страницы). Сверху над инпутом должны появится стрелочки, с помощью которых можно перемещаться по истории. 

10. Дан сайт. Пусть каждая страница для каждого посетителя хранит время последнего захода и количество заходов на нее этим посетителем. Пусть эти данные показываются при заходе в формате 'с последнего захода прошло ... вы посещали эту страницу ... раз'. 

11. Пусть по заходу на страницу показывается определенный рекламный текст. Рядом с ним сделайте кнопку 'убрать', по нажатию на которую этот рекламный текст не показывается этому пользователю ровно один день.

## 50. Задачи на работу с локальным хранилищем на JavaScript

1. Дан текстареа. В него вводится текст. Сделайте так, чтобы после захода на эту страницу через некоторое время, введенный текст остался в текстареа. Текст должен запоминаться в локальном хранилище.

2. Дан текстареа. В него можно ввести данные, затем поредактировать их, затем еще поредактировать. Пусть текстареа хранит историю своих изменений (даже после перезагрузки страницы). Сверху над текстареа должны появится стрелочки, с помощью которых можно перемещаться по истории.

3. Дана форма с инпутами, текстареа, чекбоксами, радио кнопочками, селектами и тп. Пользователь вводит какие-то данные и закрывает страницу (не факт, что он заполнил всю форму). Сделайте так, чтобы при следующем заходе на страницу введенные им ранее данные стояли на своих местах. Сделайте ваш скрипт как можно более универсальным.

4. Реализуйте записную книгу, хранящую данные в локальном хранилище.

5. Реализуйте органайзер, хранящий данные в локальном хранилище.

## 53. Canvas

1. На линии, методы lineTo, moveTo, beginPath, closePath, stroke, fill. Задания 53.01- 53.08

2. На фигуры fillRect, strokeRect, clearRect, rect, stroke, fill, arc. Задания 53.09 -53.19

3. На смену цвета: fillStyle, strokeStyle. Задания 53.20 -53.23

4. На циклы 53.24 -

5. Анимация пчелы, мячика.

### 57. Pаботa с контекстом в JavaScript(call, apply, bind)

### 74. Тип Symbol

1. Пусть дан объект. Создайте символ и добавьте в объект еще один элемент, ключом которого будет созданный символ, а значением - какая-нибудь строка. Переберите объект через цикл for-in, убедитесь в том, что новый элемент не появляется при переборе.
2. Пусть дан объект. Добавьте в него еще один элемент, значением которого будет функция, выводящая на экран '!', а ключом - созданный вами символ.
3. Пусть дан объект, ключами которого являются какие-то строки, а значением - числа. Добавьте в наш объект функцию, которая будучи вызванной будет возвращать сумму элементов нашего объекта.
4. Пусть дан массив с числами. Добавьте в этот массив функцию, которая будет возвращать сумму элементов этого массива. Сделайте так, чтобы наша функция имела символьный ключ.
5. Переделайте предыдущую задачу так, чтобы ключ-символ для функции задавался через Symbol.for.
6. Пусть у нас есть скрипт. В этом скрипте есть функция, которая возвращает массив, заполненный случайными числами от 1 до 10. В этом скрипте также есть функция, которая параметром принимает два массива с числами и возвращает массив элементов, которые есть в обоих массивах. Сделайте так, чтобы массивы, возвращаемые любой из функций нашего скрипта, содержали функцию, возвращающую сумму чисел этого массива. Ключ этой функции должен быть одинаковым для всех массивов, то есть созданным через Symbol.for.

### 75. Итераторы и генераторы


## Promise ES6

### 76. Функции resolve и reject

1. Сделайте промис, внутри которого будет задержка setTimeout в 3 секунды, после которой промис должен зарезолвится (то есть выполнится успешно).
2. Сделайте промис, внутри которого будет задержка setTimeout в 3 секунды, после которой промис должен зареджектится (то есть выполнится с ошибкой).
3. Сделайте функцию, которая будет генерировать случайные числа от 1 до 10. Сделайте так, чтобы сгенерированное число было задержкой функции setTimeout в секундах. Оберните все это в промис. Пусть промис выполнится успешно, если сгенерировано число от 1 до 5, и с ошибкой - если от 6 до 10.

### 77. Метод catch

1. Сделайте промис, который через 5 секунд случайным образом выполнится или с успехом, или с ошибкой. Примените изученный метод catch для отлавливания ошибок.

### 78. Цепочки промисов

1. Сделайте цепочку из трех промисов. Пусть первый промис возвращает число. Сделайте так, чтобы каждый последующий промис через 3 секунды возводил в квадрат результат предыдущего промиса. После окончания манипуляций выведите число алертом на экран.

### 79. Обработка ошибок

1. Переделайте предыдущую задачу так, чтобы один из промисов в цепочке выполнился с ошибкой. В конце цепочки расположите метод catch, который поймает эту ошибку.

### 80. Работа с Promise.all

1. Сделайте 3 промиса, в каждом из которых расположена функция setTimeout со случайно задержкой от 1 до 5 секунд. Пусть каждый промис своим результатом возвращает эту задержку. С помощью Promise.all получите массив результатов, найдите его сумму, выведите на экран.

### 81. Работа с Promise.race

1. Сделайте 3 промиса, в каждом из которых расположена функция setTimeout со случайно задержкой от 1 до 5 секунд. Пусть первый промис возвращает число 1, второй - число 2, третий - число 3. С помощью Promise.race дождитесь загрузки первого сработавшего промиса и выведите результат его работы на экран.

### 82. Promise async await

1. Сделайте функцию getNum, которая возвращает промис, который с задержкой в 3 секунды выведет случайное число от 1 до 5. Создайте async функцию, которая с помощью await будет дожидаться результата getNum, затем возводить его в квадрат и выводить на экран.

2. Сделайте функцию getNum1, которая возвращает промис, который с задержкой в 3 секунды выведет случайное число от 1 до 5. Сделайте также функцию getNum2, которая возвращает промис, который с задержкой в 5 секунд выведет случайное число от 6 до 10. Создайте async функцию, которая с помощью await будет дожидаться результата getNum1, затем будет дожидаться результата getNum2, а затем найдет сумму полученных чисел и выведет на экран.

### 83. Загрузка картинок через промисы

Даны 3 картинки. С помощью Promise.all дождитесь окончания загрузки всех картинок и выведите их на экран.
