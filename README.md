CLI Contacts App (GoIT Node.js Homework)

Цей проєкт — консольний застосунок для роботи з колекцією контактів.
Реалізовано перегляд усіх контактів, пошук за ID, додавання та видалення контактів.

Функціональність:
list — отримання списку контактів (вивід у форматі console.table)
get — пошук контакту за ID
add — додавання нового контакту
remove — видалення контакту за ID

Уся логіка роботи з файлами винесена в окремий модуль contacts.js і реалізована через fs/promises.
Командний інтерфейс побудовано на основі пакета commander.

Приклади запуску:
 node index.js -a list
 node index.js -a get -i <id>
 node index.js -a add -n Mango -e mango@gmail.com -p 322-22-22
 node index.js -a remove -i <id>
