Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list" https://monosnap.com/file/exteoeLAKrrBKx99al58dR5DBy76dw

Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6 https://monosnap.com/file/8O5nqV5bbYi282P3BsTBdyNPtB8fKx

Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22 https://monosnap.com/file/h7k2lGdYaMZM0pq1gRYHXwHBVrlZTf

Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH https://monosnap.com/file/6ONcqNXD7KdZyNwIIM4kTkheySKDbD