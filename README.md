# 🎵 Alexia Music Player

Hudobný prehrávač pre **Android, iPhone a Linux** s podporou offline počúvania, slovenských a českých rádií.

**Aktuálna verzia: 1.24**

[⬇️ Stiahnuť najnovšiu verziu](https://github.com/havetkin-cyber/alexia-release/releases/latest)

---

## 🆕 Novinky vo verzii 1.24

### Alexia Music aj pre iPhone a Linux
- ✅ **Rovnaká appka ako na Androide** – tie isté obrazovky, farby, písmo aj ikony, rovnaké funkcie: hľadanie, knižnica, rádiá, playlisty, video, ekvalizér a 8D zvuk
- ✅ Všetky tri verzie sa vydávajú naraz a majú rovnaké číslo verzie

### 🐧 Linux (AppImage) – Ubuntu, Fedora, SteamOS / Steam Deck…
1. Stiahni `AlexiaMusic-v…-x86_64.AppImage` z [najnovšieho vydania](https://github.com/havetkin-cyber/alexia-release/releases/latest)
2. Pravým klikom → Vlastnosti → povoľ **Spustiteľný** (alebo `chmod +x AlexiaMusic-*.AppImage`)
3. Dvojklik – appka sa sama pridá do ponuky aplikácií (Steam Deck: v Desktop Mode → *Add to Steam*)
- ✅ Aktualizuje sa **úplne sama** – klepneš na Aktualizovať, stiahne sa, nahradí a reštartuje
- ℹ️ Pri prvom spustení treba internet (stiahne si yt-dlp, ktorý sa potom aktualizuje sám)

### 📱 iPhone / iPad (iOS 16 a novší)
1. Stiahni `AlexiaMusic-iOS-v….ipa` z [najnovšieho vydania](https://github.com/havetkin-cyber/alexia-release/releases/latest)
2. Nainštaluj ho cez **AltStore**, **SideStore** alebo **Sideloadly** (s bezplatným Apple ID)
- ✅ Aktualizácie: v AltStore / SideStore pridaj zdroj `https://github.com/havetkin-cyber/alexia-release/releases/latest/download/altstore.json` – nové verzie ponúkne sám; appka ich ponúkne aj sama
- ℹ️ S bezplatným Apple ID treba podpis obnoviť raz za 7 dní (AltStore / SideStore to robí automaticky)
- ℹ️ Na iPhone nie je widget na plochu ani CarPlay (Apple to bez platenej licencie nedovolí); ovládanie zo zamknutej obrazovky funguje

---

## 🆕 Novinky vo verzii 1.23

### Widget na plochu
- ✅ Názov práve hranej skladby a tlačidlá **predchádzajúca / hraj–pauza / ďalšia**
- ✅ Pridáš ho dlhým podržaním na ploche → Widgety → Alexia Music

### Android Auto
- ✅ Alexia Music sa ukáže v aute medzi hudobnými aplikáciami
- ✅ V aute prechádzaš **Knižnicu, Playlisty a Rádiá** a ovládaš prehrávanie z auta
- ✅ Knižnicu môže prechádzať len Android Auto, systém a aplikácia sama – iné aplikácie nie

### Aktualizácia priamo v aplikácii
- ✅ Klepneš na Aktualizovať – nová verzia sa **stiahne a nainštaluje sama**, bez hľadania v Stiahnutých
- ✅ Prvýkrát treba povoliť „Inštalovať neznáme aplikácie“ pre Alexia Music, od Androidu 12 ďalšie aktualizácie bez potvrdzovania
- ℹ️ Oprávnenie inštalovať sa používa **len na vlastné aktualizácie** z tohto vydania

---

## 🆕 Novinky vo verzii 1.19

### Video
- ✅ Pri skladbe si vyberieš, či chceš počúvať **skladbu** alebo pozerať **video**
- ✅ **Okamžité prepnutie** medzi skladbou a videom – zvuk hrá ďalej bez prerušenia, obraz sa pripraví vopred
- ✅ Video na **celú obrazovku**

### Nová domovská stránka
- ✅ **Top 5 skladieb** – tvoje najčastejšie počúvané skladby aj s počtom prehratí
- ✅ **Vyhľadávanie** priamo z domovskej stránky
- ✅ **Posledné 3 vyhľadávania** – ťuknutím ich zopakuješ, dajú sa vymazať
- ✅ Sekcia *Tvoje obľúbené* bola z Domova odstránená, aby bola stránka prehľadnejšia

### Aktualizácie vo všetkých jazykoch
- ✅ Popis novej verzie sa zobrazí v jazyku aplikácie – slovensky, anglicky, nemecky alebo maďarsky

### Bezpečnosť
- ✅ Aplikácia už nemá oprávnenie inštalovať iné aplikácie – aktualizáciu stiahne prehliadač a nainštaluješ ju ty (Google Play Protect ju už neoznačuje)
- ✅ Nešifrované spojenie je povolené len pre niekoľko rádií, ktoré iné nemajú
- ✅ Aplikácia nemá prístup k tvojim súborom, fotkám ani kontaktom – pracuje len so svojimi súbormi

---

## 🆕 Novinky vo verzii 1.10

### Nový názov aplikácie
- ✅ Na ploche telefónu sa už nevolá `alexiacore`, ale **Alexia Music Player**

### České rádiá
- ✅ Pribudlo **32 českých staníc** – Český rozhlas, Impuls, Evropa 2, Frekvence 1, Blaník, Kiss, Beat, Rock Radio, Country, Fajn, Radio 1, Expres FM, Spin, Čas, City, Signál, Krokodýl, Orion, HEY, Relax, Bonton, Classic Praha, COLOR Music a ďalšie
- ✅ Každý stream bol pred vložením naozaj otestovaný – overilo sa, či z neho tečie zvuk

### Rádiá rozdelené podľa krajín
- ✅ Dve rozkladacie sekcie: **Slovenské rádiá** a **České rádiá**
- ✅ Ťuknutím na nadpis sa sekcia otvorí alebo zbalí
- ✅ Pri každej sekcii je vidieť počet staníc
- ✅ Vyhľadávanie prehľadáva obe krajiny naraz a sekcie sa pritom otvoria samy

---

## Čo aplikácia vie

### Prehrávanie
- ✅ Prehrávanie hudby priamo v telefóne
- ✅ Widget na plochu a Android Auto
- ✅ Prehrávanie videa s okamžitým prepnutím na skladbu a späť, aj na celú obrazovku
- ✅ Hranie na pozadí aj pri zhasnutom displeji
- ✅ Ovládanie z notifikácie a zo zamknutej obrazovky
- ✅ Automatický prechod na ďalšiu skladbu
- ✅ Tlačidlá predchádzajúca / nasledujúca
- ✅ Slovenské a české rádiá – živé vysielanie
- ✅ Prehrávanie sa nepreruší, keď telefón zaspí

### Zvuk
- ✅ Ekvalizér s hotovými predvoľbami (Normálny, Klasika, Dance, Rock a ďalšie)
- ✅ Vlastné nastavenie každého frekvenčného pásma
- ✅ Zosilnené basy
- ✅ Priestorový zvuk 8D – zvuk sa plynule otáča z pravej strany cez stred do ľavej
- ✅ Nastaviteľná rýchlosť otáčania a sila efektu
- ✅ Efekty bežia na zvukovom čipe telefónu, takže nezaťažujú batériu

### Sťahovanie a offline režim
- ✅ Sťahovanie skladieb do telefónu
- ✅ Stiahnutá skladba sa prehráva vždy z mobilu – nulové dáta
- ✅ Žiadne sekanie pri strate signálu alebo prepnutí WiFi / dáta
- ✅ Jedna skladba = jeden záznam v knižnici
- ✅ Prehrávač si stiahnutý súbor nájde sám aj na pozadí

### Knižnica a playlisty
- ✅ Ukladanie skladieb do vlastnej knižnice
- ✅ Vyhľadávanie priamo v knižnici
- ✅ Vlastné playlisty s prehrávaním celého zoznamu
- ✅ Zelená značka pri stiahnutých skladbách
- ✅ Zmazanie iba stiahnutého súboru – skladba zostane v knižnici
- ✅ Mazanie skladby vrátane súboru v telefóne
- ✅ Domov: top 5 skladieb, vyhľadávanie a posledné 3 vyhľadávania

### Vzhľad a jazyky
- ✅ Tmavá téma v štýle hudobného prehrávača
- ✅ Úvodná animácia – pulzujúce logo, svetelné kruhy, ekvalizér
- ✅ Plynulý prechod z úvodnej obrazovky do aplikácie
- ✅ Spodné menu: Domov, Hľadať, Knižnica, Rádiá, Playlisty
- ✅ Mini prehrávač v spodnej časti obrazovky
- ✅ Celoobrazovkový prehrávač
- ✅ Štyri jazyky na prepnutie priamo v aplikácii

### Aktualizácie
- ✅ Aplikácia sama zistí novú verziu
- ✅ Ponuka aktualizácie s popisom zmien (v jazyku aplikácie) a veľkosťou
- ✅ Nová verzia sa stiahne cez prehliadač – aplikácia nepotrebuje oprávnenie inštalovať aplikácie
- ✅ Okno sa zobrazí len ak je dostupná novšia verzia
- ✅ Tlačidlo Preskočiť – verzia sa už viac neponúka
- ✅ Nová verzia sa zostaví sama každé ráno, ak je čo vydávať

### Rýchlosť a veľkosť
- ✅ Zmenšenie zo 66 MB na 49 MB
- ✅ Odstránený nepoužívaný kód a zdroje
- ✅ Jedno univerzálne APK pre všetky moderné telefóny

---

## Opravené chyby

- ✅ Pád aplikácie po spustení
- ✅ Dve položky jednej skladby po stiahnutí
- ✅ Sekanie pri prepnutí medzi WiFi a mobilnými dátami
- ✅ Aplikácia hlásila starú verziu napriek novému vydaniu
- ✅ Nefunkčné streamy pri niektorých rádiách
- ✅ Prepínač jazyka nereagoval na výber

---

## Pripravujeme

- ⬜ Hromadné sťahovanie viacerých skladieb naraz
- ⬜ Podpora starších telefónov

---

## Vydané verzie

| Verzia | Čo priniesla | Stav |
|--------|--------------|------|
| 1.3 | Prvé vydanie | vydané |
| 1.4 | Úvodná animácia, oprava pádu pri štarte | vydané |
| 1.5 | Tlačidlo Preskočiť pri aktualizácii | vydané |
| 1.6 | Spoľahlivá kontrola dostupnosti novej verzie | vydané |
| 1.8 | Ekvalizér, priestorový zvuk 8D, vyhľadávanie v knižnici | vydané |
| 1.10 | Nový názov, 32 českých rádií, delenie podľa krajín | vydané |
| 1.12 – 1.18 | Aktualizácia systému | vydané |
| **1.19** | Video, nová domovská stránka, aktualizácie vo všetkých jazykoch, bezpečnosť | **aktuálna** |

---

## Inštalácia

1. Stiahni si súbor `.apk` zo sekcie [Releases](https://github.com/havetkin-cyber/alexia-release/releases/latest)
2. V telefóne ho otvor cez **Súbory**
3. Ak sa objaví upozornenie, povoľ **inštaláciu z tohto zdroja**
4. Ťukni na **Inštalovať**

> Ďalšie aktualizácie ti aplikácia ponúkne sama – stiahne ich prehliadač, potom ich len otvoríš a nainštaluješ. Stiahnuté skladby, knižnica ani playlisty sa pritom nestratia.

---

## Požiadavky

- Android 7.0 alebo novší
- Približne 120 MB voľného miesta
