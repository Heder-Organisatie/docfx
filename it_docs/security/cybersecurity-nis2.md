

<form id="searchForm">
  <p>Wat?</p>

  <label>
    <input type="radio" name="mainChoice" value="waarom"> Waarom
  </label><br>

  <label>
    <input type="radio" name="mainChoice" value="wie"> Wie
  </label><br>

  <div id="followUp" style="margin-top: 10px; display: none;">
    <p>Waarom?</p>
    <label>
      <input type="radio" name="followUpChoice" value="waarom1"> Waarom 1
    </label><br>
    <label>
      <input type="radio" name="followUpChoice" value="waarom2"> Waarom 2
    </label><br>
  </div>

  <button type="submit" style="margin-top: 10px;">Submit</button>
</form>

<script>
document.getElementById('searchForm').addEventListener('change', function () {
  const mainChoice = document.querySelector('input[name="mainChoice"]:checked');
  const followUpDiv = document.getElementById('followUp');

  // Show follow-up only if "waarom" is selected
  if (mainChoice && mainChoice.value === 'waarom') {
    followUpDiv.style.display = 'block';
  } else {
    followUpDiv.style.display = 'none';
  }
});

document.getElementById('searchForm').addEventListener('submit', function (e) {
  e.preventDefault();

  const mainChoice = document.querySelector('input[name="mainChoice"]:checked')?.value;
  const followUpChoice = document.querySelector('input[name="followUpChoice"]:checked')?.value;

  if (mainChoice === 'waarom') {
    if(followUpChoice === "waarom1"){
        const target = document.getElementById('waarom');
        if (target) target.scrollIntoView({ behavior: 'smooth' });
    }
    else if (followUpChoice ==="waarom2"){
        const target = document.getElementById('wie');
        if(target) target.scrollIntoView({behaviour:'smooth'});
    }
  }

  if (mainChoice === 'wie') {
    const target = document.getElementById('wie');
    if (target) target.scrollIntoView({ behavior: 'smooth' });
  }

  // You can add more follow-up actions here as needed
});
</script>


# Wat houdt de cybersecurity-wetgeving in voor zorginstellingen? 

De cybersecurity-wetgeving (NIS2-richtlijn - Network and Information Security 2) is een Europese wet die vanaf oktober 2024 ook geldt in België. Deze wet is bedoeld om de digitale weerbaarheid van belangrijke sectoren te verbeteren. Voor grotere zorginstellingen zoals Heder betekent dit dat zij aan strengere regels moeten voldoen om hun digitale systemen en gegevens te beschermen.   

De Belgische overheid heeft in dit kader [het Cybersecurity Center Belgium (CCB) https://ccb.belgium.be/nl](https://ccb.belgium.be/nl) opgericht die instaat voor de definitie, sensibilisatie, opleiding en opvolging van de Cybersecurity bij particulieren en bedrijven in België. 


<div id="waarom">

## Waarom is NIS2 nodig?

Zorginstellingen zijn steeds afhankelijker geworden van digitale systemen voor het opslaan van patiëntgegevens, communicatie tussen afdelingen, medicatiebeheer en nog veel meer. Tegelijkertijd zijn zij steeds vaker doelwit van cyberaanvallen. Denk aan hackers die systemen platleggen of gevoelige patiëntgegevens stelen. De gevolgen hiervan kunnen ernstig zijn: uitval van zorg, gevaar voor patiënten en verlies van vertrouwen. NIS2 moet dit risico beperken door betere beveiliging verplicht te stellen. 

</div>

<div id="wie">

## Wie valt onder NIS2? 

NIS2 geldt voor zogeheten "essentiële" en "belangrijke" organisaties in sectoren zoals energie, transport, drinkwater, digitale infrastructuur én de gezondheidszorg. Grote zorginstellingen met meer dan 250 FTE vallen automatisch onder deze regels, omdat ze als essentieel voor de samenleving worden gezien.  

</div>

## Wat moet een zorginstelling doen? {#wat}

Zorginstellingen moeten voldoen aan verschillende verplichtingen: 

1. **Risicobeheer en beveiliging:** Instellingen moeten risico’s in kaart brengen en passende maatregelen nemen. Denk aan firewalls, antivirussoftware, toegangsbeheer, back-ups, en training van medewerkers en beheerders. 

2. **Incidenten melden:** Ernstige IT-incidenten, zoals datalekken of uitval van systemen, moeten binnen 24 uur gemeld worden aan het Nationaal Cyber Security Centrum of de toezichthouder. 

3. **Toezicht en controle:** De overheid houdt toezicht. Als instellingen zich niet aan de regels houden, kunnen er sancties volgen, zoals boetes. 

4. **Zorgplicht voor de toeleveringsketen:** Een zorginstelling moet niet alleen haar eigen beveiliging op orde hebben, maar ook die van leveranciers van digitale diensten goed controleren. 

5. **Aanstelling van een verantwoordelijke:** Instellingen moeten iemand aanstellen die verantwoordelijk is voor informatiebeveiliging en NIS2-compliance. 

## Wat betekent dit concreet? 

- Er moet meer aandacht en geld naar cyberbeveiliging. 

- IT-afdelingen krijgen meer verantwoordelijkheden. 

- Bestuurders kunnen persoonlijk aansprakelijk worden gesteld bij ernstige nalatigheid. 

- De hele organisatie moet bewuster omgaan met digitale veiligheid, van arts tot administratief medewerker. 

**Samengevat:** 

De NIS2-wetgeving verplicht grote zorginstellingen om digitale veiligheid serieus te nemen en structureel te verbeteren. **Het is geen vrijblijvende richtlijn,** maar een set duidelijke eisen met mogelijke boetes als deze niet worden nageleefd. Het doel is om de continuïteit van de zorg te waarborgen in een tijd waarin cyberdreigingen steeds groter worden. 