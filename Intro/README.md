Intro


Kacem el Bazi

    
    
    1.Wat is het verschil tussen het internet en het world wide web?

        WorldWideWeb (WWW) is een site op Internet. Internet is een netwerk van miljoenen WWW's. 
        Eigenlijk is een WEBsite een web vol met informatie, en het Internet een web vol met websites.

        Anders gezegd:
        Het internet is de som van alle computers, alle netwerken, alle hardware, alle gegevens.
        Het World Wide Web is dat, wat voor de meeste gebruikers het internet “tot leven wekt”.



    2.Wat is het verschil tussen HTML, CSS en JavaScript? 
    
        Javascript is een programmeertaal, terwijl CSS een stijlbladtaal is. 
        CSS zorgt ervoor dat een webpagina er goed uitziet door het uiterlijk te wijzigen. 
        Het is echter allemaal statisch. Wat als u wilt dat de verschijning dynamisch en interactief is. 
        Javascript kan HTML-objecten en CSS-instellingen toevoegen / verwijderen / wijzigen zonder een pagina opnieuw
        te hoeven laden!

        Ik kan een afbeelding toevoegen aan een webpagina met behulp van de img HTML-tag. Vervolgens 
        kan ik CSS gebruiken om het een frame-look te geven met een schaduweffect en misschien het 
        formaat te wijzigen om het er groter uit te laten zien. Met Javascript kunt u de afbeeldingen animeren 
        als een carrousel-fotogalerij, inzoomen wanneer u over een deel van de afbeelding zweeft. 
        Javascript verandert de CSS, geen alternatief ervoor.



    3.Wat is een HTML tag en een HTML element? 
     
        Een tag is een opdracht die door een browser kan worden geïnterpreteerd. 
        HTML gebruikt tags om bijvoorbeeld de positie en weergave van elementen op een pagina aan te geven.
        Het HTML- element is alles van de start-tag tot de eindtag.


            Hoe open je een HTML tag en hoe sluit je een HTML tag. 
            
                <begintag> een begin tag doe je binnen twee haakjes en bij een eindtag voeg je na de eerste haakje 
                een schuin streep </eindtag>



    4.HTML gebruikt basis tags om structuur op te bouwen. De <html>, <head> en <body>. Geef voor elke element aan waarvoor het dient. 
    
        <html>: geeft aan dat het om een HTML5 bestand gaat
    
        <head>: De head wordt gedefinieerd met het HEAD element en bevat informatie, 
                die betrekking heeft op het document, maar niet in het documentvenster wordt weergegeven.

                bevat metadata en (links naar) CSS en scripts die nodig zijn voor de webpagina

        <body>: bevat de inhoud van de pagina



    5.Op HTML elementen kun je attributen gebruiken. Wat zijn HTML attributen ? Geef minimaal 5 attributen en maak voorbeelden waar je de attributen in toepast. 

        In sommige elementen kan je meer informatie toevoegen. Deze aanvullende informatie wordt een attribuut genoemd.
            
        Attributen worden altijd geschreven in de start-tag en worden gevolgd door een gelijk teken. Het attribuut gegevens komen tussen aanhalingstekens te staan. Zie het onderstaande voorbeeld.

        Voorbeelden: 

        <h2 style="background-color: #ff0000;">Mijn eerste HTML pagina.</h2>
            Dit is het attribut (style="background-color: #ff0000;")

        <a href="http://techgrounds.nl" >Dit is een link</a>
            Dit is het attribut (href="http://techgrounds.nl")

        <P ALIGN="right">Deze paragraaf wordt rechts uitgelijnd.</P>
            Dit is het attribut (ALIGN="right")

        <img src="plaatje.jpg" width=254 height=190 border=0 hspace=5 vspace=4>
            Dit is het attribut (src="plaatje.jpg")

        <div id="container">Some content</div>
            Dit is het attribut (id="container")



    6.Waarom is een goede HTML Structuur belangrijk? Is deze code een goede structuur? Leg uit. 

        Het is overzichtelijker en voorkomt tijdverlies bij een foutmelding of een toekomstige aanpassing door de develper zelf of een andere programeur



    7.Wat is het verschil tussen inline en block elementen? 

        Inline:
            Standaard zijn <a> elementen inline. Dat wil zeggen dat ze bij manier van spreken tussen de rest van de regel gezet worden.

            Als je de volgende HTML invoert:

            <a href="#gedicht1">De hand van de dichter</a>
            <a href="#gedicht2">Voor het inslapen</a>
            <a href="#gedicht3">De liefde slaapt in haar hart</a>

        Block:
            Standaard zijn <li> elementen block elementen. Dat wil zeggen dat elke item uit de lijst op een nieuwe regel komt te staan. Of dat elk item in de lijst de gehele breedte van het browservenster inneemt.

            Als je de volgende HTML invoert:

            <ul>
                <li>De hand van de dichter</li>
                <li>Voor het inslapen</li>
                <li>De liefde slaapt in haar hart</li>
            </ul>


    8.Wat betekent nesting? Codeer een voorbeeld met nesting erin.

        Door HTML-tags correct te nesten, worden HTML-fouten voorkomen.

        Als u de HTML- opmaak voor een webpagina vandaag bekijkt , ziet u HTML-elementen die zich in andere HTML-elementen bevinden. Deze elementen die zich "binnen" andere elementen bevinden, staan ​​bekend als geneste elementen en zijn essentieel voor het bouwen van een webpagina.

        Voorbeeld:
            <p> Welkom bij <strong> Techgrounds </strong> Amsterdam. </p>

            Techgrounds is gennest in <strong> tag
