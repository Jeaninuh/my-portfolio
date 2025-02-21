---
title: AI Course Generator
publishDate: 2025-29-01
img: /assets/stock-1.jpg
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  Voor een learning management system heb ik onderzoek gedaan naar en een ontwerp gemaakt voor een AI course generator.
tags:
  - UI Design
  - UX Research
  - User Testing
---

<a href=#overzicht>Overzicht</a><br/>
<a href=#onderzoek>Onderzoek</a><br/>
<a href=#concept>Concept</a><br/>
<a href=#testen>Testen</a><br/>
<a href=#design>Design</a><br/>
<a href=#conclusie-en-geleerde-lessen>Conclusie en geleerde lessen</a>

## Overzicht

Voor een learning management system heb ik meegeholpen aan het ontwikkelen van een AI course generator. Als UI/UX designer heb ik onderzoek gedaan, een gebruiksvriendelijke interface bedacht, getest en uiteindelijk ontworpen. Voor dit project heb ik nauw samengewerkt met de AI developer van het team.

_Uitdagingen en beperkingen_<br/>
Tijdens dit project kreeg ik ook te maken met bepaalde randvoorwaarden die invloed hadden op mijn design proces:

- De variabelen waar de course generator op gebaseerd zou worden, stonden van tevoren al vast
- Het project moest in een korte tijdspanne van 4 weken en met beperkte middelen worden uitgevoerd

Benieuwd naar het eindresultaat en de belangrijkste bevindingen? <a href=#design>Scroll dan gelijk door naar de designs en de conclusie.</a>

## Onderzoek

We begonnen het project met heel veel vragen, zoals:

- Hoe sluit de generator aan op de businessdoelen en de wensen en behoeften van de opdrachtgever?
- Hoe zorgen we ervoor dat de gebruikerservaring en de output van de generator goed didactisch onderbouwd zijn?
- Hoe leren studenten het beste en hoe volgen ze het liefst een training?
- Wat vinden de verschillende doelgroepen van het genereren van en leren van lesmateriaal gemaakt met behulp van AI?

Voor antwoorden op deze en meer vragen hebben we user interviews gehouden met 3 belangrijke doelgroepen:

- **De product owners**: om erachter te komen hoe de businesspropositie binnen het plaatje past.
- **Onderwijsprofessionals**: om te ontdekken hoe lesmateriaal en curricula worden ontwikkeld.
- **Studenten**: om te leren hoe mensen het beste leren en lesmateriaal willen verwerken.

Voordat we aan de interviews begonnen, heb ik eerst een user flow gemaakt. Normaal gesproken word die verderop in het proces gemaakt, maar de reden dat ik dat op dit moment al deed, was omdat ik graag met het developmentteam wilde schakelen om de juiste verwachtingen te scheppen en om goedkeuring te krijgen van de product owners.

<div data-lightbox="true">
<Image src="../../assets/userflows/userflow1.png" alt="A part of a user flow of a teacher generating a course with AI"></Image>
</div>
(Klik op de afbeeldingen om in te zoomen)<br/>
<a href="https://www.figma.com/design/xtrIubMX2FrYrcuKDBoXYT/AI-Course-Generator?node-id=0-1&t=QVOl3j0uTwqJW3DD-1" target="_blank">Bekijk de volledige user flow in Figma</a>

### Belangrijkste bevindingen

Met behulp van NotebookLM kon ik de interviews snel en tegelijkertijd analyseren. Hierdoor kon ik snel en makkelijk patronen ontdekken en inzichten verzamelen. Een aantal van de meest belangrijke bevindingen waren:

- **Begin bij het ontwikkelen van lesmateriaal met de leerdoelen.** Van daaruit ontwerp je lesmateriaal en de toetsen. Dit wordt ook wel "backwards design" genoemd.
- Het is belangrijk dat **de moeilijkheidsgraad aansluit bij de voorkennis** van de studenten zodat de stappen niet als te groot of te klein worden ervaren.
- **Interactie is cruciaal voor het leren.** Dit kan in de vorm van groepsopdrachten, discussies of bijvoorbeeld een dialoog met een (AI-)tutor. E-learning moet niet alleen zenden zijn, maar het moet ook interactie stimuleren.
- Er is **meer vertrouwen in AI** gegenereerd lesmateriaal als het **gebaseerd is op betrouwbare bronnen** en als er een feedbackloop is ingebouwd (onder andere van studenten).

#### Uitdaging

Voor de cursistendoelgroep hadden we geen werknemers van de klanten van de opdrachtgever om te interviewen tot onze beschikking. Wel had de opdrachtgever een e-maillijst met gebruikers die al eerder trainingen via hun hadden gevolgd toen het platform nog een open B2C platform was. We kregen echter weinig respons toen we een oproep deden.

#### Oplossing

Om mensen aan te sporen, werd er een beloning aangeboden: Als respondenten zouden meedoen aan een aantal gebruikersonderzoeken (waaronder een diepte-interview voor dit project) kregen ze een jaar lang gratis toegang tot de bibliotheek aan trainingen. Uiteindelijk hebben we 1 iemand hierdoor kunnen interviewen. De feedback van de respondent was enorm waardevol!

## Concept

Met het onderzoek achter de rug en met vele ideeën in petto ging ik aan de slag met een eerste versie. Hiervoor heb ik lo-fi wireframes gemaakt.<br/>
Ik heb ervoor gekozen om de generator als een wizard vorm te geven. Hierdoor kun je de gebruiker stap voor stap door een nieuwe feature leiden, waarbij de hoeveelheid informatie per stap beheersbaar blijft.

<div data-lightbox="true">
<Image src="../../assets/lofi-wireframes/10-lofi-step4-3.jpg" alt="A lofi wireframe of step 4 of the course generator user flow" />
</div>
(Klik op de afbeeldingen om in te zoomen)

Voor sommige stappen in de user flow heb ik meerdere versies gemaakt en getest om erachter te komen wat de testers ervan vonden.<br/>

<a href="https://www.figma.com/design/xtrIubMX2FrYrcuKDBoXYT/AI-Course-Generator?node-id=0-1&t=QVOl3j0uTwqJW3DD-1" target="_blank">Bekijk de wireframes in Figma</a>

## Testen

Voor de test heb ik 5 mensen uitgenodigd om de lo-fi wireframes te testen. Het verliep als volgt:

1. De tester kreeg een scenario voorgelegd
2. Ik stelde enkele vragen over het platform en wat hun verwachtingen waren
3. Ik liep samen met de tester stap voor stap door de interfaces en stelde vragen zoals “Waarom klik je daar op?" en “Wat verwacht je op het volgende scherm te zien?”
4. Een aantal stappen hadden verschillende versies, wat ik niet aan de testers vertelde. Ik vroeg bij de eerste versie wat ze ervan vonden en of ze iets anders zouden willen zien. Daarna liet ik ze de andere versies van dezelfde stap zien. Hun feedback gaf óf bevestiging welke versie het meeste beviel, óf gaf me weer heel andere inzichten en ideeën.

Aan het einde vroeg ik naar hun ervaring met de gehele flow, wat ze goed vonden, wat ze verraste en wat verbeterd zou kunnen worden.

### Belangrijkste bevindingen

- **De AI course generator moet beter vindbaar zijn.** Testers zochten naar een manier om de course generator te vinden en misten duidelijke informatie hierover op de homepagina of in het hoofdmenu.
- **De stappen** in de AI training generator worden als **overzichtelijk** ervaren, met name door de linker navigatiebalk.
- **De definities van 'beginner, gemiddeld en gevorderd' zijn subjectief.** Testers interpreteerden de termen op verschillende manieren. Sommigen dachten dat een visuele schaal van 0-10 zou kunnen helpen. Een versie met extra contextuele informatie bij deze opties werd positiever ontvangen.
- **De vraag over de doorlooptijd van de training was verwarrend en leidde tot vragen over hoe de AI dit zou interpreteren.** Testers hadden veel vragen over wat er precies werd bedoeld met de vraag over de doorlooptijd. Sommigen dachten aan trainingsdagen, anderen aan het aantal uren per week. Er werd gesuggereerd om duidelijker te zijn over de studielast en de relatie met de hoeveelheid lesmateriaal
- **De vraag over de doelgroep was vaag en leidde tot onduidelijkheid over wat er van de testers werd verwacht.** Testers waren onzeker over wat ze moesten invoeren bij de vraag over de doelgroep. Sommigen verwachtten een dropdown met sectoren. Een versie met een placeholder tekst werd beter ontvangen, maar het moet duidelijk zijn dat gebruikers uiteindelijk zelf iets moeten invoeren.

#### Uitdaging

De tests konden niet worden gedaan door directe leden van de doelgroepen, zoals de onderwijsprofessionals of de student. Ik moest dus op zoek naar alternatieve testers.

#### Oplossing

Ik heb 5 werknemers van het moederbedrijf van de opdrachtgever gevraagd om deel te nemen als testers. Dit waren werknemers van andere afdelingen, zoals office managers en medewerkers van marketing en sales. Omdat ze niet direct betrokken waren bij het project hadden ze een frisse en onbevooroordeelde blik. Bovendien was de test snel en lokaal uit te voeren, omdat de meeste testers op hetzelfde kantoor aanwezig waren.

## Design

Nadat ik de resultaten van de tests had geanalyseerd, heb ik een definitief ontwerp gemaakt.

#### Opmerkingen

Het systeem waar het design uiteindelijk in gebouwd zal worden heeft een development freeze, omdat er wordt gewerkt aan een nieuw systeem met een nieuwe tech stack. Hierdoor was ik beperkt tot het gebruik van de huidige implementatie van de component library en design systeem. Hier is het uiteindelijke ontwerp ook op gebouwd.

<div data-lightbox="true">
<Image src="../../assets/learning-goals-screen-design.jpg" alt="A design of the goals screen of the course generator" />
</div>
(Klik op de afbeeldingen om in te zoomen)<br/>
<a href="https://www.figma.com/design/xtrIubMX2FrYrcuKDBoXYT/AI-Course-Generator?node-id=0-1&t=QVOl3j0uTwqJW3DD-1" target="_blank">Bekijk de volledige designs in Figma</a>

## Conclusie en geleerde lessen

- De user flow was al snel bedacht, omdat ik wilde checken bij development of mijn ideeën mogelijk waren in het huidige systeem. Deze user flow heb ik ook laten zien tijdens de interviews met de onderwijsprofessionals. Als ik hier op terugkijk had ik dit liever niet gedaan. Hierdoor had ik de onderwijsprofessionals al in een bepaald stramien laten nadenken. Dit gaf wel structuur aan het interview, maar beperkte ze wel in hun antwoorden.
- Tijdens interviews is het belangrijk geen sturende of gekleurde vragen te stellen. Om dit zoveel mogelijk te voorkomen heb ik na elk interview bewust gereflecteerd op hoe het ging en wat beter kon. Hierdoor had ik snel door wat ik kon veranderen waardoor de opvolgende interviews een stuk beter gingen. Dit is iets wat ik graag wil blijven doen in toekomstige projecten.
- Tijdens de usability tests had ik te snel de conclusie getrokken dat de course generator beschikbaar zou zijn in het dashboard. Dit was terug te zien in mijn lo-fi wireframes, maar uit de gesprekken met de testers kwam naar voren dat dit niet hun eerste gedachte was. Hier heb ik mijn eigen aannames dus laten doorschemeren.
