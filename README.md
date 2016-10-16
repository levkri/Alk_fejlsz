Dokumentáció
--
Online szódolgozat
--
1. Követelményanalízis
1.1. Célkitűzés, projekt indító dokumentum

A program célja, hogy az álltalános iskolákban vagy középiskolákban a papír alapú szódolgozatot részben vagy egész részben kiváltsa. Így gyorsabb és kényelmesebb lenne az ellenőrzése. Nem lenne probléma a diákok "szépírása".

Funkcionális követelmények:
Bejelentkezés
A regisztrációt a rendszergazda végezné
A bejelentkezés után a diák és a tanár a jogkörének megfelelő elemeket látná csak az oldalból
diák: szódolgozat kitöltése, pontszámok megtekintése
tanár: szavak megadása, dolgozat létrehozása, összesítések megtekintése

Nem funkcionális követelmények:
Könnyű áttekinthetőség: Csak a legszükségesebb menüpontok legyenek láthatóak, azok könnyen észrevehetőek
Használhatóság: Ésszerű elrendezés, könnyen kezelhetőség
Megbízhatóság:  Jelszóval védett funkciók, és a jelszavak védelme a háttérben
Karbantarthatóság: Könnyen lehessen bővíteni, a különböző típusú fájlok külön csoportosítva, ésszerűen legyenek felbontva, a könnyebb fejleszthetőség miatt

1.2. Használatieset-modell, funkcionális követelmények
Vendég: Csak a publikus oldalakat éri el
Főoldal
Bejelentkezés

Diák:
Eredmények
Dolgozat megírása

Tanár:
Osztályok módosítása
Dolgozat létrehozása

<img src="https://github.com/levkri/Alk_fejlsz/blob/master/use-case.gif">

2. Tervezés

2.1. Architektúra terv

2.1.1. Komponensdiagram

----------------------------------------------------------------

2.1.2. Oldaltérkép:

Publikus:
Főoldal
Bejelentkezés

Diák:
Jelszó modosítás
Eredmények
Dolgozat írás

Tanár
Jelszó modosítás
Osztályok módosítása
  Osztály létrehozása
  Osztály törlése
  Osztály módosítása
Dolgozat létrehozása

Admin
Felhasznaló felvétele

2.2. Felhasználói-felület modell

2.2.1. Oldalvázlatok:

Főoldal
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Foldal.jpg">

Bejelentkezés
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/bejelentkezes.jpg">

Eredmények
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Eredmenyek.jpg">

Dolgozat írás
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Dolgozat_iras.jpg">

Osztályok módosítása
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Osztalyok_modositasa.jpg">

Dolgozat létrehozása
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Dolgozat_letrehozasa.jpg">

Jelszó modosítás
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Jelszo_modositas.jpg">

Felhasznaló felvétele
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/Felhasznalo_felvetele.jpg">

2.2.3. Osztálymodell
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/database.png">

2.2.3. Adatbázisterv
<img src="https://github.com/levkri/Alk_fejlsz/blob/master/database.png">


