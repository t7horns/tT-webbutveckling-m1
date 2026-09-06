# Assignment
Du ska skapa en webbplats bestående av tre sidor som handlar om dig själv och något du är intresserad av – en hobby, sport, spel, musik, ett husdjur eller något annat du tycker om.

## Mappstruktur
Organisera dina filer enligt följande struktur:

dt224g_fornamn_efternamn/
├── index.html
├── hobby.html
├── kontakt.html
└── images/
    └── (dina bildfiler)

## Gemensamma krav för alla sidor
Samtliga tre sidor ska innehålla:

- [x] Korrekt HTML-dokumentstruktur med <!DOCTYPE html>, <html lang="sv">, <head> och <body>,
- [x] En <header> med webbplatsens namn - du väljer själv vad din webbplats ska heta.
- [x] En <nav> i headern med länkar till alla tre undersidor (index.html, hobby.html och kontakt.html),
- [x] En <main> med sidans huvudinnehåll,
- [x] En <footer> med en copyright-rad, t.ex. © 2026 Ditt Namn, samt en länk till kontaktsidan.
- [x] Samtliga sidor ska valideras utan fel i W3C:s HTML-validator

Sidorna ska följa grundläggande tillgänglighetsprinciper 
— [x] semantiska element
- [x] alt-texter på bilder
- [x] korrekt formulär- och tabellstruktur

## index.html – Startsida
Startsidan ska innehålla en kort presentation av dig själv. Här berättar du vem du är, var du kommer ifrån och vad du är intresserad av. Sidan ska innehålla:

- [x] Minst två rubriknivåer (<h1>, <h2>)
- [x] Minst två paragrafer med text (<p>)
- [x] Minst en bild på dig själv eller något som representerar dig, med beskrivande alt-text.

## hobby.html – Hobbysida
Den här sidan handlar om ditt valda intresse. Sidan ska innehålla:

- [x] Minst två bilder med beskrivande alt-texter,
- [x] Minst två rubriknivåer (, ),
- [x] Minst en paragraf med text där du kortfattat beskriver ditt valda intresse (),
- [x] En tabell med relevant innehåll kopplat till ditt intresse, t.ex. en topplista, ett schema eller faktatabell. Den ska innehålla minst fyra kolmner och tre rader,
- [x] Tabellen ska ha korrekt struktur med <thead>, <tbody> och <th>,
- [x] En extern länk till en relevant webbplats, t.ex. en officiell sida eller Wikipedia, med target="_blank" och rel="noopener".

## kontakt.html – Kontaktsida
Kontaktsidan ska innehålla ett kontaktformulär samt en alternativ kontaktväg med länk till e-postadress. Sidan ska innehålla:

Ett kontaktformulär med:

[x] Minst tre olika typer av inputfält (t.ex. text, email, textarea, checkbox eller radio),
[x] Korrekt användning av <label> kopplat till respektive fält med for och id,
[x] En skicka-knapp (<button type="submit">).
[x] Ett exempel kan vara fält för namn, e-post, meddelande och submit-knapp.

En kort introducerande text med en mailto:-länk, t.ex.:

[x] "Du kan också nå mig direkt på [student_id@student.miun.se]"

## Krav för godkänt
För att uppgiften ska anses vara godkänd krävs det att:

- [x] Alla tre sidor är skapade enligt instruktionerna ovan,
- [x] Navigeringen fungerar korrekt mellan samtliga sidor,
- [x] Sidorna följer grundläggande tillgänglighetsprinciper,
- [x] Samtliga sidor validerar utan fel i W3C:s HTML-validator,
- [x] Momentet ska lämnas in som en komprimerad fil i zip-format (ej rar, 7zip eller annat) innehållande samtliga undersidor och bilder. Döp filen med strukturen dt224g_fornamn_efternamn.av u