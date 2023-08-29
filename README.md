# Node.js-hw-01
1. Получаем и выводим весь список контактов в виде таблицы (console.table) 
   node index.js --action list - https://monosnap.com/file/RfQbj2mWZXHh73OpoR2O2SlU80PB7J
2. Получаем контакт по id - выводим в консоль объект контакта или null, если контакта с таким id не существует.
   node index.js --action get --id 05olLMgyVQdWRwgKfg5J6 - https://monosnap.com/file/zvpmth5SPNoyFg9CFGktW7FycUzTbF
3. Добавляем контакт и выводим в консоль созданный контакт
   node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22 - https://monosnap.com/file/QzrhWzsfY1rbnGU4Y86GBaCxZ3qNPe
4. Удаляем контакт и выводим в консоль удаленный контакт или null, если контакта с таким id не существует.
   node index.js --action remove --id qdggE76Jtbfd9eWJHrssH - https://monosnap.com/file/L2XPDWLNwz4aA6A5YQZZ0ZAUge2XFp
