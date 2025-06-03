# GitHub

## Wat doet GitHub

[GitHub](https://github.com) is een online platform dat git-repositories beheert. Git-repositories kunnen beschouwd worden als een gemeenschappelijke folder met documenten en bestanden waar door meerdere mensen samen aan gewerkt kan worden met versiebeheer.

Wij gebruiken GitHub om alle code en scripts op een gecentraliseerde plaats bij te houden en ook een backup te hebben van vorige versies. Elk script dat geschreven wordt maar ook deze documentatie worden dus bijgehouden.

## Hoe installeren

Om GitHub goed te kunnen moet je een GitHub-account en GitHub Desktop hebben.

1. Ga naar [desktop.github.com](https://desktop.github.com/download/) en download GitHub Desktop
2. Open GitHubDesktopSetup-x64.exe en volg de stappen. Deze toepassing zal verschijnen bij je downloads.
3. Nadat de installatie is afgerond zal je moeten inloggen met een GitHub-account.
4. Eens je account is toegevoegd aan de Heder organisatie kan je op "Clone a repository from the internet" klikken en de juiste repository kopieëren.

Officiële documentatie voor GitHub kan je vinden op de volgende links:

- [docs.github.com](https://docs.github.com/en) voor het gebruik van GitHub
- [docs.github.com/en/desktop](https://docs.github.com/en/desktop) voor het gebruik van GitHub Desktop.

## Gebruikers

Elke ICT-medewerker zal een eigen GitHub-account hebben, buiten deze accounts zal er ook nog een algemeen admin account bestaan.

|Username|Wachtwoord|
|---|---|
|github.hadmin@heder.be|zie 1Password|

## Hoe gebruik je GitHub

### Een repository aanmaken

Om een nieuwe repository aan te maken ga je naar de organisatie op GitHub.com ([https://github.com/Heder-Organisatie](https://github.com/Heder-Organisatie)) en klik je op de knop "New". Hier kan je dan de naam van je repository/project opgeven, een optionele beschrijving, de privacy settings en een licentie kiezen. 
De repository zal altijd op "Private" gezet worden, dit zorgt ervoor dat enkel mensen binnen de organisatie de repository kunnen bekijken/bewerken.
Met de licentie moet geen rekening gehouden worden, alles wat op GitHub staat zal enkel binnen Heder gebruikt worden.

Eens je op de knop "Create repository" klikt zal er een nieuwe lege repository aangemaakt worden.

### Een repository clonen

Om de repository van GitHub op je lokale machine te zetten doe je het volgende:

1. Open GitHub Desktop
2. Klik bovenaan op "File"
3. Druk op "Clone repository..." (de shortcut "Ctrl+Shift+O" werkt ook)
4. Onder "Heder-Organisatie" vind je een lijst van alle repositories die gekoppeld zijn aan de organisatie. Klik hier op de repository die je wilt kopieren.
5. Selecteer bij "Local path" de locatie op de computer waar je de repository wilt opslaan.
6. Druk op "Clone"

Er staat nu een versie van de repository op je lokale computer, in deze aangemaakt folder kan je nu werken en je wijzigingen op GitHub zetten.

### Wijzigingen opslaan

[Voeg hier nog iets toe over aanpassingen opslaan]: <>
Eens je klaar bent om je wijzigingen naar GitHub te sturen doe je jet volgende:

1. Controleer of je de veranderingen ziet op GitHub Desktop, indien dit niet het geval is, moet je mogelijks het bestand nog eens opslaan.
2. Links onderaan het venster van GitHub Desktop geef je een beschrijvende titel aan je commit, je kan ook een optionele beschrijving meegeven.
3. Klik onderaan op de knop "Commit *number of changed files* file(s) to *branch name*"
4. Druk op de knop "Push Origin".

### Branching

De kans is groot dat meerdere mensen aan dezelfde repository werken, zeker als het een groot project is. Om te voorkomen dat iedereen dezelfde versie aanpast en mogelijks dingen kapot maakt of iemands aanpassingen ongedaan maakt, kan men werken met branches. Een branch in git is een aftakking van de huidige versie, aanpassingen kunnen hierop gemaakt worden zonder de "hoofdversie (vaak de "main" genoemd) te beïnvloeden.

Om een nieuwe branch aan te maken op GitHub Desktop doe je het volgende:

1. Zorg dat je de huidige versie gefetched hebt.
2. Klik op de knop "Current branch", standaard staat hier de branch "main" aangeduid.
3. Druk op de "New branch knop".
4. Geef de naam van je branch en selecteer op welke branch het gebaseerd is.
5. Druk op "Push origin" om de nieuwe branch naar GitHub te pushen.

### Definities

|Term|Beschrijving|
|---|---|
|Commit|Een aanpassing in een repository|
|Push|Een of meerdere commits naar GitHub sturen|
|Fetch|Aanpassingen die op GitHub staan (mogelijks door andere mensen) ophalen|
|Branch|Een aftakking van een repository|