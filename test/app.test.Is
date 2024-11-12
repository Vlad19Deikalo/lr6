const express = require('express');     
const app = express(); 

// Правильна стрілочна функція
app.get('/', (req, res) => {
    res.send('Hello World!');
});

// Використовуємо порт з environment variables або 3000 за замовчуванням
const port = process.env.PORT || 3000;

// Запускаємо сервер
app.listen(port, () => {
    console.log(`App listening at http://localhost:${port}`);
});
