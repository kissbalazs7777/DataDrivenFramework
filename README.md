[Link to Extent Report](https://kissbalazs7777.github.io/DataDrivenFramework)  
[Link to reportNG](https://kissbalazs7777.github.io/DataDrivenFramework/target/surefire-reports/html/index.html)  

Manuális teszt esetek: manual_test_cases.xlsx fájlban megtalálhatóak!  

Tesztek:  
-Regisztráció  
-Bejelentkezés  
-Adatkezelési nyilatkozat használata  
-Adatok listázása  
-Több oldalas lista bejárása  
-Új adat bevitel  
-Ismételt és sorozatos adatbevitel adatforrásból  
-Meglévő adat módosítása  
-Adat vagy adatok törlése  
-Adatok lementése felületről  
-Kijelentkezés  

Valamennyi teszt adatot egy excel táblázatból (testdata.xlsx) olvasok be. A webelemek lokátorait Locators.properties fájlból olvasom be. A teszt környezetet pedig a Config.properties fájlból olvasom be.
Github workflow is be van állítva, a teszteket lefuttatja automatikusan abban az esetben, ha valami változás történik a repositoryval. Ilynekor a jelentést automatikusan frissíti (link a jelentéshez: lásd első sor).
