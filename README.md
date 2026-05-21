# 🎓 Quiz Cooperatiu – Crea el teu Kahoot de Classe

Eina web interactiva per dissenyar, compartir i fusionar qüestionaris educatius.  
Pensada per a l'aprenentatge cooperatiu: **cada alumne crea les seves preguntes, les exporta en JSON, i el professor les fusiona totes** per generar un únic Kahoot de repàs col·lectiu.

![Quiz Cooperatiu](https://img.shields.io/badge/estat-actiu-brightgreen) ![Llicència MIT](https://img.shields.io/badge/llicència-MIT-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) 

---

## 🚀 Característiques principals

- ✏️ **Disseny de preguntes** amb 4 opcions, resposta correcta i explicació teòrica.
- 📥 **Exportació i importació** de preguntes en format JSON (qualsevol extensió permesa).
- 🔀 **Fusionador intel·ligent** per combinar múltiples fitxers JSON en un sol banc.
- 🎮 **Joc de Kahoot** completament funcional en una sola pantalla.
- 🔀 **Barreja aleatòria** de preguntes i respostes (Fisher-Yates) per evitar còpies.
- 📱 **Disseny responsiu** adaptat a mòbil, tauleta i PC.
- 💾 **Emmagatzematge local** (localStorage) per conservar les preguntes entre sessions.
- 🧑‍🏫 **Modal d'instruccions** integrat per guiar alumnes i professors.

---

## 📸 Captures de pantalla

| Pantalla principal | Editor de preguntes | Joc en marxa |
|-------------------|---------------------|--------------|
| *(Menú amb botons: Jugar, Dissenyar, Fusionar, Exportar, Esborrar)* | *(Formulari amb camps de text, opcions i explicació)* | *(Quadrícula de 4 respostes de colors, feedback immediat)* |

| Fusionador de fitxers | Resultat final |
|-----------------------|----------------|
| *(Botó per triar fitxers, barra d'estat, descàrrega combinada)* | *(Encerts, percentatge, llista d'errors)* |

---

## 🧑‍🎓👨‍🏫 Com s'utilitza

### Per a l'alumne
1. Obre l'aplicació i ves a **Dissenyar Preguntes**.
2. Crea cada pregunta amb les 4 opcions, marca la correcta i escriu una explicació.
3. Torna al menú principal i prem **Exportar el meu banc**.
4. Envia el fitxer `.json` descarregat al professor.

### Per al professor
1. Recopila tots els fitxers `.json` dels alumnes.
2. Ves a la secció **Fusionador de Quizzes**.
3. Clica **Triar fitxers** i selecciona'ls tots alhora.
4. Prem **Descarregar Tot Fusionat** per obtenir el fitxer final.
5. Ara ja pots prémer **Jugar al Kahoot** amb totes les preguntes de la classe.

💡 *El mateix fitxer fusionat es pot tornar a pujar en un altre ordinador per continuar editant o jugant.*

---

## 🛠️ Tecnologies utilitzades

- **HTML5** – estructura semàntica i accessibilitat.
- **CSS3** – variables, flexbox, grid, animacions, disseny responsiu.
- **JavaScript (ES6)** – lògica del joc, gestió de localStorage, importació/exportació JSON, algorisme de Fisher-Yates.
- **Cap dependència externa** – tot el codi és autònom i s'execuga directament al navegador.

---

## 📂 Estructura del projecte
