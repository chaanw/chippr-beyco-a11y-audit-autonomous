# Rapportage webtoegankelijkheid-test voor Chippr-Beyco

![Uploading free-macbook-pro-on-table-mockup-a11y.jpg…]()

Dit document is een template voor een webtoegankelijkheid-test volgens de Web Content Accessibility Guidelines (WCAG). Een consistente rapportage helpt bij het uitvoeren van een evaluatie en zorgt er voor dat verschillende tests kunnen worden vergeleken.

In deze rapportage wordt de **Coffees Page** getest aan de hand van de checklist van het a11y project.  

Datum webtoegankelijkheid-test: 28-10-2021

Webtoegankelijkheid-test uitgevoerd door: Chaan Soekana

## Inhoudsopgave

  * [Samenvatting](#samenvatting)
  * [Achtergrond bij de evaluatie](#achtergrond-bij-de-evaluatie)
  * [Afbakening](#afbakening)
  * [Beoordelaars](#beoordelaars)
  * [Beoordelingsproces](#beoordelingsproces)
  * [Testresultaten en aanbevelingen](#testresultaten-en-aanbevelingen)
  * [Bijlagen](#bijlagen)
  * [Licentie](#licentie)
  


## Samenvatting

Dit rapport beschrijft in hoeverre de website Beyco (Coffee pagina)overeenstemt met de Web Content Accessibility Guidelines (WCAG) van het W3C. Na de achtergrondinformatie en afbakening van de test worden beoordelaars, beoordelingsproces en testresulltaten beschreven.

Conslusie van deze test luidt dat de Beyco (Coffee pagina) website voldoet de WCAG 2.1, op niveau AA. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.

## Achtergrond bij de evaluatie

De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op 1-11-2021. De website kan ondertussen aangepast zijn.

##  Afbakening

Naam website: Beyco Doel website: Beyco “Beyond Coffee” is een wereldwijd koffie handelsplatform dat kopers en producenten met elkaar in contact brengt. Op dit online platform kunnen producenten hun koffie online verkopen en kunnen kopers koffie vinden die ze zoeken. Daarnaast kun je ook ‘trader’ zijn, iemand die zowel koopt als verkoopt.

De website wordt veel gebruikt in landen zoals Peru. Hier is vaak een slechte internetverbinding en ook heel erg veel zonlicht, daarom is het de bedoeling dat de website goed werkt voor deze gebruikers.

URL Website die wordt getest: https://beyco.nl/trade/offers/public


<!-- ![afbeelding](afbeeldinglink) -->

Test data:

   * 28-10-2021
   * 29-10-2021
   * 01-11-2021

Taal van website: Engels

## Beoordelaars

Chaan Soekana

Student

chaan.soekana@hva.nl

Nederlands

## Beoordelingsproces

Deze beoordelings is uitgevoerd op WCAG 2.1 Niveau AA

De tools die zijn gebruikt voor deze beoordeling zijn de volgende:

   
 * [A11Y Checklist](https://www.a11yproject.com/checklist/)
 *  [WCAG Guidelines Overview](https://www.w3.org/WAI/standards-guidelines/wcag/)
 * [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)


## Testresultaten en aanbevelingen

### Checklist

#### Content

* Het taalgebruik is duidelijk en er worden geen stijlfiguren of metaforen gebruikt. Sommige buttons zijn daarentegen wat minder duidelijk; ‘Learn more’ geeft weinig context. De pagina bevat weinig tekst maar ze worden wel links uitgelijnd en niet in het midden. Mocht de meertaligheid uitbreiden, zou er voor de Arabische uitwerking een nieuw design moeten worden gemaakt, hierbij moeten de teksten namelijk rechts uitgelijnd zijn.

#### Global code

* n.v.t.

#### Keyboard

* Bij de interactieve elementen is er een focus state die past binnen de huisstijl. Helaas zijn niet alle dropdown menu’s navigeerbaar met toetsenbord en zijn er onzichtbare knoppen aanwezig. 

#### Images

* Image elementen hebben geen alt. Bij afbeeldingen met tekst (zoals logo’s) moet de alt beschrijving ook de tekst die in de afbeelding staat bevatten.

#### Headings

* Headings worden goed gebruikt om content de introduceren. Er is maar 1 <code>h1</code> element gebruikt, de headings staan in een logische volgorde en er worden geen heading niveaus overgeslagen

#### Lists

* n.v.t.

#### Controls

* Social media links in de footer hebben geen focus state en geen alt waardoor het niet accessible is voor screenreaders. Buttons gebruiken wel een <code>button</code> element maar hebben geen toegankelijke beschrijving voor screenreaders en er is geen skip link aanwezig. 

#### Tables

* n.v.t.


##  Bijlagen

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
