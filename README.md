# Correlation_table-R
Korrelációs táblázat létrehozása R nyelvben. Színes, számos. Állítható betűstílus és méret. 
A saját, eredeti korrelációs táblázatomból indul ki, amit a disszertációba is raktam.
Ezt írom arra, hogy Betti is tudja alkalmazva a sajátjára.

**Forma**: 
- Én Times New Roman betűstílust, 12-es betűmérettel alkalmaztam, de ízlés kérdés, csak én ezt kaptam meg kritikaként.

**Lépések:**
1. Le és betöltöd a könyvtárakat. Valamint a nyelvi stílusokat is. 
2. Megadod neki a mappád helyét ahol dolgozni fogsz.
3. Beöltöd a fájlodat amivel dolgozol
4. Adat szűkítés. HA te egy teljesen letisztázott excellel dolgozol akkor ez nem kell.
5. Adattípusokat átalakítod amivel az R tud dolgozolni. (Fakotorokká a kezeléseknél és számokká a mért paramétereknél.) Utána ezt ellenőrzöd az "str(df)" funkcióval.
6. Oszlopok kiválasztása amikkel dolgozunk és átnevezés. #Első és utolsó oszlopod nevének a megadása. Ugyanaz mint a numerikus adatok megadásánál.
  # Új nevek megadása az oszlopoknak: Itt tudod megadni, hogy az oszlopoknak mi legyen majd a neve az ábrán. Ezt szabadon tudod változtatni, hogy kiférjen, vagy ha szeretnéd, hogy angol legyen. Rájössz, hogy más nevet szeretnél ide, mértékegységet, stb. ... Ez sajnos pepecs, könnyű hibázni. Minden oszlopodat begépelni. De az előző str() funkció utáni eredmény másolható. 
  !!! Figyelem. Ha itt hibázol / új neveket akarsz megadni, akkor újra be kell tölteni a fájlt. 
7. Lefuttatjuk a korrelációs vizsgálatot és megkreáljuk az ábrát. 
  Innen manuális ki tudjuk menteni az ábrát (előbb olvasd el a 8. pontot!): 
  - Jobb alsó szekció: Export gomb
  - Save as Image...
  - Beállítjuk a kívánt méretet. Update Preview-al csekkoljuk. (800 x 750-el szerintem okés a méret.)

8. DE a 7. ponttal a betűméretet (és stílust) nem állítottuk. ### EZ MÉG nem tetszik
   - Ehhez
   - 800 x 800


**Optimalizáció**:
- A könyvtárakat letöltését is benne hagyom a kódban, valamint a mindent betűstílust letöltök. Ezzel lassul kicsit a kód, de így elég egy kijelölés, és ENTER-t nyomni, hogy lefusson a kód.
- De továbbra is ajánlom szakaszonként lefuttatni. Kijelölöd és **Ctrl + Enter**
- A **front_import()** leütése után pl. kérdez valamit "[y/n]". Itt a console részben (bal alsó szekció) üsd be, hogy "y", és nyomj egy ENTER-t. Ezután elkezd letölteni, ami több perc is lehet. 
- (vamúgy valszeg nem kéne minden könyvtár, de még nem jutottam oda, hogy kiválogassam. Itt, még mindent benne hagytam amivel addig dolgoztam. ...) 
- Persze ha valahol megáll, mert frissíteni akar, akkor azt kiikszeled, vagy frissíted. A Szoftver frissítés nem kell "Remind me later", a librarykat frissítését leokézod.
- De egy library/package frissítése után újra el kell indítani a könyvtárak installálását, mert megáll.



**Lementés, ajánlott méret**: Miután lefutott a kód manuálisan kell lementeni és beállítani a kívánt méretet. 
- 500 x 500-as pixelmérettel mentettem le, de szerintem lehet nagyobbis cikk esetén. 
- Ebben az esetben a betűméretet is érdemes feljebb állítani, hogy ne legyenek kényelmetlenül kicsik a betűk.

