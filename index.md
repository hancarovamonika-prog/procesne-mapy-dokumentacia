---
title: "Procesné mapy: čo appka zatiaľ vie"
---

# Procesné mapy: čo appka zatiaľ vie

Stav k 18. 10. 2026 o 21:01.

Procesné mapy je webová aplikácia, ktorá z popisu procesu urobí procesnú mapu. Dnes vie z vloženého textu nakresliť prehľadovú mapu s krokmi rozdelenými podľa rolí a ktorýkoľvek krok rozpísať na detailnú mapu. Je zadarmo, s limitom 15 analýz mesačne na účet.

Prihlasuje sa odkazom v e-maile, bez hesla. Každý vidí len svoje mapy.

## Prihlásenie a môj účet

Prihlási sa ktokoľvek s akoukoľvek e-mailovou adresou, bez pozvánky a bez hesla.

- Na úvodnej stránke zadáš e-mail a príde ti prihlasovací odkaz. Po jeho otvorení klikneš ešte na „Prihlásiť sa“, aby ho nespotrebovala automatická kontrola e-mailu. Nový odkaz si môžeš vypýtať najskôr o minútu.
- Keď je odkaz použitý alebo vypršal, aplikácia povie „Odkaz už neplatí“ a ponúkne poslanie nového.
- Na tom istom zariadení ostaneš prihlásený až 30 dní.
- Na stránke „Môj účet“ vidíš svoj e-mail, môžeš sa odhlásiť alebo si účet natrvalo zrušiť. Zrušenie zmaže všetky tvoje mapy a dáta.

Vedľa prihlásenia je ukážková mapa „Káva došla“: s nadhľadom ukazuje, ako procesná mapa vyzerá, ešte kým sa človek prihlási.

![Úvodná stránka s prihlásením odkazom v e-maile a vtipnou ukážkovou mapou „Káva došla“](obrazky/uvod.png)

Zatiaľ chýba potvrdzujúci e-mail po zrušení účtu.

## Moje mapy a vloženie textu

Nová mapa vzniká z textu, ktorý vložíš alebo napíšeš. Môže to byť aj skopírovaný zápis či prepis zo stretnutia.

- Text má 30 až 30 000 znakov, počítadlo pod poľom ukazuje, koľko sa ešte zmestí. Pole sa prispôsobí oknu a potiahnutím za roh sa dá zväčšiť.
- Názov je nepovinný, najviac 30 znakov. Bez názvu mapu pomenuje AI pri analýze.
- Zoznam „Moje mapy“ ukazuje názov, dátum, čas a stav každej mapy, najnovšie hore. Kým nemáš žiadnu mapu, stránka ukáže znudené oranžové rozhodnutie a tlačidlo „Dať mu prácu“, ktoré vedie na novú mapu.
- Text aj názov sa dajú kedykoľvek upraviť.
- Mapu môžeš natrvalo zmazať aj s textom, po potvrdení.
- Jeden účet môže mať najviac 200 máp.

![Moje mapy: jedna analyzovaná a jedna čakajúca na analýzu](obrazky/moje-mapy.png)

![Nová mapa: pole na popis procesu a rady, čo má text povedať](obrazky/nova-mapa.png)

## Analýza AI a prehľadová mapa

Tlačidlo „Analyzovať“ pošle text AI a za pol minúty až minútu je na stránke prehľadová mapa. Pred prvou analýzou potvrdíš, že rozumieš, že text odchádza poskytovateľovi AI (Anthropic).

Mapa ukazuje:

- pásy podľa rolí, teda kto ktorý krok robí (krok bez zistiteľnej roly je v páse „Neurčené“),
- 3 až 11 hlavných krokov, začiatok, koniec a šípky medzi nimi,
- rozhodnutia ako kosoštvorec s otázkou a pomenovanými vetvami,
- návraty späť (napríklad na opravu) a kroky, ktoré bežia súčasne.

![Prehľadová mapa nákupu tovaru s rozhodnutiami, návratom, súbežnou prácou skladu a účtovníčky a jedným rozpísaným krokom](obrazky/mapa.png)

Po kliknutí na krok vidíš jeho popis a vetu z tvojho textu, z ktorej ho AI vyvodila. Mapa je v jazyku textu. Na počítači ju posunieš ťahaním myšou, na mobile ju posúvaš a zväčšuješ prstami.

![Detail kroku: popis a veta z textu, z ktorej ho AI vyvodila, nad mapou tlačidlo „Upraviť mapu“](obrazky/detail-kroku.png)

Analýza beží aj po zatvorení okna. Keď v texte nie je proces, aplikácia nič nenakreslí a poradí, čo doplniť. Pri výpadku sa pokus do limitu nezapočíta.

## Verzie mapy a limity

Každá úspešná analýza je nová verzia mapy aj s textom, z ktorého vznikla. Po úprave textu aplikácia ukáže, že mapa už nesedí, a ponúkne „Analyzovať znova“.

- Staršiu verziu si môžeš pozrieť, vrátiť sa k nej (vráti sa aj jej text) alebo ju natrvalo zmazať.
- Mapa má najviac 10 verzií. Pred jedenástou aplikácia povie, ktorú najstaršiu zmaže.

| Čo | Limit |
| --- | --- |
| Analýzy na účet | 15 mesačne, obnoví sa 1. dňa v mesiaci |
| Mapy na účet | 200 |
| Verzie na mapu | 10 |
| Dĺžka textu | 30 až 30 000 znakov |
| Rozpísania krokov na účet | 30 mesačne, obnoví sa 1. dňa v mesiaci |

Návrat k verzii limit neminie. Pri analýze vidíš, koľko analýz ti tento mesiac ostáva.

## Detailná mapa kroku

Ktorýkoľvek krok prehľadovej mapy sa dá rozpísať na detailnú mapu: čo presne sa v ňom deje, kto to robí a v akom poradí.

- Po kliknutí na krok tlačidlo „Rozpísať krok“ pošle AI text a krok. Zhruba za pol minúty má krok vlastnú stránku s detailnou mapou, aj keď okno medzitým zavrieš.
- Detailná mapa má 2 až 8 menších krokov a kreslí sa rovnako ako prehľadová: pásy podľa rolí, rozhodnutia, súbežné cesty a návraty. Pri každom menšom kroku je veta z textu.
- Keď text o kroku viac nehovorí, AI si nič nevymyslí a aplikácia poradí, čo doplniť.
- Rozpísaný krok je v prehľadovej mape označený a „Zobraziť detail“ ho otvorí.
- „Rozpísať znova“ po potvrdení nahradí detail novým, starý sa neuchová.
- Rozpísania majú vlastný limit 30 mesačne na účet, oddelený od analýz. Pri tlačidle vidíš, koľko ti ostáva.

![Detailná mapa kroku „Skontroluje dodávku“ s rozhodnutím a reklamáciou u nákupcu](obrazky/detailna-mapa.png)

![Rozpísať znova: otázka „Nový detail nahradí súčasný. Pokračovať?“](obrazky/rozpisat-znova.png)

Detaily patria k verzii mapy. Nová analýza začína bez rozpísaných krokov a návrat k staršej verzii vráti aj jej detaily. Pri staršej verzii sa detaily dajú otvoriť, no nové sa nerozpisujú. Zmazanie verzie, mapy aj účtu zmaže aj detaily.

![Staršia verzia mapy: rozpísaný krok sa dá otvoriť cez „Zobraziť detail“](obrazky/starsia-verzia.png)

## Ručná úprava mapy

Keď AI niečo pochopí zle, mapu opravíš sám a nemusíš míňať analýzu. Tlačidlo „Upraviť mapu“ je pri platnej verzii mapy, upravuje sa na počítači.

- Prepíšeš názov a popis kroku, otázku rozhodnutia aj názvy vetiev.
- Pridáš krok, ktorý AI vynechala, alebo zmažeš krok navyše. Mapa môže mať najviac 25 krokov.
- Šípky kreslíš, mažeš a pomenúvaš, aj tie, ktoré vedú späť.
- Krok potiahneš do iného pásu, a tým mu zmeníš rolu. Pás premenuješ, posunieš hore alebo dole, alebo pridáš nový.
- Počas úpravy máš „Späť“ a „Znova“, zmeny „Uložíš“ alebo „Zrušíš“.

Prvé uloženie založí verziu „Upravená ručne“ a návrh od AI ostane ako staršia verzia. Zmenený krok má značku „Upravené ručne“, pridaný krok má namiesto vety z textu „Pridané ručne“ a dá sa rozpísať. Detaily krokov sa do novej verzie prenesú.

![Úprava mapy: vybraný krok s názvom, popisom a pásom, tlačidlá na pridanie krokov a „Späť“, „Znova“, „Zrušiť“, „Uložiť“](obrazky/uprava-mapy.png)

## Čo zatiaľ nevie a čo príde ďalej

Dnes appka berie len vložený text. V tomto poradí prídu:

1. Dokončenie ručnej úpravy: rozhodnutia a súbežné cesty, voľné rozmiestnenie krokov a zachovanie opráv pri novej analýze.
2. Posielanie mapy odkazom niekomu inému.
3. Nahratie dokumentu (Word, PDF…) ako vstupu.
4. Nahratie záznamu alebo prepisu stretnutia.
5. Spojenie viacerých vstupov do jednej mapy.
6. Export mapy ako obrázok alebo PDF.

Neskoršie, mimo tohto zoznamu: platby, prihlásenie cez Microsoft či Google a spoločné priestory pre kolegov z jednej firmy.
