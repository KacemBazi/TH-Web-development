Paragrafen

Kacem el Bazi


13. Onderzoek wat een paragraaf tag is en hoe hij gebruikt wordt.
    Geef hier een voorbeeld bij.

    Het HTML- <p> element vertegenwoordigt een alinea. Alinea's worden in visuele media meestal weergegeven als tekstblokken die van aangrenzende blokken zijn gescheiden door lege regels en / of eerste regelinspringing, maar HTML-alinea's kunnen elke structurele groepering van gerelateerde inhoud zijn, zoals afbeeldingen of formuliervelden.

    Alinea's zijn elementen op blokniveau en worden met name automatisch gesloten als een ander element op blokniveau wordt geparseerd vóór de afsluitende </p>tag. Zie "Weglaten van tags" hieronder

    Voorbeeld: 
                <p> Wij leiden deelnemers uit de wijk op tot webontwikkelaar, met technische kennis van oa
                GIT, HTML, CSS, Javascript, Frameworks, NodeJS, Angular, React, REST API's en hands-on professionele projectervaring </p>

                <p> De TechGrounds incubator is de plek voor toekomstige ondernemers uit de wijk om begeleiding te krijgen bij het opzetten van een startup!</p>



14. Onderzoek en leg het verschil tussen het stoppen van alle tekst in één
    paragraaf tag, en het opsplitsen van de tekst in meerdere tags uit.

        Als je alle text in één P-tag voert dan heb je maar één alinea, en als je meerdere P-tags gebruikt dan splits je de tekst in meerdere alinea's op blokniveau.



    


15. Reproduceer het volgende resultaat door gebruik te maken van text-headers
    en de paragraaf tags.

        <header>
            <h1>Mijn eerste website</h1>
                <h2>Mijn eerste sub-kop</h2>
                    <br>
                    <p>Mensen uit kwetsbare wijken binnen een paar maanden aan een baan als programmeur helpen, zonder vooropleiding. Dat is het idee achter TechGrounds, een gratis tech-opleidingsprogramma. Vandaag openden de deuren van de eerste van een reeks vestigingen, in de Amsterdamse wijk Osdorp.</p>
                    <br>
                <h2>Mijn tweede sub-kop</h2>
                    <p>Elk jaar worden er zo'n 150 mensen geselecteerd om mee te doen, ongeacht hun achtergrond en opleiding. Twee maanden geleden zijn er al wat mensen begonnen. 
                    <br>
                    "Ik heb redelijk wat uitdagingen gehad in het leven. Als je dan nergens meer terecht kan, kan dat heel frustrerend zijn. Dat gevoel ervaar ik hier dus niet", vertelt Rinaldo Wouterson een van de deelnemers die meedraait in het project.</p>
        </header>




    16. Voeg een Horizontal rule toe en reproduceer het volgende resultaat.

        <header>
            <h1>Mijn eerste website</h1>
                <h2>Mijn eerste sub-kop</h2>
                    <br>
                    <p>Mensen uit kwetsbare wijken binnen een paar maanden aan een baan als programmeur helpen, zonder vooropleiding. Dat is het idee achter TechGrounds, een gratis tech-opleidingsprogramma. Vandaag openden de deuren van de eerste van een reeks vestigingen, in de Amsterdamse wijk Osdorp.</p>
                    <br>
                <h2>Mijn tweede sub-kop</h2>
                    <p>Elk jaar worden er zo'n 150 mensen geselecteerd om mee te doen, ongeacht hun achtergrond en opleiding. Twee maanden geleden zijn er al wat mensen begonnen. 
                    <br>
                    "Ik heb redelijk wat uitdagingen gehad in het leven. Als je dan nergens meer terecht kan, kan dat heel frustrerend zijn. Dat gevoel ervaar ik hier dus niet", vertelt Rinaldo Wouterson een van de deelnemers die meedraait in het project.</p>
                <hr>
                <h3>Footer</3>
                <p>Deze website is gebouwt door <a href="https://www.techgrounds.nl/">TechGrounds</a> student.</p>
        </header>



    17. Voeg een link tag toe en reproduceer het volgende resultaat in de footer.

            Voorbeeld: <p>Deze website is gebouwt door <a href="https://www.techgrounds.nl/">TechGrounds</a> student.</p>



    18. Onderzoek welke 4 attributen een link tag kan hebben, 
        leg uit wat deze doen en voeg deze als voorbeeld toe op je  website.

        <link href=””> 
        Beschrijft de relatie tussen het bronbestand en een extern bestand, zoals een script.

        <link media=””>
        Vertelt de browser voor welk type apparaat een bron is ontworpen.

        <link title=””>
        Wijst een naam toe aan verschillende gekoppelde bronnen, zodat gebruikers ertussen kunnen kiezen.

        <link type=””>
        Beschrijft het mediatype van de gekoppelde bron (MIME-type).

        


