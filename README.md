# 📊 Relació de Freqüències i Percentatges - PCMAT

Aplicació web interactiva dissenyada dins del marc del **Programa PCMAT (Llenguatge Matemàtic)** per treballar l'associació entre expressions verbals de probabilitat i freqüència amb la seva representació numèrica en percentatge i fracció.

## ✨ Característiques Principals

* **Associació visual amb línies corbes (SVG):** L'alumnat pot unir cada expressió verbal de la columna **A** amb el seu valor corresponent de la columna **B** tant fent clic com arrossegant (*Drag & Drop*).
* **Avaluació instantània i retroacció:** En prémer **Avaluar**, l'aplicació valida totes les parelles, calcula la puntuació sobre 6 i indica visualment els encerts i les correspondències correctes en cas d'error.
* **Aleatorietat en reiniciar:** Cada vegada que es prem **Reiniciar**, l'ordre dels valors de la columna B es barreja automàticament per afavorir la pràctica repetida.
* **Disseny adaptatiu (*Responsive*):** Funciona de manera fluida en ordinadors d'aula, pissarres digitals interactives (PDI) i tauletes, recalculant dinàmicament les línies de connexió.
* **Sense dependències de servidor:** Implementat íntegrament en un únic fitxer HTML/CSS/JS, llest per obrir en local o allotjar directament a **GitHub Pages**.

## 📋 Contingut de l'Activitat (Parelles)

| Expressió Verbal (Columna A) | Valor / Percentatge (Columna B) |
| :--- | :--- |
| **Sempre / Segur** | `100%` |
| **Gairebé sempre** | `90%` |
| **A vegades / Equiprobable** | `50% (1/2)` |
| **Un de cada quatre** | `25% (1/4)` |
| **Gairebé mai** | `10%` |
| **Mai / Impossible** | `0%` |

## 🛠️ Tecnologies Utilitzades

* **HTML5:** Estructura semàntica de l'activitat.
* **Tailwind CSS:** Disseny net, accessible i adaptat a l'estètica del programa PCMAT.
* **JavaScript (Vanilla) & SVG:** Lògica d'emparellament, arrossegament, avaluació i càlcul dinàmic de corbes de Bézier.

## 🚀 Desplegament a GitHub Pages

1. Puja els fitxers `llenguatge_matematic.html` (o reanomena'l a `index.html`) i `README.md` al teu repositori de GitHub.
2. Accedeix a **Settings > Pages** dins del repositori.
3. Selecciona la branca `main` i fes clic a **Save** per obtenir l'enllaç públic per compartir amb l'alumnat.