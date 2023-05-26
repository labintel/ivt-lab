## 1. teszt
SINGLE lövést szeretnénk leadni. A primary tár üres, viszont a secondary tár nem az. Így az elvárt működés az lenne, hogy a secondary fog tüzelni, elvárt visszatérési érték true.
## 2. teszt
SINGLE lövést szeretnénk leadni. Mindkét tár üres, ezért az elvárt visszatérési érték false.
## 3. teszt
ALL lövést szeretnénk leadni. A primary tár tele, viszont a secondary üres. Így az elvárt működés az lenne, hogy tüzel az primary, viszont false a visszatérési érték.
## 4. teszt
ALL lövést szeretnénk leadni. A secondary tár tele, viszont a primary üres. Így az elvárt működés az lenne, hogy tüzel az secondary, viszont false a visszatérési érték.
## 5. teszt
Két SINGLE lövést szeretnénk leadni, mindkét tár tele van. Az elvárt visszatérési érték true.