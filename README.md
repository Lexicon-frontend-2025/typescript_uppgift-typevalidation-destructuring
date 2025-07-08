# 🧪 Övning: Praktisk Tillämpning

## ✅ Uppgifter:

1. **📦 Fortsätt med Produktkatalogen**  
   Se till att din produktkatalog har **full validering**:
   - 📝 Namn får **inte vara tomt**
   - 💰 Pris måste vara ett **nummer större än 0**

2. **🔧 Använd Destructuring i `addProduct`**  
   Använd **destructuring** när du hanterar input från formuläret, t.ex. när du skapar det nya `Product`-objektet.

3. **🔁 Använd Destructuring i `renderProducts`**  
   När du loopar igenom `products`-arrayen, använd destructuring för att plocka ut:
   - `name` 🏷️
   - `price` 💵
   - `isInStock` ✅  
   direkt i `forEach`-loopen.

4. **👤 Enkel Användarprofil**  
   Skapa ett objekt:
   ```js
   const userProfile = {
     username: "devCoder",
     email: "dev@example.com",
     settings: {
       theme: "dark",
       notifications: true
     }
   };
````

Använd **destructuring** för att plocka ut `username` 🧑‍💻 och `theme` 🎨 i separata variabler.
➕ **Skriv ut dem i konsolen.**

5. **📅 Array Destructuring**
   Skapa en array:

   ```js
   const weekdays = ["Måndag", "Tisdag", "Onsdag", "Torsdag", "Fredag"];
   ```

   Använd **array destructuring** för att plocka ut:

   * `Tisdag` 📆
   * `Torsdag` 📆
     i separata variabler.
