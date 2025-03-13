<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Платформа для криптовалюты</title>
    <style>
        body { font-family: Arial, sans-serif; }
        .hidden { display: none; }
    </style>
</head>
<body>

<h2>Введите пароль для доступа</h2>
<input type="password" id="password" placeholder="Пароль">
<button onclick="checkPassword()">Войти</button>

<div id="content" class="hidden">
   <h2>Что такое криптовалюта?</h2>
    <p>Криптовалюта — это цифровая или виртуальная валюта, использующая криптографию для обеспечения безопасности. Она децентрализована и основана на технологии блокчейн, что позволяет проводить транзакции без необходимости в центральном банке или другом финансовом учреждении.</p>
</section>

<section>
    <h2>Популярные криптовалюты</h2>
    <ul>
        <li><strong>Bitcoin (BTC)</strong> - первая и наиболее известная криптовалюта.</li>
        <li><strong>Ethereum (ETH)</strong> - платформа для создания смарт-контрактов и децентрализованных приложений.</li>
        <li><strong>Ripple (XRP)</strong> - криптовалюта, ориентированная на банковский сектор.</li>
        <li><strong>Litecoin (LTC)</strong> - создана как "легкая версия" Bitcoin.</li>
    </ul>
</section>

<section>
    <h2>Преимущества криптовалют</h2>
    <ol>
        <li>Децентрализация и независимость от центральных банков.</li>
        <li>Анонимность транзакций.</li>
        <li>Низкие комиссии за переводы.</li>
        <li>Быстрые международные переводы.</li>
    </ol>
</section>
     <h2>Создатель криптовалюты</h2>
<p>Александр Литяев - родился 14 мая 2007 года в городе Балаково Саратовская область. Первые 9 классов он учился в МАОУ Лицей 1. После того как Александр расстался с Соней Макуриной, он перевелся в 28 школу, далее работал веб разработчиком в компании Google. После этого он создал компанию Apple и наконец, в 2022 году он создал криптовалюту.</p>
<p> Помощником Александра Литяева является специалист по бинарке, и главный трейдер мира ДМИТРИЙ ХАЙРУТДИНОВ </p>
<img src="https://content.foto.my.mail.ru/mail/lityaev.a/_myphoto/h-1.jpg" alt="Создатель криптовалюты"
width="600" height="1000"


<footer>
</footer>
</div>

<script>
    function checkPassword() {
        var password = document.getElementById('password').value;
        var correctPassword = 'Фаристый'; // Замените 'ваш_пароль' на нужный вам пароль
        if (password === correctPassword) {
            document.getElementById('content').classList.remove('hidden');
            document.getElementById('password').style.display = 'none';
            document.querySelector('button').style.display = 'none';
        } else {
            alert('Неправильный пароль!');
        }
    }
</script>
</head>
<body>



</body>
</html>
