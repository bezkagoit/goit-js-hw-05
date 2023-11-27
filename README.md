# goit-js-hw-05

Задача 1. Імена користувачів Напиши стрілочну функцію getUserNames(users), яка
прийматиме один параметр users — масив об’єктів користувачів. Функція має
повертати масив імен усіх користувачів (властивість name) із масиву users.

1. Оголошена змінна getUserNames Змінній getUserNames присвоєна стрілочна
   функція з параметром (users).
2. Для перебирання параметра users використовується метод map()
3. Виклик функції із зазначеним масивом користувачів повертає масив ["Moore
   Hensley", "Sharlene Bush", "Ross Vazquez", "Elma Head", "Carey Barr",
   "Blackburn Dotson", "Sheree Anthony"]
4. Виклик функції з випадковими, але валідними аргументами повертає правильне
   значення

Задача 2. Користувачі з другом Напиши стрілочну функцію
getUsersWithFriend(users, friendName) , яка прийматиме два параметра:

перший параметр users — масив об’єктів користувачів другий параметр friendName —
ім’я друга для пошуку. Функція має повертати масив усіх користувачів із масиву
users, у яких є друг з іменем friendName. Друзі кожного користувача зберігаються
у властивості friends. Якщо користувачів, у яких є такий других немає, то
функція має повернути порожній масив.

Поради:

Метод filter() можна використовувати для створення нового масиву з елементами,
які задовольняють певну умову. Використовуй метод includes() для перевірки, чи
масив friends містить friendName.

1. Оголошена змінна getUsersWithFriend
2. Змінній getUsersWithFriend присвоєна стрілочна функція з параметрами (users,
   friendName)
3. Для перебирання параметра users використовується метод filter()
4. Якщо значення параметра friendName — це рядок "Briana Decker", функція
   повертає масив об'єктів користувачів з іменами Sharlene Bush і Sheree Anthony
5. Якщо значення параметра friendName — це рядок "Goldie Gentry", функція
   повертає масив об'єктів користувачів з іменами Elma Head і Sheree Anthony
6. Якщо значення параметра friendName — це рядок "Adrian Cross", функція
   повертає порожній масив Виклик функції з випадковими, але валідними
   аргументами повертає правильне значення

Задача 3. Сортування за кількістю друзів Напиши стрілочну функцію
sortByDescendingFriendCount(users) , яка прийматиме один параметр users — масив
об’єктів користувачів.

Функція має повертати масив усіх користувачів, відсортованих за спаданням
кількостій їх друзів (властивість friends).

1. Оголошена змінна sortByDescendingFriendCount
2. Змінній sortByDescendingFriendCount присвоєна стрілочна функція з параметром
   (users)
3. Для перебирання параметра users використаний метод toSorted()
4. Виклик функції із зазначеним масивом users повертає новий масив користувачів,
   відсортований за спаданням кількості їхніх друзів
5. Виклик функції з випадковими, але валідними аргументами повертає правильне
   значення

   Задача 4. Загальний баланс Напиши стрілочну функцію
   getTotalBalanceByGender(users, gender), яка прийматиме два параметра:

перший параметр users — масив об’єктів користувачів, другий параметр gender —
рядок, що зберігає стать. Функція має використовувати ланцюжок виклику методів
та повертати загальний баланс користувачів (властивість balance), стать яких
(властивість gender) збігається зі значенням параметра gender.

1. Оголошена змінна getTotalBalanceByGender
2. Змінній getTotalBalanceByGender присвоєна стрілочна функція з параметрами
   (users, gender)
3. У тілі функції використовується ланцюжок методів у правильному порядку
4. Значення параметра users не змінюється
5. Якщо значення параметра gender — це рядок "male", функція повертає число
   12053
6. Якщо значення параметра gender — це рядок "female", функція повертає число
   8863
7. Виклик функції з випадковими, але валідними аргументами повертає правильне
   значення
