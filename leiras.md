1. A program egy képszerkesztő alkalmazás, amelyet Google Colab környezetben lehet futtatni.
2. A felhasználó különböző parancsokkal tud képeket módosítani, például átméretezni, kivágni, forgatni vagy fekete-fehérré alakítani.
3. A program támogatja a képek címkézését (labeling), amellyel minden képhez külön megadható egy kategória vagy név.
4. A címkék egy labels.txt nevű fájlba mentődnek, így később egyszerűen visszakereshetők.
5. Az augment parancs automatikusan mesterségesen bővíti az adatokat különböző módosításokkal.
6. Az augmentation során a program véletlenszerű forgatást, tükrözést és kontrasztváltoztatást hajt végre a képeken.
7. A módosított képek mindig külön mappákba kerülnek, például /resized, /rotated, /bw vagy /augmented.
8. A felhasználó egyszerű szöveges parancsokkal irányíthatja az összes funkciót a Colab terminálján keresztül.
9. A program a Python Pillow könyvtárát használja a képfeldolgozási műveletekhez.
10. A felhasználói felület egyszerű, mégis lehetőséget ad komplex műveletek gyors végrehajtására.
11. Összességében a program jól szemlélteti a képfeldolgozás és az adat-előkészítés (data augmentation) alapjait gépi tanulási projektekhez.
