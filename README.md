# Repte-0
Hola sóc Àngel i aquest és el meu repte 0
Hola son las 11:38 del 2/10/2025


<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Prova de JavaScript</title>
</head>
<body>
  <h1>Prova de codi JavaScript</h1>
  <p id="missatge">Fes clic al botó per executar el codi.</p>


  <button id="boto">Executa JS</button>


  <!-- Enllaç al fitxer extern -->
  <script src="script.js"></script>
</body>
</html>


// 🔤 Tipus de dades en JavaScript

// 1️⃣ Cadenes de text (string)
let nom = "Anna";
console.log("Nom:", nom); // Mostra: Anna

// 2️⃣ Nombres (number)
let edat = 25;        // enter
let preu = 12.99;     // real (coma flotant)
console.log("Edat:", edat); // Mostra: 25
console.log("Preu:", preu); // Mostra: 12.99

// 3️⃣ Nombres grans (BigInt)
let gran = 123456789012345678901234567890n;
console.log("Nombre molt gran:", gran);

// 4️⃣ Booleans (boolean)
let esMajorEdat = true;
let teCarnet = false;
console.log("És major d’edat?", esMajorEdat);
console.log("Té carnet?", teCarnet);

// 5️⃣ Arrays (llistes)
let colors = ["vermell", "verd", "blau"];
console.log("Colors:", colors);
console.log("Primer color:", colors[0]); // Accés a un element

// 6️⃣ Objectes (diccionaris)
let persona = {
  nom: "Joan",
  edat: 30,
  ciutat: "Barcelona"
};
console.log("Persona:", persona);
console.log("Nom de la persona:", persona.nom); // Accés a una propietat

// 🔎 Exemple final combinat
console.log(`Hola! Em dic ${persona.nom}, tinc ${persona.edat} anys i m’agraden els colors ${colors.join(", ")}.`);



// 🧮 Nombres enters (int) en JavaScript
// Els nombres enters serveixen per fer operacions bàsiques com sumes, restes, multiplicacions o divisions.

// Exemples de nombres enters: 1, 3, -15, 250...
let exemple1 = 1;
let exemple2 = 3;
let exemple3 = -15;
let exemple4 = 250;

console.log("Exemples de nombres enters:", exemple1, exemple2, exemple3, exemple4);

// 🧩 Exemple 1: Suma de dos nombres enters
let a = 1234;
let b = 23;
console.log("Suma:", a + b); // Resultat: 1257

// ⚠️ Atenció: Encara que les variables siguin enters, 
// en fer una divisió el resultat pot tenir decimals.

// 🧩 Exemple 2: Divisió amb resultat decimal
let x = 25;
let y = 2;
console.log("Divisió:", x / y);          // Resultat: 12.5
console.log("Tipus de dada:", typeof (x / y)); // Resultat: 'number'

// 💡 En JavaScript no hi ha distinció entre enters (int) i decimals (float):
// tots dos són del mateix tipus → number.
console.log("typeof 25:", typeof 25);   // 'number'
console.log("typeof 12.5:", typeof 12.5); // 'number'



// 🌊 MD4.2 Nombres reals o de coma flotant (number)
// Els nombres reals representen valors amb part decimal (coma flotant).

// Exemples de nombres reals (float)
let num1 = 1.2;
let num2 = 3.5;
let num3 = 6.24;
let num4 = -10.345;
let num5 = 1245.23;

console.log("Exemples de nombres reals:", num1, num2, num3, num4, num5);

// 🧩 Exemple
let a = 3.2;
let b = 7;
console.log("Resultat de la multiplicació:", a * b); 
// Resultat esperat: 22.4
// Resultat real: 22.400000000000002 (petita errada d’arrodoniment)

// ❗ ATENCIÓ!
// En les operacions amb decimals, és freqüent trobar petites errades d’arrodoniment.
// Això passa perquè alguns decimals no es poden representar exactament en binari.

// 💡 Solució: limitar els decimals visibles amb .toFixed()
let resultat = a * b;
console.log("Resultat amb dos decimals:", resultat.toFixed(2)); 
// Mostra: 22.40

// 📘 Informació addicional:
// typeof 3.2 i typeof 7 són tots dos 'number'
console.log("Tipus de 'a':", typeof a); // 'number'
console.log("Tipus de 'b':", typeof b); // 'number'
console.log("Tipus del resultat:", typeof resultat); // 'number'





