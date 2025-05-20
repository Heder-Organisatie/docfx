# Docfx

## Wat is Docfx?

Docfx is een tool die gebruikt kan worden om documentatie om te vormen naar webpagina's. Hiervoor wordt intern vooral gebruik gemaakt van [Markdown (.md)](../ittools/markdown.md) bestanden.

## Hoe installeren

Om Docfx te installeren heb je het volgende nodig:

- [.NET SDK](https://dotnet.microsoft.com/en-us/download) 8.0 of hoger
- [Node.js](https://nodejs.org/en) v20 of hoger (dit is optioneel en enkel nodig als men PDF bestanden wilt maken)

Nadat de .NET SDK geïnstalleerd is moet je in een opdrachtvenster het volgende commando invoeren
```
dotnet tool update -g docfx
```
Eens dit commando is uitgevoerd zal Docfx geïnstalleerd zijn en kan je een project opstarten.

## Gebruikers

Iedereen die toegang heeft tot de [GitHub](../ittools/github.md) van Heder zal toegang hebben om aanpassingen te maken binnen Docfx.
Voor een volledige lijst van gebruikers zie het artikel over [GitHub](../ittools/github.md).


## Gebruik


### Opzet project

Om een nieuw project op te starten gebruik je het volgende commando:
```
dockfx init
```
Na de vragen beantwoord te hebben zal een template project opgezet worden waar je in kan werken. Om de webpagina te genereren kan je het volgende commando gebruiken. 
```
dockfx docfx.json --serve
```
Standaard kan je een preview van je site zien op [http://localhost:8080](http://localhost:8080).

### Wijzigen van pagina's

Standaard is er in een nieuw project een docs folder. In deze folder kunnen er markdown bestanden gezet worden die omgevormd worden in HTML pagina's, ook kan er een toc.yml bestand aangemaakt worden dat dient als inhoudsopgave.

Je kan ook nieuwe folders aanmaken in de mappenstructuur om zo op een meer georganiseerde manier te werken. In deze nieuwe mappen kan je zonder problemen nieuwe markdown of .yml bestanden zetten.
