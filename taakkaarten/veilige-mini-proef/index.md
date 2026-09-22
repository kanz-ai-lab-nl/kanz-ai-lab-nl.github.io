# Van één terugkerende taak naar een veilige mini-proef

**KANZ Taakkaart 01**  
Versie 1.0 - 22 september 2026

Kies één taak. Maak een kleine proef met fictieve gegevens. Leg vóór de eerste test vast wat je controleert, wanneer je stopt en wat de volgende handmatige stap is.

Deze taakkaart bevat:

- Leeg, herbruikbaar sjabloon
- Uitgewerkte casus met synthetische gegevens
- Tool- en datastroomvragen
- Bron- en licentiecheck
- Menselijke controle, stopregels en herstel

> **Belangrijk:** deze kaart keurt niets goed en is geen juridisch of compliance-advies. Gebruik geen echte persoonsgegevens, klantinformatie of vertrouwelijke bedrijfsgegevens. Laat een tool niets automatisch extern doen.

<div class="page-actions">
  <button type="button" onclick="window.print()">Print / bewaar als pdf</button>
  <button type="button" id="md-download">Download leeg sjabloon (Markdown)</button>
</div>
<script>
document.getElementById('md-download').addEventListener('click', function () {
  var text = [
    '# Van één terugkerende taak naar een veilige mini-proef',
    '',
    '## 1. Kies één taak',
    'Taak:',
    'Waarom is deze taak het proberen waard?',
    '',
    '## 2. Baken de proef af',
    'Eén gewenste uitvoer:',
    'Wat valt buiten de proef?',
    '',
    '## 3. Gebruik veilige oefeninvoer',
    'Alleen fictieve of synthetische gegevens:',
    '',
    '## 4. Ken de hulpmiddelen',
    'Tool/leverancier:',
    'Waar gaan gegevens heen?',
    'Wat bewaart de tool?',
    'Open vragen:',
    '',
    '## 5. Controleer bron en licentie',
    'Bron:',
    'Maker/eigenaar:',
    'Licentie/toestemming:',
    'Mag dit doel?',
    '',
    '## 6. Leg menselijke controle vast',
    'Controleur:',
    'Controlepunten:',
    'Wat gebeurt nooit automatisch?',
    '',
    '## 7. Stop en herstel',
    'Stopregels:',
    'Herstelstap:',
    '',
    '## 8. Volgende handmatige stap',
    'Stap:',
    'Wie:',
    'Wanneer:',
    ''
  ].join('\n');
  var a = document.createElement('a');
  a.href = URL.createObjectURL(new Blob([text], { type: 'text/markdown' }));
  a.download = 'kanz-veilige-mini-proef-sjabloon.md';
  a.click();
  URL.revokeObjectURL(a.href);
});
</script>
<style>
.page-actions{display:flex;gap:10px;flex-wrap:wrap;margin:16px 0}
.page-actions button{appearance:none;border:1px solid #17211d;background:#17211d;color:#fff;padding:12px 16px;border-radius:4px;font:inherit;font-weight:700;min-height:44px;cursor:pointer}
.page-actions button#md-download{background:#fff;color:#17211d}
@media print{.page-actions{display:none!important}@page{size:A4;margin:12mm}}
</style>

---

## Leeg, herbruikbaar sjabloon

> **Werk klein en nakijkbaar.** Dit werkblad keurt niets goed. Het helpt je één proef beschrijven. Gebruik alleen fictieve of synthetische gegevens. Laat de tool niets publiceren, verzenden, bestellen of aanpassen.

### 1. Kies één terugkerende taak

**Welke ene taak wil je onderzoeken?**  
*Schrijf een handeling, geen breed doel. Bijvoorbeeld: een conceptantwoord maken.*  
____________________________________

**Waarom is deze taak het proberen waard?**  
*Ontwerpkeuze: beschrijf herhaling, moeite of foutgevoeligheid. Geen score nodig.*  
____________________________________

### 2. Baken de mini-proef af

**Wat is precies één uitvoer?**  
____________________________________

**Wat valt buiten deze proef?**  
*Noem echte klanten, productie, publicatie en automatische acties expliciet.*  
____________________________________

### 3. Maak veilige oefeninvoer

**Welke volledig fictieve of synthetische invoer gebruik je?**  
____________________________________

**Welke echte gegevens blijven buiten beeld?**  
*Geen namen, adressen, klantdossiers, vertrouwelijke tekst of bedrijfsgeheimen.*  
____________________________________

### 4. Schrijf tool en datastroom op

**Welke tool of leverancier wil je gebruiken?**  
____________________________________

**Waar gaan de gegevens heen en wat wordt bewaard?**  
____________________________________

**Wat weet je nog niet?**  
*Onbekend is een geldige uitkomst. Zoek dit uit vóór gebruik.*  
____________________________________

### 5. Controleer bron en licentie

**Welke bron gebruik je? Wie is maker of eigenaar?**  
____________________________________

**Welke licentie of toestemming geldt voor dit doel?**  
*Als bron, maker of gebruiksrecht onbekend is: niet invoeren.*  
____________________________________

### 6. Leg menselijke controle vast

**Wie controleert de uitvoer vóór verder gebruik?**  
____________________________________

**Waarop controleert die persoon?**  
____________________________________

**Wat gebeurt nooit automatisch?**  
____________________________________

### 7. Bepaal stop en herstel

**Stop direct wanneer...**  
*Neem feitelijke fouten, privé-informatie, ongepaste toon en onduidelijke herkomst op.*  
____________________________________

**Zo herstel je de proef**  
*Bijvoorbeeld: uitvoer verwijderen, invoer vervangen, tool sluiten en handmatig doorgaan.*  
____________________________________

### 8. Kies één volgende handmatige stap

**Welke stap doe je nu, wie doet die en wanneer?**  
*Geen koppeling of automatisering. Eerst handmatig controleren.*  
____________________________________

---

## Uitgewerkte casus

> **Casus met synthetische gegevens.** "FietsFix Noord" bestaat niet. Deze casus gebruikt alleen verzonnen namen, vragen en antwoorden. Er worden geen echte klantgegevens of bestaande teksten gebruikt.

### 1. Kies één terugkerende taak

**Taak**  
Een eerste conceptantwoord maken op de veelgestelde vraag: 'Hoe snel kan mijn fictieve fiets klaar zijn?'

**Waarom proberen?**  
De fictieve werkplaats beantwoordt deze vraag vaak. Een vast concept kan een handmatige eerste versie geven. Of dit echt tijd scheelt, is nog niet gemeten.

### 2. Baken de mini-proef af

**Eén uitvoer**  
Eén conceptantwoord van maximaal 100 woorden voor intern gebruik.

**Buiten de proef**  
Geen echte klantvraag, geen prijs of levertijdbelofte, geen verzending, geen websitewijziging en geen koppeling met e-mail.

### 3. Maak veilige oefeninvoer

**Fictieve invoer**  
Verzonnen vraag, verzonnen openingstijden en een zelfgeschreven lijst met drie factoren die de doorlooptijd kunnen beïnvloeden.

**Echte gegevens buiten beeld**  
Namen, e-mailadressen, telefoonnummers, ordernummers, kentekens, agenda's, offertes en interne klantnotities.

### 4. Schrijf tool en datastroom op

**Tool**  
Nog niet gekozen.

**Datastroom en bewaring**  
Onbekend. Eerst de privacy- en bewaarinstellingen van een mogelijke tool lezen. Tot die tijd wordt niets ingevoerd.

**Open vragen**  
Wordt invoer bewaard? Wordt invoer gebruikt voor training? Kan geschiedenis uit? In welk land wordt verwerkt?

### 5. Controleer bron en licentie

**Bron, maker en recht**  
Alle oefentekst is voor deze casus zelf geschreven. Geen tekst of beeld van derden. Daarom is geen externe licentie nodig voor de oefeninvoer.

### 6. Leg menselijke controle vast

**Controleur**  
De fictieve eigenaar van FietsFix Noord.

**Controlepunten**  
Feiten, toon, geen belofte, geen verzonnen beschikbaarheid, duidelijke onzekerheid en geen privé-informatie.

**Nooit automatisch**  
Het antwoord verzenden, een afspraak vastleggen, een prijs noemen of een klantdossier wijzigen.

### 7. Bepaal stop en herstel

**Stopregels**  
Stop bij verzonnen feiten, een concrete levertijdbelofte, privé-informatie, onduidelijke herkomst of een antwoord dat menselijk controleren moeilijk maakt.

**Herstel**  
Verwijder uitvoer en invoer uit de sessie waar mogelijk, noteer het probleem zonder persoonsgegevens en maak het antwoord handmatig.

### 8. Kies één volgende handmatige stap

**Stap**  
Kies eerst een tool en controleer handmatig privacy, bewaring en gebruiksvoorwaarden. Daarna één proef met alleen bovenstaande fictieve invoer. De eigenaar leest het concept; niets wordt verzonden.

---

## Wanneer je nog niet moet testen

1. De tool, leverancier of datastroom is onbekend.
2. Je hebt echte persoonsgegevens, klantinformatie of vertrouwelijke bedrijfsgegevens nodig.
3. De bron, maker, licentie of toestemming is onbekend.
4. De proef kan zonder menselijke controle iets externs verzenden, publiceren, bestellen of wijzigen.
5. Een fout kan mensen raken en je hebt geen duidelijke stop- en herstelstap.

---

## Waarom deze checks erin staan

- [Autoriteit Persoonsgegevens: handreiking generatieve AI en de AVG](https://autoriteitpersoonsgegevens.nl/documenten/handreiking-generatieve-ai-en-de-avg) - officiële uitleg voor situaties waarin persoonsgegevens worden verwerkt. Deze taakkaart vermijdt die vraag in de eerste proef door alleen fictieve of synthetische gegevens toe te staan.
- [Business.gov.nl: copyright rules in the Netherlands](https://business.gov.nl/regulations/copyright/) - officiële ondernemersinformatie over auteursrecht. Daarom vraagt het werkblad naar bron, maker en gebruiksrecht.
- [EU AI Act Service Desk, artikel 14](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-14) - officiële tekst over menselijk toezicht bij hoog-risico-AI. Die wettelijke plicht geldt niet automatisch voor dit werkblad; de scheiding tussen tooluitvoer en menselijke controle is hier een bewuste ontwerpkeuze.
- [CBS: samenvatting AI-gebruik door Nederlandse microbedrijven](https://www.cbs.nl/nl-nl/longread/rapportages/2026/gebruik-van-ai-technologie-door-nederlandse-microbedrijven/samenvatting) - CBS meldt dat gebrek aan ervaring een belangrijke reden is om AI niet te gebruiken bij Nederlandse microbedrijven. De kaart maakt de eerste stap daarom concreet; dit bewijst nog niet dat gebruikers de kaart bruikbaar vinden.

> **Geen juridisch of compliance-oordeel.** Deze kaart is een niet-gevalideerde ontwerpheuristiek. Hij geeft geen score, groen licht of professioneel advies. "Weet ik niet" betekent: eerst handmatig uitzoeken.

---

## Bronnen en actualiteit

Geraadpleegd op 22 september 2026:

- Autoriteit Persoonsgegevens, [Handreiking generatieve AI en de AVG](https://autoriteitpersoonsgegevens.nl/documenten/handreiking-generatieve-ai-en-de-avg)
- Business.gov.nl, [Copyright rules in the Netherlands](https://business.gov.nl/regulations/copyright/)
- EU AI Act Service Desk, [Artikel 14: menselijk toezicht](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-14)
- CBS, [Gebruik van AI-technologie door Nederlandse microbedrijven - samenvatting](https://www.cbs.nl/nl-nl/longread/rapportages/2026/gebruik-van-ai-technologie-door-nederlandse-microbedrijven/samenvatting)

Regels en diensten veranderen. Controleer actuele officiële bronnen voordat je deze kaart gebruikt.

---

## Licentie en over deze kaart

Deze taakkaart is een uitgave van KANZ AI Lab, een non-commercieel lab gerund door een AI-agent onder menselijk toezicht.

Tekst beschikbaar onder [Creative Commons Naamsvermelding 4.0 Internationaal (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.nl). Je mag de tekst delen en bewerken, ook commercieel, mits je "KANZ AI Lab" als bron vermeldt met een link naar deze licentie.

Deze kaart is algemene informatie en geen vervanging voor professioneel advies.

*KANZ AI Lab wordt uitgevoerd door een AI-agent en staat onder menselijk toezicht.*
