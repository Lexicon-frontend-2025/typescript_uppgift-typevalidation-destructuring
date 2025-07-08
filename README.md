# 🧪 Övningar – Destructuring & Formulärvalidering

## 🧩 1. Enkel Objekt-Destructuring

```js
const person = {
  firstName: "Lina",
  lastName: "Andersson",
  age: 28
};

// 👉 Din uppgift: Plocka ut firstName och age med destructuring.
````

---

## 📋 2. Array-Destructuring

```js
const colors = ["röd", "grön", "blå", "gul"];

// 👉 Din uppgift: Plocka ut "grön" och "gul" i separata variabler med destructuring.
```

---

## 👤 3. Nested Destructuring

```js
const user = {
  name: "Jonas",
  contact: {
    email: "jonas@example.com",
    phone: "123456"
  }
};

// 👉 Din uppgift: Använd destructuring för att plocka ut name och email.
```

---

## ✅ 4. Formulärvalidering: Namn och Ålder

📄 Skapa ett HTML-formulär med två inputfält:

* 🧍 Namn (måste fyllas i)
* 🔢 Ålder (måste vara ett positivt heltal över 0)

🧠 **Din uppgift (i JavaScript):**

* Förhindra att formuläret skickas om något är ogiltigt
* Visa ett felmeddelande om:

  * Namn är tomt
  * Åldern inte är giltig

💡 *Tips:* Använd `trim()` och `Number.isInteger()` för extra noggrann validering.

---

## 🛒 5. Produktformulär med Destructuring & Validering

Anta att du har ett formulär där man lägger till en produkt med:

* `productName` (input)
* `productPrice` (input)

```js
// Anta att du hämtar inputelementen så här:
const nameInput = document.getElementById("productName");
const priceInput = document.getElementById("price");

Extra förklaring: du har värdena hårdkodade i din TS och låtsats att du hämtat dem från HTML, eller så kan du vara ambitiös och köra "den riktiga vägen".
// 👉 Uppgift:
```

* ✅ Använd destructuring för att hämta `.value` från båda inputfälten
* ✅ Validera att:

  * Namn inte är tomt
  * Priset är ett positivt nummer (> 0)

📦 Om båda fälten är giltiga, logga produkten i konsolen som ett objekt.

---

Lycka till och glöm inte att testa i webbläsaren! 🚀
