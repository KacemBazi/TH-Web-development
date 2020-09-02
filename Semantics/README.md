Semantics

Kacem el Bazi

    9. Sinds de komst van HTML5 zijn er elementen die betekenissen hebben. Wat
    wordt er bedoeld met HTML semantics? Waarom is het gebruik van
    semantics belangrijk?
    
         Wat zijn semantische elementen?

            Semantische html is geen nieuwe html-versie. Het legt enkel de nadruk op de overeenkomst tussen de naam van het element en de inhoud ervan. Aan de inhoud van de elementen wordt een betekenisvolle naam gegeven.

            De naam van een semantisch element drukt duidelijk zijn betekenis uit, zowel voor de ontwikkelaar als voor de browser.

            Voorbeelden hiervan zijn:

            <article>
            <aside>
            <details>
            <figcaption>
            <figure>
            <footer>
            <header>
            <main>
            <mark>
            <nav>
            <section>
            <summary>
            <time>
            De naam van die elementen geven duidelijk aan wat de inhoud ervan is.

        
            Voorbeelden van niet-semantische elementen:

            <div>
            <span>

        Waarom semantische html?
            
            De voordelen van semantische html:

            snellere laadtijd: omdat de code eenvoudiger is doordat enkel html elementen worden gebruikt en dus minder attributen om de inhoud in te delen is er minder dataverkeer;
            betere toegankelijkheid: screenreaders en andere alternatieve browsers kunnen beter overweg met semantisch opgemaakte html-documenten omdat ze de 'betekenis' van de inhoud uit de tags kunnen afleiden;
            mobiel: responsive design is stukken gemakkelijker met semantische elementen;
            betere ranking: spiders kunnen semantische webpagina's beter en nauwkeuriger indexeren. Een spider ziet namelijk geen opmaak en is dan ook niet in staat daaruit het belang van woorden, zinnen of teksten te halen;
            de vormgeving in CSS is nauwkeuriger en flexibeler;
            HTML-code is eenvoudiger en overzichtelijk.


    
    10.Wat voor content zou je in de volgende elementen gebruiken?
    Geef in je antwoord voor elk element een toelichting.
    
        ● <header> 
                    Vertegenwoordigt inleidende inhoud, meestal een groep inleidende of navigatiehulpmiddelen. Het kan enkele kopelementen bevatten, maar ook een logo, een zoekformulier, een auteursnaam en andere elementen.


        ● <footer>   
                    Vertegenwoordigt een voettekst voor de dichtstbijzijnde sectie-inhoud of het hoofdelement voor secties . Een voettekst bevat doorgaans informatie over de auteur van de sectie, copyrightgegevens of links naar gerelateerde documenten.

                    Voorbeeld:  
                                <footer>
                                    <p>© 2018 Gandalf</p>
                                </footer>


        ● <main>    
                    Vertegenwoordigt de dominante inhoud <body>van een document. Het hoofdinhoudsgebied bestaat uit inhoud die direct gerelateerd is aan of voortbouwt op het centrale onderwerp van een document, of de centrale functionaliteit van een applicatie.

                    Voorbeeld: <header>Gecko facts</header>

                    <main role="main">
                        <p>Geckos are a group of usually small, usually nocturnal lizards. They are found on every continent except Australia.</p>
                    
                        <p>Many species of gecko have adhesive toe pads which enable them to climb walls and even windows.</p>
                    </main>

                    Een document mag niet meer dan één <main>element bevatten waarvoor het hiddenkenmerk niet is opgegeven.

        ● <nav>     
                Vertegenwoordigt een sectie van een pagina waarvan het doel is om navigatielinks te bieden,       hetzij binnen het huidige document, hetzij naar andere documenten. Veelvoorkomende voorbeelden van navigatiesecties zijn menu's, inhoudsopgaven en indexen.

                Voorbeeld:
                            <nav class="crumbs">
                                <ol>
                                    <li class="crumb"><a href="TechGrounds.nl">Techgrounds</a></li>
                                </ol>
                            </nav>
    
        ● <section> 
                    Definieert een sectie in een document.

                    Volgens de HTML-documentatie van W3C: "Een sectie is een thematische groepering van inhoud, meestal met een titel."

                    Een webpagina kan normaal gesproken worden opgesplitst in secties voor inleiding, inhoud en contactgegevens.

        ● <aside>   
                    Vertegenwoordigt een deel van een document waarvan de inhoud slechts 
                    indirect verband houdt met de hoofdinhoud van het document. 
                    Afscheidingen worden vaak gepresenteerd als zijbalken of call-out boxes.
        
        ● <article>
                    vertegenwoordigt een op zichzelf staande compositie in een document, pagina, toepassing of site, die bedoeld is om onafhankelijk verspreid of herbruikbaar te zijn (bijvoorbeeld in syndicatie). Voorbeelden zijn: een forumbericht, een tijdschrift- of krantenartikel of een blogbericht.

                    Een bepaald document kan meerdere artikelen bevatten; bijvoorbeeld, op een blog die de tekst van elk artikel een voor een laat zien terwijl de lezer scrolt, zou elk bericht in een <article>element staan, mogelijk met een of meer <section>s erin

                    Voorbeeld:  <article class="forecast">

                                    <h1>Weather forecast for Seattle</h1>
                                    <article class="day-forecast">
                                        <h2>03 March 2018</h2>
                                        <p>Rain.</p>
                                    </article>

                                    <article class="day-forecast">
                                        <h2>04 March 2018</h2>
                                        <p>Periods of rain.</p>
                                    </article>

                                    <article class="day-forecast">
                                        <h2>05 March 2018</h2>
                                        <p>Heavy rain.</p>
                                    </article>

                                </article>



    11. Onderzoek en leg uit waarom headers zowel belangrijk zijn voor zoekmachines als
        voor de gebruikers.

        Betreft het belang voor zoekmachines en gebruikers is het zo dat je informatie verwerkt in headers die jou pagina makelijk doet vinden op basis van overeenkomsten tussen je headers info en zoek opdrachten.

        Het <header>element vertegenwoordigt een container voor inleidende inhoud of een reeks navigatielinks.

        Een <header>element bevat doorgaans:

        een of meer kopelementen (<h1> - <h6>)
        logo of pictogram
        auteurschap informatie
        Opmerking: u kunt meerdere <header>elementen in één HTML-document hebben. Echter, <header>niet binnen een <footer>, <adres> worden geplaatst of een ander <header>element.



    12. Onderzoek hoe je een text-header aanmaakt en reproduceer het volgende resultaat:

        <header>
            <h1>Headings opdrachten</h1>
            <h1>Heading 1</h1>
            <h2>Heading 2</h2>
            <h3>Heading 3</h3>
            <h4>Heading 4</h4>
            <h5>Heading 5</h5>
            <h6>Heading 6</h6>
        </header>



    