# Iskolacsengő Program

Ez a program két fő alkalmazás felülettek rendelkezik, Manuális vezérlés és Táblázatok nevű palettával.

## Manuális vezérlés:
   - `Módosítás` gomb:
     A módosítás gomb segítségével változtathatjuk meg az előre beírt adatokat.
   - `Leállítás` gomb:
     A gomb használatával leállítható az teljes program.
   - `Rövidített óra` gomb:
     A vezérlő e gomb megnyomásával azonnal rövidített üzemmódra állíthatja a csengőket, a bekapcsolt állapotát lámpa jelzi. (Éjfélkor automatikusan kikapcsol)
   - `Tűzriadó` gomb:
     A gomb bekapcsolásától a gomb kikapcsolásáíg tűzjelző hangot ad ki, a bekapcsolt állapotát lámpa jelzi.
   - `Bombariadó` gomb:
     A gomb bekapcsolásától a gomb kikapcsolásáig bombariadót fúj, a bekapcsolt állapotát lámpa jelzi.
   - Ezen a felületen még egy `Speciális tanítás` lámpa van, mely akkor világít, ha nem normál tanítás zajlik.

## Táblázatok:

Ezen részen láthatóak a Csengetési rendek (rövidített óra esetén automatikusan átvált) melyek segítségével könnyen el lehet igazodni a csengetések között
Valamint egy "Szünetek" nevű táblázat, ami az előre bejegyzett szüneteket tartalmazza(ezáltal a szünidőben nem lesznek felesleges csengetések)
amelyek természetesen a "Módosítások" gomb segítségével könnyen és gyorsan javíthatóak.

## Visszajelző felület

Az alkalmazás átláthatóságának könnyítése érdekében a felület jobb oldalán 5 led helyezkedik el.
Ezek leolvasásával nyomon követhetjük, hogy az adott napon milyen rendkívüli események, folyamatok befolyásolják a programot:

1. Tanitási nap: A mai napon tanítás zajlik.
2. Munkaszüneti nap/ Szünet: A mai napon nincs tanítás, a csengők nem üzemelnek.
3. Csengő: Jelen pillanatban működik-e a csengő(ha világít, de nem szól a csengő, valószínüleg nem a programban van a hiba).
4. Jelzőcsengő: Jelen pillanatban működik-e a jelzőcsengő(ha világít, de nem szól a csengő, valószínüleg nem a programban van a hiba).
5. Kevesebb tanóra: Megmutatja, hogy az adott nap kevesebb óra lesz-e megtartva az előírtnál(alatta kiírja, hogy az adott nap maximum hány tanóra lesz)

## **_FIGYELEM!!!_**
A `fájlok` mappában található adatokat a program megfelelő működése érdekében semmiképp se nevezze át vagy törölje.

## Köszönet

Köszönet Kajtár Gergőnek és Kajtár Bencének, volt Huszár Gál Gimnáziumos Tanulóknak a segítségért a Design, a Programdokumentáció, és a Tesztelés területén és Vizi Tibor tanárúrnak az egész éves munkáért.
