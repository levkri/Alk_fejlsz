<h1>Dokumentáció</h1>
<h3>Készítette: Lévai Krisztián<h3>
--
<h1>Online szódolgozat</h1>
--
<h1>1. Követelményanalízis</h1>
<h2>1.1. Célkitűzés, projekt indító dokumentum</h2>
<p>
A program célja, hogy az álltalános iskolákban vagy középiskolákban a papír alapú szódolgozatot részben vagy egész részben kiváltsa. Így gyorsabb és kényelmesebb lenne az ellenőrzése. Nem lenne probléma a diákok "szépírása".
</p>
<strong>Funkcionális követelmények:</strong><br>
<p>Bejelentkezés
A regisztrációt a rendszergazda végezné
A bejelentkezés után a diák és a tanár a jogkörének megfelelő elemeket látná csak az oldalból
diák: szódolgozat kitöltése, pontszámok megtekintése
tanár: szavak megadása, dolgozat létrehozása, összesítések megtekintése
</p>
<p>
<strong>Nem funkcionális követelmények:</strong><br>
Könnyű áttekinthetőség: Csak a legszükségesebb menüpontok legyenek láthatóak, azok könnyen észrevehetőek
Használhatóság: Ésszerű elrendezés, könnyen kezelhetőség
Megbízhatóság:  Jelszóval védett funkciók, és a jelszavak védelme a háttérben
Karbantarthatóság: Könnyen lehessen bővíteni, a különböző típusú fájlok külön csoportosítva, ésszerűen legyenek felbontva, a könnyebb fejleszthetőség miatt
</p>

<h2>1.2. Használatieset-modell, funkcionális követelmények</h2>
Vendég: Csak a publikus oldalakat éri el
<ul>  
  <li>Főoldal</li>
  <li>Bejelentkezés<li>
</ul>

<strong>Diák:</strong>
<ul>  
  <li>Eredmények</li>
  <li>Dolgozat megírása</li>
</ul>

<strong>Tanár:</strong>
<ul>
  <li>Osztályok módosítása</li>
  <li>Dolgozat létrehozása</li>
</ul>

<img src="https://github.com/levkri/Alk_fejlsz/blob/master/use-case.gif">

<h1>2. Tervezés</h1>

<h2>2.1. Architektúra terv</h2>

<h2>2.1.1. Komponensdiagram</h2>

----------------------------------------------------------------

<h2>2.1.2. Oldaltérkép:</h2>

<strong>Publikus</strong>
<ul>
<li>Főoldal</li>
<li>Bejelentkezés</li>
</ul>

<strong>Diák</strong>
<ul>
    <li>Jelszó modosítás</li>
    <li>Eredmények</li>
    <li>Dolgozat írás</li>
</ul>

<strong>Tanár</strong>
<ul>
    <li>Jelszó modosítás</li>
    <li>Osztályok módosítása</li>
      <li>Osztály létrehozása</li>
      <li>Osztály törlése</li>
    <li>Osztály módosítása</li>
    <li>Dolgozat létrehozása</li>
</ul>

<strong>Admin</strong>
    Felhasznaló felvétele

<h2>2.2. Felhasználói-felület modell</h2>

<h2>2.2.1. Oldalvázlatok:</h2>

<strong>Főoldal</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Foldal.jpg">

<strong>Bejelentkezés</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/bejelentkezes.jpg">

<strong>Eredmények</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Eredmenyek.jpg">

<strong>Dolgozat írás</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Dolgozat_iras.jpg">

<strong>Osztályok módosítása</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Osztalyok_modositasa.jpg">

<strong>Dolgozat létrehozása</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Dolgozat_letrehozasa.jpg">

<strong>Jelszó modosítás</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Jelszo_modositas.jpg">

<strong>Felhasznaló felvétele</strong>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Felhasznalo_felvetele.jpg">

<h2>2.2.3. Osztálymodell</h2>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/database.png">

<h2>2.2.3. Adatbázisterv</h2>
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/database.png">


