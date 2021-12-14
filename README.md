# Web_Tutorial

- `Element` - ochuvchi  < **tag** >, content va yopuvchi  < /**tag** > dan tashkil topgan struktura.
- `Emptiy` `element` - faqatgina ochuvchi tagdan tashkil topgan element.
- `Nested` `element` - boshqa element ichida joylashgan element.
- `Attribute` - element haqida qo'shimcha ma'lumot beruvchi maxsus so'zlar.
- `Headings` - veb sahifa sarlavha ko'rsatish uchun mo'ljallangan maxsus < **tag** >lar.
- `Paragraphs` - veb sahifa matn chiqarish uchun mo'ljallangan maxsus < **tag** >. < Paragraph >lar har doin xat boshidan ( *abzast* ) boshlanadi .
- `Style` - Html da Style berish .

```html
	<tag-nomi style="property1: value1; property2: value2">Contentc</tag-nomi>

	**Misol**:
	<p style="color: red; text-align: center"> qizil rangdagi o'rtada joylashgan matn </p>
```

- `Inline` Styles - yuqridagi style berish usuli .
- `Internal` Styles -  < **style**> p{ } h1{ } </**style**> taglarida orasida yoziladi . Barcha <p> ..... taglariga style beradi.
- `External` Styles - < **link** > tagi orqali - `Css` file ni bog'lash(relationsheep).

```html
<link rel="stylesheet" herf="stillar.css">
```

- `anchor` tag - < **a** href="2-sahifa.html"> o'tish-link </**a**> - `Relative` path
- `absolute` path  - < **a** href="https://google.com"> o'tish-link </**a**>
- `Target` atribute - < **a** href="https://google.com" target="_blank"> o'tish-link </**a**> - yangi oynada ochib berish uchun.
- `Table` —> **Thead** ( Jadval boshi ) —> **tr** ( Jadval qatori ) —> **th** ( table head data - jadval boshi ma'lumoti ) —> **tbody** ( table body  ) —> **td** ( table date )
- `Id` : id nomi orqali stillash.

```html
<p id="birinchi"> Lorem ipsum </p>
<style>
#birinchi{
	color: red;
}
</style>
```

- `Class` lar - id dan farqi bunda guruhlash mumkun va bir class ga 1 dan ortiq  class ni ham berish mumkun  —> **class**="**qizil** center" (orasida hech qanday belgi bo'lmaydi).

```html
<p class="qizil"> Lorem ipsum </p>
<style>
.qizil{
	color: res;
}
</style>
```
`Block` elementlar -  *Har doim yangi qatordan boshlanadi.*

- **Block elementlar ro'yhati**
    - `<article>`
    - `<aside>`
    - `<dd>`
    - `<div>`
    - `<footer>`
    - `<from>`
    - `<h1>`-`<h6>`
    - `<header>`
    - `<hr>`
    - `<li>`
    - `<main>`
    - `<nav>`
    - `<ol>`
    - `<p>`
    - `<section>`
    - `<table>`
    - `<ul>`
    - `<video>`

`Inline` elementlar - *ekranda faqatgina o'ziga yetarli joyni oladi va boshqa inline element yoniga joylashaveradi.*

- **Inline elementlar ro'yhati**
    - `<a>`
    - `<b>`
    - `<br>`
    - `<button>`
    - `<i>`
    - `<img>`
    - `<input>`
    - `<label>`
    - `<select>`
    - `<small>`
    - `<span>`
    - `<strong>`
    - `<sub>`
    - `<sup>`
    - `<textarea>`

`div` - *konteyner deb tushunsa bo'ladi. Bu block element hisoblanib o'z ichiga Block va inline elementlarni oladi.*

`span` - *inline inline elementlar uchun Konteyner .*

- `Form` "tagi" —> **label** , **input**, **button**, ***for***(atributi).
    - `Input`
        - `<input type="button">`
        - `<input type="checkbox">`
        - `<input type="color">`
        - `<input type="date">`
        - `<input type="datetime-local">`
        - `<input type="email">`
        - `<input type="file">`
        - `<input type="hidden">`
        - `<input type="image">`
        - `<input type="month">`
        - `<input type="number">`
        - `<input type="password">`
        - `<input type="radio">`
        - `<input type="range">`
        - `<input type="reset">`
        - `<input type="search">`
        - `<input type="submit">`
        - `<input type="tel">`
        - `<input type="text">`
        - `<input type="time">`
        - `<input type="url">`
        - `<input type="week">`
        - 
        
        ```html
        <form action="/server.dotnet">
              <label for="username">Username</label>
              <input type="text" name="username" id="username"> <br><br>
              <label for="password">Password</label>
              <input type="password" name="password" id="password"> <br><br>
              <label for="data">Data</label>
              <input type="date" name="data" id="data"> <br><br>
              <label for="email">Email</label>
              <input type="email" name="email" id="email"> <br><br>
              <label for="image">Image</label>
              <input type="file" name="image" id="image"> <br><br>
              <label for="search">Search</label>
              <input type="search" name="search" id="search"> <br><br>
              <label for="tel">Tel</label>
              <input type="tel" name="tel" id="tel"> <br><br>
              <hr>
              <label for="student">Student</label>
              <input type="checkbox" name="student" id="student"> <br><br>
              <label for="erkak">Erkak</label>
              <input type="radio" name="gender" value="male"> 
              <label for="ayol">Ayol</label>
              <input type="radio" name="gender" value="female"> <br><br>
              <input type="submit" value="Submit">
              <input type="button" onclick="alert('Hello World!')" value="Click Me!">
        </form>
        ```
        
    - `select`
    - lable
    - textarea
    - button
    - option
    
- `Head` Elementlari
    - `title`
    - `style`
    - `link`
        
        ```html
        <link rel="stylesheet" href="./stillar.css">
        <link rel="icon" type="image/png" href="../CSS-Cheat-Sheet-OverAPI.com_.png">
        ```
        
    - `meta`
        
        ```html
        <meta charset="UTF-8">
        <meta name="keywords" content="HTML darslar, CSS darslar, Dasturlash">
        <meta name="auther" content="Xakimov Nosirbek">
        <meta name="description" content="Dasturlash bo'yicha kurslar web sahifasi">
        ```
        
    - `script`
        
        ```html
        <script>
            alert('JavaScript yuklandi (ok) ni bosing');
        </script>
        ```
        
- `Layouts` - Planirovka
    
    ![photo_2021-12-13_12-13-31.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b04e999-72bb-4728-b54e-646530c147d3/photo_2021-12-13_12-13-31.jpg)
    
    ```html
    <!DOCTYPE html>
    <html>
        <head>
            <title>Layout</title>
            <style>
                .box{
                    background-color: blue;
                    font-size: 20px;
                    color: white;
                    text-align: center;
                    margin-top: 1px;
                }
                header{
                    height: 100px;
                    line-height: 100px;
                }
                nav{
                   
                    height: 100px;
                    line-height: 100px;
                }
                section{
                    height: 500;
                    line-height: 500px;
                    width: 70%;
                    float: left;
                    
                }
                aside{
                    height: 500;
                    line-height: 500px;
                    width: 30%;
                    float: left;
                }
                footer{
                    height: 100px;
                    margin-top: 1px;
                    line-height: 100px;
                    width: 100%;
                    float: left;
                }
            </style>
        </head>
        <body>
            <header class="box">
                Header
            </header>
            <nav class="box">
                Nav
            </nav>
            <section class="box">
                Section
            </section>
            <aside class="box">
                Aside
            </aside>
            <footer class="box">
                Footer
            </footer>
        </body>
    </html>
    ```
    
- `Semantics` - Ma'noli elementlar
    
    ![photo_2021-12-13_12-15-06.jpg](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ed719b12-9dbc-4e96-9833-bfade14244b3/photo_2021-12-13_12-15-06.jpg)

- `Best Practices` - Qoidala
    - 1 Kod youzish bo'yicha qoidalar
        - Hamma <<`tag`>> larni kichik xarf bilan yozing
        - <<`Indentation`>> dan ( otstup ) to'g'ri foydalaning
    - 2 Inline style'lar ishlatmang
    - 3 Rasm uchun <<`alt`>> attributini ko'rsatib o'ting
    - 4 Har bir sahifada bittadan ko'p bo'lmagan <`h1`> elementi ishlating
    - 5 <`title`> va <`meta`> elementlarida to'g'ri foydalaning
    - 6 `HTML` validatorlaridan foydalaning
        
        [https://validator.w3.org](https://validator.w3.org/)