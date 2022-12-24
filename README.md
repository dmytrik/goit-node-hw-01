# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
![1](https://user-images.githubusercontent.com/107771156/209438449-ed973541-3eb9-4835-8ff1-56a7d1ea3bdf.PNG)


# Отримуємо контакт по id
node index.js --action="get" --id=5
![2](https://user-images.githubusercontent.com/107771156/209438488-7a55899b-155d-4956-936d-ac7cc7c807f4.PNG)


# Додаємо контакт
node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22"
![3](https://user-images.githubusercontent.com/107771156/209438500-b798d5ef-1473-4a02-bf53-49f42fdcc48a.PNG)
![3-1](https://user-images.githubusercontent.com/107771156/209438502-7fa17eb9-d034-4ab1-bfb1-ac2530abbbae.PNG)

# Видаляємо контакт
node index.js --action="remove" --id=3
![4](https://user-images.githubusercontent.com/107771156/209438505-07da00cd-6788-4368-8634-50452397cca5.PNG)
![4-1](https://user-images.githubusercontent.com/107771156/209438508-3f880f1c-8b16-40da-b3d2-1889852d051d.PNG)
