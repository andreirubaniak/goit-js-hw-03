# goit-js-hw-03

Задача 3-1
CRUD для свойств объекта
С - create (создать)
R - read (читать)
U - update (обновить)
D - delete (удалить)
Напиши скрипт, который, для объекта user, последовательно:

добавляет поле 'mood' со значением 'happy'
добавляет поле 'full time' со значением true
заменяет значение 'hobby' на 'skydiving'
заменяет значение 'premium' на false
в переменную message записывает содержимое объекта user:
для переменной keys присваивает массив свойств объекта, используя метод Object.keys()
с помощью оператора for...of
в формате ключ:значение
c переносом строки ('\n')

Задача 3-2
Подсчет количества свойств в объекте
Напиши функцию countProps(obj), которая возвращает число - количество свойств в объекте.

Циклы не должны использоваться

Задача 3-3
Поиск наибольшего значения среди свойств объекта
Напиши функцию findBestEmployee(employees), которая принимает объект сотрудников и возвращает имя самого продуктивного (который выполнил больше всех задач). 
Сотрудники и кол-во выполненных задач содержатся как свойства объекта в формате "имя":"кол-во задач".

Задача 3-4
Суммирование значений свойств объекта
Напиши функцию countTotalSalary(employees) принимающую объект зарплат. Функция считает общую сумму зарплаты работников и возвращает ее. 
Каждое поле объекта, передаваемого в функцию, имеет вид "имя":"зарплата".

Задача 3-5
Оператор in и метод push
Напиши функцию getAllPropValues(arr, prop), которая получает массив объектов и имя свойства.

Функция возвращает массив значений определенного свойства prop из каждого объекта в массиве.

Используй метод push для добавления значения в массив и оператор in для проверки наличия свойства в объекте.

Задача 3-6
Суммирование значений свойства из массива объектов
Напиши функцию calculateTotalPrice(allProdcuts, productName), которая получает массив объектов и имя продукта (значение свойства name). Возвращает общую стоимость продукта (цена умноженная на количество).

Вызовы функции для проверки работоспособности твоей реализации.

// calculateTotalPrice(products, 'Радар'));
// 9080

// calculateTotalPrice(products, 'Сканер')); // 10200

// calculateTotalPrice(products, 'Захват')); // 2400

// calculateTotalPrice(products, 'Дроид')); // 2800
