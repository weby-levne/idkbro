# & — Music & Video Player

První funkční prototyp webového přehrávače pro PC i mobil.

## Spuštění
1. Rozbal ZIP.
2. Otevři `index.html` v moderním prohlížeči.
3. Pro online vyhledávání doporučujeme spustit projekt přes lokální webový server nebo ho publikovat na GitHub Pages.

## Funkce
- Lokální audio a video soubory z telefonu/počítače.
- Ovládání přehrávání, hlasitosti a pozice.
- Online vyhledávání hudebních ukázek přes iTunes Search API.
- Vyhledávání videí na Internet Archive a pokus o načtení přehratelného souboru.
- Oblíbené, historie, playlisty a světlý/tmavý režim.
- Responzivní rozhraní pro mobil a desktop.

## Důležitá omezení prototypu
- iTunes poskytuje pouze krátké náhledy skladeb, nikoli plné skladby.
- Dostupnost videí na Internet Archive se liší podle konkrétního záznamu a formátu.
- Lokální soubory se přehrávají přímo ze zařízení. Prohlížečové object URL nejsou trvalé, takže je po obnovení stránky potřeba vybrat znovu.
- Playlisty, oblíbené položky a historie se ukládají v localStorage daného prohlížeče.
- Aplikace neobchází placené služby, DRM ani omezení platforem.

## Soubory
- `index.html` — struktura aplikace
- `style.css` — vzhled a responzivní rozložení
- `app.js` — přehrávač, knihovna, playlisty a vyhledávání

## Licence a zdroje
Rozhraní prototypu je vlastní. Online obsah poskytují uvedené služby podle jejich vlastních podmínek. Před veřejným komerčním nasazením zkontroluj podmínky API a pravidla použití obsahu.
