# CustomStringList

Класс `CustomStringList` предоставляет функционал для работы с массивом строк.

## Использование

### Создание объекта

```java
// Создание объекта с передачей списка строк
String[] initialList = {"apple", "banana", "orange"};
CustomStringList customList = new CustomStringList(initialList);

// Создание пустого объекта
CustomStringList emptyList = new CustomStringList();
Методы
check(String str)
Метод check проверяет наличие строки в списке.

java
Copy code
boolean exists = customList.check("apple");
check(String[] arr)
Метод check проверяет наличие всех строк из переданного массива.

java
Copy code
String[] words = {"apple", "banana"};
boolean allExist = customList.check(words);
longestWord()
Метод longestWord возвращает самое длинное слово из списка.

java
Copy code
String longest = customList.longestWord();
getList()
Метод getList возвращает весь список строк.

java
Copy code
String[] allWords = customList.getList();
add(String str)
Метод add добавляет строку в список.

java
Copy code
customList.add("grape");
addIfNotExists(String str)
Метод addIfNotExists добавляет строку в список, если ее там еще нет.

java
Copy code
customList.addIfNotExists("apple");
Важно
Класс реализует функционал работы с массивом строк и предоставляет методы для проверки наличия, добавления и получения строк.

go
Copy code

Этот README поможет пользователям понять, как использовать `CustomStringList` и какие методы предоставляются этим классом.




