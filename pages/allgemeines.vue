<template>
    <div class="body">
        <div class="step-dark">
            <img class="image-umsetzung-header" src="../assets/header-bild-allgemeines.jpg"
                 alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline">Allgemeines</h1>
            <p class="summery-text-top">Mit statischen Webseiten-Generatoren kann man komplette Websites erstellen ohne
                ein Content Management System (CMS) zu benutzen. Mittlerweile gibt es über 400 verschiedene Tools auf
                dem Markt. Vor allem kleine Internetseiten wie Blogs, Unternehmensseiten oder private Homepages können
                auch schon mit ausschließlich statischen Inhalten überzeugen. Zudem ist die Umsetzung etwas einfacher,
                da man auch auf vorgefertigte Layouts zurückgreifen kann.
                Weitere Informationen findet ihr weiter unten.
            </p>
        </div>
        <div class="step-light">
            <img class="image-step-1" src="../assets/was-ist-ein-statischer-website-generator.jpg" alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline">Was ist ein statischer Webseiten-Generator?</h1>
            <p class="summery-text">
                Statische Webseiten-Generatoren, auch Static-Site-Generatoren genannt, sind fertige Codegerüste, auf
                deren Basis sich statische Webseiten erstellen lassen. Anders als bei einem CMS wird der HTML-Code lokal
                auf dem Rechner des Entwicklers erzeugt. Es werden also keine Datenbanken oder serverseitige
                Skriptsprachen
                benötigt, was statische Websites besonders sicher macht. Alle Komponenten, die gebraucht werden um den
                Code zu erzeugen, werden in einem gut strukturierten Verzeichnis gespeichert. Besonders wichtig dabei
                ist
                eine strikte Trennung zwischen Layout und Content. Durch diese Struktur ist es zum Beispiel möglich
                schnell
                Änderung am Design vorzunehmen, ohne dabei Einfluss auf die veröffentlichten Inhalte zu nehmen. <br>
                <br>
                Bedient und installiert werden die Generatoren über die Kommandozeile. Mithilfe einer vereinfachten
                Auszeichnungssprache – in der Regel Markdown – werden die eigentlichen Inhalte einer Webseite
                geschrieben.
                Um eine solche Seite zu veröffentlichen muss der automatisch generierte Webcode auf den gewünschten
                Webspace
                übertragen werden.
            </p>
        </div>
        <div class="step-dark-1">
            <img class="image-step-2" src="../assets/wann-sind-generatoren-sinnvoll-image.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline">Wann ist der Einsatz von statischen Webseiten Generatoren sinnvoll?</h1>
            <p class="summery-text-1">Auf jeden Fall bedenken sollte man, dass die Generatoren von Entwicklern für
                Entwickler sind, und man einiges an technischem Wissen benötigt, um sie zu benutzen. Außerdem sollte man
                sich vor der Wahl eines Generators überlegen, was für eine Seite man gestalten möchte und welche
                Funktionen sie haben soll, da nicht jeder Generator für jeden Zweck geeignet ist. </p>
        </div>
        <div class="step-light">
            <div class="overview">
                <table id="table-vor-nachteile">
                    <tr>
                        <th>Vorteile</th>
                        <th>Nachteile</th>
                    </tr>
                    <tr>
                        <td>
                            <strong> Geschwindigkeit:</strong> Statische Webseiten liegen bereits fertig auf einem Server und werden ohne
                            Umwege aufgerufen und ausgegeben, was sie um einiges schneller macht als dynamische Seiten.
                        </td>
                        <td>
                            <strong> Echtzeit-Inhalte </strong> nicht möglich: Mit einem statische Webseiten-Generator gibt es keine Möglichkeit
                            dynamische Inhalte zu erzeugen, also z. B. Inhalte, die sich an den Nutzer anpassen. Falls man
                            solche Inhalte doch einbinden möchte ist dies nur über Umwege möglich, z.B. mit clientseitiger
                            Skripten wie JavaScript. Das wiederum kann Sicherheitslücken mit sich bringen, zudem haben viele Nutzer
                            Skriptsprachen in ihrem Browser blockiert und bekommen die Inhalte trotzdem nicht angezeigt.
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <strong> Sicherheit: </strong> Statische Webseiten haben sehr wenig Angriffsfläche, da sie ohne Datenbankzugriffe,
                            Nutzerinteraktion oder -authentifizierung auskommen. Dadurch sind die Seiten sehr gut vor unerwünschten Zugriffen geschützt.
                        </td>
                        <td>
                            <strong> Schwierigkeiten mit User-Input: </strong> Auch Benutzereingaben können mit einem statischen Webseiten-Generator
                            nur schwer eingebunden werden. Es ist zwar mithilfe von JavaScript oder Drittanbieter-Services möglich,
                            aber erfordert einen großen zeitlichen und technischen Aufwand.

                        </td>
                    </tr>
                    <tr>
                        <td>
                            <strong> Einfache Instandhaltung der Server:</strong> Alles was zur Veröffentlichung der Seite benötigt wird ist
                            ein funktionsfähiger Webserver. Für den Live-Betrieb wird keine zusätzliche Software gebraucht,
                            regelmäßige Aktualisierungen und andere Wartungsarbeiten fallen somit weg.
                        </td>
                        <td>
                            <strong> Keine Benutzeroberfläche: </strong>Statische Webseiten-Generatoren haben kein User-Interface über das
                            Inhalte bearbeitet werden können. Das ist besonders für Nutzer mit wenig technischem Hintergrundwissen
                            ein Problem, da für den manuellen Upload der Daten ein gewisses Verständnis des Codes und der Struktur
                            der Website nötig ist. Daher nimmt der Einstieg sehr viel Zeit in Anspruch.
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <strong> Besseres Traffic-Management: </strong> Bei dynamische Seiten sind unerwartet viele Seitenaufrufe und
                            die damit verbundenen Datenbankabfragen oft ein Problem. Das Abrufen und Ausliefern von HTML-Seiten
                            beansprucht einen Server nur minimal, weshalb Traffic-Spitzen besser abgefangen werden.
                        </td>
                        <td>
                            <strong> Schlechtes Content Management: </strong> Der Content einer Seite muss in der Regel auch aus einem einzigen
                            Dokument kommen. Eine einzelne Seiten aus mehreren Content-Bausteinen zusammen zu bauen ist meistens
                            mehr oder weniger kompliziert, wenn nicht sogar ganz unmöglich.
                        </td>
                    </tr>
                </table>
            </div>
        </div>
        <div class="step-dark-2">
            <img class="image-step-3" src="../assets/fazit-image.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline">Fazit</h1>
            <p class="summery-text-3">Am besten geeignet sind statische Webseiten-Generatoren für Blogs. Die meisten
                Generatoren wurden für den Aufbau eines Blogs entwickelt, dementsprechend bieten sie dafür auch die meisten
                Möglichkeiten. Neben Blogs eignen sich statische Webseiten-Generatoren aber auch für Webseiten für
                kleine und mittlere Unternehmen, Dokumentationen und Hilfetexte. Deren Inhalte ändern sich nicht oft und
                sie profitieren von der Schnelligkeit und Sicherheit einer statischen Website.</p>
        </div>
    </div>
</template>


<script>

</script>


<style>
    .body {
        padding-top: 40px;
    }

    .step-dark {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 50px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .step-dark-1 {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 80px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .step-dark-2 {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 70px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .overview {
        padding-top: 20px;
        padding-right: 80px;
        padding-left: 60px;
    }

    #table-vor-nachteile {
        border-collapse: collapse;
        width: 100%;
    }

    #table-vor-nachteile .merkmal {
        background-color: rgba(29, 112, 124, 0.15);
    }

    #table-vor-nachteile td, #table-vor-nachteile th {
        border: 1px solid #ddd;
        padding: 8px;
    }

    #table-vor-nachteile tr:nth-child(even) {
        background-color: #f2f2f2
    }

    #table-vor-nachteile tr:hover {
        background-color: #ddd;
    }

    #table-vor-nachteile th {
        padding-top: 12px;
        padding-bottom: 12px;
        text-align: left;
        background-color: #1d707c;
        color: white;
    }

    .summery-text-1 {
             padding-bottom: 60px;
             padding-right: 80px;
             padding-top: 15px;
             text-align: justify;
         }

    .summery-text-3 {
        padding-bottom: 60px;
        padding-right: 80px;
        padding-top: 15px;
        text-align: justify;
    }

    .number-picture {
        width: 70px;
        height: 60px;
        float: left;
    }

    .step-light {
        padding-bottom: 60px;
        box-shadow: 0 8px 5px -6px grey;
        position: relative;
        z-index: 100;
    }

    .image-umsetzung-header {
        height: 220px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 30px;
        width: 700px;
        float: left;
    }

    .image-step-1 {
        height: 320px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 80px;
        padding-bottom: 30px;
        width: 700px;
        float: right;
    }

    .image-step-2 {
        height: 320px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 60px;
        width: 550px;
        float: left;
    }

    .image-step-3 {
        height: 320px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 50px;
        width: 550px;
        float: left;
    }

    .content-headline {
        padding-top: 40px;
        padding-left: 60px;
        font-size: 20pt;
        color: #1d707c;
    }

    .step-dark {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 40px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .summery-text-top {
        text-align: justify;
        padding-top: 15px;
        padding-right: 85px;
        padding-left: 60px;
    }

    .summery-text {
        text-align: justify;
        padding-top: 15px;
        padding-right: 85px;
        padding-left: 60px;
    }
</style>