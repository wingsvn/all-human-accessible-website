> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](https://github.com/fdnd-task/all-human-accessible-website/blob/main/docs/INSTRUCTIONS.md)

# Mijn OBA platform: uitleningen
Voor de opdrachgever OBA heb ik een website gebouwd voor de uitleningen binnen het mijn OBA platform. Ik heb hierbij gewerkt vanuit de feedback van een versie (ook door mij) van de vorige sprint. Voor deze 2e versie van de website heb ik me naast het verwerken van de feedback me vooral bezig gehouden met de toegankelijkheid volgens de WCAG richtlijnen. Hiervoor heb ik voorafgaand een aantal toegankelijkheidstesten uitgevoerd: Lighthouse test, handmatige testen, zoals de keyboard en screenreader test.


## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
Userstory: "Toon in een overzicht alle abonnementen van een familie met een verwijzing naar een indiviueel profiel van elk familielid, met de functies: familieleden, beschikbare diensten, laatst geleende boeken en in te leveren boeken om boete te voorkomen."

Mijn OBA uitleningen pagina bestaat uit 2 delen, namelijk de navigatiebar en uit de homepage met uitleningen zelf. Op de navigatiebar vindt je een search-box, darkmodus en linkjes naar andere pagina's binnen het mijn OBA platform. Deze is ook in- en uit te klappen mocht dat nodig zijn. Op de homepage met de uitleningen vindt je alle uitgeleende producten en materialen op volgorde van boeken, DVD's en CD's. Per categorie staan de producten horizontaal naast elkaar en kun je door middel van scrollen, de rest van de producten zien, die evt. niet in beeld zijn. Elk product heeft verder nog een verleng button, mocht de gebruiker het product nog langer willen lenen. En bijna in te leveren producten zijn voorzien van een rode font voor de urgentie er van. Voor een duidelijker overzicht staat er boven op de pagina ook nog het totaal aantal producten die de gebruiker nog moet inleveren. 

<!-- Voeg een mooie poster visual toe 📸 -->
<img width="255" alt="image" src="https://github.com/wingsvn/all-human-accessible-website/assets/144009709/35966dcf-4123-48e2-a85f-f49423dd07f1">

<img width="650" alt="image" src="https://github.com/wingsvn/all-human-accessible-website/assets/144009709/95ab95df-69ea-490f-93c5-1c3283f4c634">

<img width="905" alt="image" src="https://github.com/wingsvn/all-human-accessible-website/assets/144009709/18643485-62ca-42fc-860f-e19dcbdef131">

<img width="905" alt="image" src="https://github.com/wingsvn/all-human-accessible-website/assets/144009709/9791e4de-dfc7-4a9d-b3a2-90a880f10659">

<!-- Voeg een link toe naar Github Pages 🌐-->
Link naar mijn website: https://wingsvn.github.io/all-human-accessible-website/uitleningen.html

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

Mijn pagina is in HTML gestructureerd uit een navbar en main met daarin div- en article elementen. De navigatiebar heb ik in HTML opgezet met list items binnen een unordered list.  De gegevens van elk boek, DVD en CD bevinden zich elk in een article element. Elk article van de desbetreffende categoriën zit weer in hun desbetreffende div element, om ze van elkaar te onderscheiden. En om per categorie de producten naast elkaar te zetten heb ik CSS flex gebruikt. Verder heb ik voor de uitbeeld vallende producten CSS overflow: scroll gebruikt om deze producten zichtbaar te krijgen. Om de website aan te passen naar verschillende schermgroottes heb ik mediaquery gebruikt.

## Bronnen
Google Lighthouse
https://www.a11yproject.com/checklist/
https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html
Colour Contrast Analyzer

## Licentie


This project is licensed under the terms of the [MIT license](./LICENSE).
