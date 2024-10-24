# Justify Your Tech-Stack

Verantwoord en presenteer je keuze voor een tech-stack.

![image](https://github.com/user-attachments/assets/85a58afa-c646-4736-8593-24c80e813c93)

## Inleiding

In deze opdracht onderzocht ik  een nieuwe tech-stack en verantwoord ik deze gebaseerd op UX, DX en CMX. Het doel van deze opdracht was om te leren hoe ik een onderbouwde keuze kan maken voor een passende tech-stack en hoe ik deze bevindingen kan presenteren.

De tech-stack die ik onderzocht mocht bestaan uit frameworks als Astro, React, Angular, etc. Het was de bedoeling dat ik iets koos waar ik nog geen ervaring mee had zodat ik kon ontdekken wat de voor- en nadelen zijn van deze stack.

Ik heb na een kort onderzoek gekozen voor Enhance. Deze was niet mijn eerste keuze (Astro 👀) maar toen ik in eerste instantie onderzoek deed naar een snel framework die het simpel maakt statische code te renderen, maar ook goed te werk kan gaan met een API kwam ik uit tussen Qwik en Enhance, maar Enhance was uiteindelijk toch het framework waar ik voor ging.

![image](https://github.com/user-attachments/assets/fe6e81df-e4b6-4c45-a403-be084c5bc872)

Tijdens deze opdracht heb ik de volgende stappen doorlopen:

## 1. User Experience (UX)
Ik onderzocht de gebruikerservaring van de gekozen tech-stack. Het was hierbij lastig om iets specifiek aan deze tech stack te vinden buiten performance, het is namelijk aan de developer om goede UX principes toe te passen om de site accessible te maken, maar performance speelt ook een grote rol in UX en kan per tech-stack op de langere termijn toch een verschil maken.

### Performance
Om de performance te optimaliseren biedt Enhance SSG, dit helpt met:

**Schaalbaarheid:** Statische delen kunnen gemakkelijk worden gestuurd via een CDN (content delivery network), hierdoor wordt de site opgehaald vanuit de dichtsbijzijnde server.

**JAMstack:** Met dynamische elementen zoals de interactieve agenda helpt JAMstack (JavaScript, APIs, en Ma## 2. Developer Experience (DX)
Ik analyseerde de ontwikkelervaring met Enhance. Hierbij keek ik naar functionaliteit, gebruiksgemak en ondersteuning.
## 2. Developer Experience (DX)

### Scalability
Enhance is ontworpen met components in het achterhoofd, wat het makkelijker maakt voor het toevoegen van nieuwe functies zonder negatieve invloed op de prestaties. Het framework ondersteunt server-side rendering, wat helpt bij het efficiënt laden van content, ook als de applicatie groeit.

### Ease of used
Hoewel ik om mijn svelte project over te zetten naar enhance niet veel ingewikkelde code hoefde over te zetten, moet ik zeggen dat het erg intuitief was. Enhance maakt gebruik van ``.mjs`` bestanden waarin ik mijn html in een functie moet schrijven en returnen. 

### Support
Enhance heeft een behulpzame community met een Discord-kanaal en GitHub-repositories. De documentatie is goed gestructureerd, wat helpt bij een soepele ontwikkelervaring, maar van wat ik kon vinden zijn er nog weinig tutorials van te vinden, en het heeft nog niet eens zijn eigen stack overflow tag, dus het is lastig om buiten het discord kanaal en documentatie antwoord op je vragen te krijgen. 

![image](https://github.com/user-attachments/assets/4f15c951-2828-40d2-a984-fe2e6215cde2)


## 3. Content Management Experience (CMX)
Enhance geeft een goede ervaring voor contentbeheer, ideaal als contentbeheerders aangezien het gaat over het CMS dat je gebruit, Enhance doet daar niet moeilijk over. 

![image](https://github.com/user-attachments/assets/2c528577-d9a7-49f8-a6ff-ef2c962a9adc)


### Integratie met CMS
Enhance werkt goed met verschillende headless CMS-systemen zoals Strapi en Sanity. Hierdoor kunnen content beheerders eenvoudig via een CMS content invoeren en bewerken.

### 4. Conclusies
Omdat het framework en de content management meerendeels apart gebeurd is het niet nodig voor contentbeheerders om veel kennis te hebben over HTML, CSS en Javascript. Hoewel de code voor het ophalen van data best simpel is, en dus met de hiervoor genoemde basiskennis te begrijpen, is het niet nodig.


## Conclusie User Experience (UX)
Enhance presteert uitstekend op het gebied van snelheid dankzij SSR en SSG. Deze technieken zorgen voor snelle laadtijden en een goede gebruikerservaring. Wat toegankelijkheid betreft, biedt Enhance genoeg flexibiliteit (zoals elk framework zou moeten) om best practices voor toegankelijkheid toe te passen, maar het is aan de ontwikkelaar om ervoor te zorgen dat de site ook echt toegankelijk is. 

## Conclusie Developer Experience (DX)
Enhance is gebruiksvriendelijk voor ontwikkelaars door zijn intuïtieve structuur. Het maakt gebruik van een eenvoudige syntax wat de leercurve verlaagt. De documentatie is goed gestructureerd en de community is behulpzaam, al hoewel er nog weinig vragen- en antwoorden beschikbaar zijn buiten het Discord-kanaal. 

## Conclusie Content Management Experience (CMX)
Enhance biedt een goede ervaring voor contentbeheerders, vooral wanneer het gekoppeld is aan gebruiksvriendelijke headless CMS-systemen zoals Sanity (Werken sinds kort samen). De interface van deze CMS-oplossingen maakt het beheren van content een stuk makkelijker. Voor complexere taken kan enige kennis van HTML, CSS en JavaScript nuttig zijn, maar dit is niet nodig voor de dagelijkse contentbeheer.

## Aanbevelingen
Om Enhance succesvol in te zetten, moet er een duidelijke scheiding zijn tussen content en presentatie. Zorg voor een goed gekozen headless CMS dat past bij de behoeften van de contentbeheerders. Het is ook belangrijk om een basiskennis van HTML, CSS en JavaScript te hebben om complexere integraties te kunnen overzien.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).


