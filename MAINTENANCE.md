# Showcase frissítése

Ez önálló dokumentációs repó. A main ág a bemutatható anyag; nem olvasztjuk az alkalmazás ágaiba. Nincs build, deployment vagy GitHub Actions workflow.

## Rögzített forrásállapot

- Bemutató és képek: 2026-11-03.
- Alkalmazás fejlesztési ága: codex/family-accounts-lists.
- Alkalmazás commit: 8fe2adcd799e940d99f72f55b66418023ad0bb05.
- Teszteredmény: a 2026-10-29-i teljes helyi pnpm verify dokumentált eredménye; a bemutató készítésekor nem futott új teljes regresszió.
- Későbbi használói visszajelzés: a vegyes elválasztók és az 1 kg paprika egy tételben megőrzése működött.

## Következő frissítés

1. Ellenőrizd az alkalmazás legfrissebb elfogadott fejlesztési állapotát; a Preview nem feltétlenül egyezik az éles változattal.
2. Frissítsd a README funkcióit, állapotát és az igazolt teszteredmény dátumát. Ne állítsd késznek a nyitott készülékes vagy minőségi próbákat.
3. A képeket helyi demo nézetből készítsd, kizárólag mintaadatokkal. Ne kerüljön ide valódi jegyzet, e-mail-cím, API-kulcs vagy belső üzemeltetési napló.
4. A jelenlegi négy kép: asztali jegyzetszerkesztő, vegyes elválasztós lista, mobil checklist, családi funkcióbeállítások. Megújításkor várd meg a tartalom betöltését és szemrevételezd a képeket.
5. Ellenőrizd a relatív képlinkeket és a GitHub README megjelenését, majd commit és push ebbe a repóba. Az alkalmazás repóját és a kikapcsolt Actions állapotát ne módosítsd.

A 2026-11-03-i felvételek helyi API-mockokkal készültek; élő Groq/DeepSeek-hívás és adatbázis-mentés nem történt. A listaképen kézzel beírt mintaátiratot a valódi kliensoldali parser dolgozta fel. A képek felületet és folyamatot mutatnak, nem új hangminőségi mérést.
