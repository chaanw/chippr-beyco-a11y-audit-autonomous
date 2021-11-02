
# Rapportage webtoegankelijkheid-test voor Chippr-Beyco

Dit document is een template voor een webtoegankelijkheid-test volgens de Web Content Accessibility Guidelines (WCAG). Een consistente rapportage helpt bij het uitvoeren van een evaluatie en zorgt er voor dat verschillende tests kunnen worden vergeleken.

In deze rapportage wordt het **detail pagina** getest aan de hand van de checklist van het a11y project.  

Datum webtoegankelijkheid-test: 28-10-2021

Webtoegankelijkheid-test uitgevoerd door: Finn van Bekkum

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



## Achtergrond bij de evaluatie

De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op 1-11-2021. De website kan ondertussen aangepast zijn.

##  Afbakening

https://beyco.nl/

Beyco zorgt voor een platform waar verkopers en inkopers met elkaar in contact kunnen komen.

https://test.beyco.chippr.dev/

https://test.beyco.chippr.dev/trade/offers/8f3622d6-75a1-43b8-a960-3daecc5c880a


![afbeelding](https://user-images.githubusercontent.com/26089533/139428771-4d6678e4-d6ab-48e7-b6fc-06e987d8828f.png)

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

* Bij de interactieve elementen is de focus state duidelijk zichtbaar en past binnen de huisstijl. Helaas zijn niet alle dropdown menu’s zijn navigeerbaar met toetsenbord.

#### Images

* Image elementen hebben geen alt. Bij afbeeldingen met tekst (zoals logo’s) moet de alt beschrijving ook de tekst die in de afbeelding staat bevatten.

#### Headings

* Headings worden goed gebruikt om content de introduceren. Er is maar 1 <h1> element gebruikt, de headings staan in een logische volgorde en er worden geen heading niveaus overgeslagen

#### Lists

* n.v.t.

#### Controls

* Social media links in de footer en de link naar de homepage (logo) worden niet beschreven waardoor het niet accessible is voor screenreaders. Buttons gebruiken een <button> element maar hebben geen toegankelijke beschrijving voor screenreaders en er is geen skip link aanwezig. Daarentegen zijn focus states wel duidelijk zichtbaar en worden er geen links in een ander tabblad geopend

#### Tables

* n.v.t.


##  Bijlagen

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
