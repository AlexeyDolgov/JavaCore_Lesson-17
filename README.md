# JavaCore_Lesson-17
Inner Classes (Nested, Local, Anonymous)

* [Завдання](https://github.com/AlexeyDolgov/JavaCore_Lesson-17/tree/master/JavaCore_Lesson-17/src/ua/lviv/lgs/task17)<br>
Створити інтерфейс <i>Iterator</i>, в якому оголосити методи hasNext(), next().<br><br>
Створити клас <i>Collection</i>, в якому оголосити як поле масив типу Number. Створити конструктор з визначеними параметрами, куди
передати даний масив. Створити два <i>внутрішніх класи</i>, які імплементуватимуть інтерфейс Iterator. Перевизначити методи так, щоб:<br>
• перший клас виводив значення масиву від першого до останнього. Зробити заміну непарних елементів на нуль і вивести на екран даний
масив.<br>
• другий клас виводив значення масиву від останнього до першого через одну цифру.<br><br>
Створити <i>анонімний клас</i>, який повинен прогнати від останнього до першого елементу масиву. Перевірити кожен третій елемент масиву
від останнього, чи він непарний. Якщо так, то вивести дані елементи на консоль.<br><br>
Створити <i>локальний клас</i>, який повинен пройтись від першого до останнього елементу масиву. Перевірити кожен п’ятий елемент масиву,
чи він парний. Якщо так, то відняти від нього число 100 і вивести на консоль ці числа.<br><br>
Створити <i>статичний клас</i>, який повинен пройтись від першого до останнього елемента масиву. Перевірити кожен другий елемент масиву
на парність. Якщо він парний, тоді зробити з нього непарний і вивести дані елементи на консоль.<br><br>
