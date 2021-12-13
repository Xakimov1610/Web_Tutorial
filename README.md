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
    
    ```html
    <form action="/server.dotnet" method="get">
          <label for="username">Username</label>
          <input type="text" name="username" id="username"><br><br>
          <label for="password">Password</label>
          <input type="password" name="password" id="password"><br><br>
          <button type="submit">Login</button>
     </form>
    ```