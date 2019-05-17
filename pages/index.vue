<template>
    <div class="body">

        <div class="content-top-slider">
            <img class="slider-image" src="../assets/top-slider.jpg" alt="slider"/>
        </div>

        <div class="content-allgemeines">
            <img class="image-allgemeines" src="../assets/teaser-bild-allgemeines.jpg"
                 alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline-allgemeines">Allgemeines</h1>
            <p class="summery-text">Mit statischen Webseiten-Generatoren kann man komplette Websites erstellen ohne
                ein Content Management System (CMS) zu benutzen. Mittlerweile gibt es über 400 verschiedene Tools auf
                dem Markt. Vor allem kleine Internetseiten wie Blogs, Unternehmensseiten oder private Homepages können
                auch schon mit ausschließlich statischen Inhalten überzeugen. Zudem ist die Umsetzung etwas einfacher,
                da man auch auf vorgefertigte Layouts zurückgreifen kann.
                Weitere Informationen findet ihr weiter unten.</p>
            <nuxt-link class="button-allgemeines" to="/allgemeines">Read more</nuxt-link>
        </div>

        <div class="content-function">
            <img class="image-functions" src="../assets/teaser-bild-funktion.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-function">Funktion</h1>
            <p class="summery-text">Statische Webseiten-Generatoren sind Codegerüste mit deren Hilfe statische
                Webseiten
                erstellt werden können. Der HTML-Code wird lokal auf dem Rechner erzeugt, bei der Nutzung sind also
                keine
                Datenbanken oder serverseitige Sprachen, wie PHP, nötig. Die Generatoren müssen über die Kommandozeile
                sowohl installiert als auch bedient werden, da die große Mehrheit der Generatoren keine
                Benutzeroberfläche hat.
            </p>
            <nuxt-link class="button-function" to="/funktion">Read more</nuxt-link>
        </div>

        <div class="content-vergleich">
            <img class="image-vergleich" src="../assets/teaser-bild-vergleich.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Vergleich</h1>
            <p class="summery-text">Welcher Generator ist der richtige für mich?
                Um Euch all diese Dinge zu erleichtern, haben wir einen Vergleich von den für uns geeignetsten Generatoren
                auf dem Markt gemacht. Wir haben die Generatoren HUGO, Nuxt.js und Jekyll miteinander verglichen.
                Dabei gehen wir auf alle wichtigen Dinge ein von der Funktionsweise, über die Vor und Nachteile.
                Außerdem haben wir eine Schritt für Schritt Anleitung für jeden Generator erstellt um Euch den Einstieg zu
                erleichtern. </p>
            <nuxt-link class="button-vergleich" to="/vergleich">Read more</nuxt-link>
        </div>

        <div class="footer">
            <div class="table">
                <table id="table-footer">
                    <tr>
                        <td>
                            Maximillian Acker <br>
                            Carina Brücher <br>
                            Christina Bünnagel <br>
                            Marleen Lorenz
                        </td>
                        <td>
                            Wenn dir diese Seite geholfen hat, <br>
                            würden wir uns über ein kleines Dankeschön freuen :-) <br>
                            Auch über Verbesserungsvorschläge freuen wir uns sehr. <br>
                        </td>
                        <td>
                            <nuxt-link class="footer-link" to="/impressum">Impressum</nuxt-link>
                            <br>
                            <nuxt-link class="footer-link" to="/kontakt">Kontakt</nuxt-link>
                        </td>
                    </tr>
                </table>
            </div>
        </div>
    </div>
</template>


<script>
    export default {}
</script>


<style>

    .table {
        padding-top: 20px;
        padding-left: 60px;
        padding-bottom: 40px;
        width: 100%;
    }

    #table-footer {
        width: 100%;
    }

    .body {
        padding-top: 50px;
    }

    .button-allgemeines {
        background-color: #1d707c;
        border: none;
        color: white;
        padding: 10px 10px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin-top: 30px;
        cursor: pointer;
    }

    .button-allgemeines:hover {
        background-color: #22a8b4;
        box-shadow: 0px 1px 3px 0px grey;
    }

    .button-function {
        background-color: #1d707c;
        border: none;
        color: white;
        padding: 10px 10px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin-top: 20px;
        margin-left: 60px;
        cursor: pointer;
    }

    .button-function:hover {
        background-color: #22a8b4;
        box-shadow: 0px 1px 3px 0px grey;
    }

    .button-vergleich {
        background-color: #1d707c;
        border: none;
        color: white;
        padding: 10px 10px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin-top: 20px;
        cursor: pointer;
    }

    .button-vergleich:hover {
        background-color: #22a8b4;
        box-shadow: 0px 1px 3px 0px grey;
    }

    .button-umsetzung {
        background-color: #1d707c;
        border: none;
        color: white;
        padding: 10px 10px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin-top: 20px;
        margin-left: 60px;
        cursor: pointer;
    }

    .button-umsetzung:hover {
        background-color: #22a8b4;
        box-shadow: 0px 1px 3px 0px grey;
    }

    .content-top-slider {
        position: relative;
        z-index: 0;
        padding-bottom: 3px;
        box-shadow: inset 0px 0px 5px 2px grey;
        background-color: #e3e3e3;
    }

    .content-allgemeines {
        padding-bottom: 40px;
        box-shadow: 0 8px 5px -6px grey;
        position: relative;
        z-index: 100;
    }

    .content-function {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 40px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .content-vergleich {
        padding-bottom: 40px;
        position: relative;
        z-index: 100;
    }

    .content-umsetzung {
        background-color: #e3e3e3;
        position: relative;
        z-index: 100;
        padding-bottom: 40px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .content-headline-function {
        padding-top: 40px;
        padding-left: 60px;
        font-size: 20pt;
        color: #1d707c;
    }

    .content-headline-allgemeines {
        padding-top: 45px;
        font-size: 20pt;
        color: #1d707c;
    }

    .content-headline-vergleich {
        padding-top: 40px;
        font-size: 20pt;
        color: #1d707c;
    }

    .content-headline-umsetzung {
        padding-top: 40px;
        padding-left: 60px;
        font-size: 20pt;
        color: #1d707c;
    }

    .image-allgemeines {
        height: 320px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 50px;
        width: 550px;
        float: left;
    }

    .image-vergleich {
        height: 320px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 30px;
        width: 700px;
        float: left;
    }

    .image-functions {
        height: 320px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 80px;
        padding-bottom: 30px;
        width: 700px;
        float: right;
    }

    .image-umsetzung {
        height: 320px;
        padding-top: 40px;
        padding-left: 55px;
        padding-right: 80px;
        padding-bottom: 50px;
        width: 700px;
        float: right;
    }

    .slider {
        box-shadow: inset 0px 0px 3px 8px grey;
        padding-bottom: 20px;
        position: relative;
        z-index: 40;
    }

    .slider-image {
        position: relative;
        z-index: 0;
    }

    .summery-text {
        text-align: justify;
        padding-top: 15px;
        padding-right: 85px;
        padding-left: 60px;
    }

    .thank-you-text {
        padding-top: 20px;
        padding-left: 60px;
        float: left;
    }

    .footer-link {
        text-decoration: none;
        color: black;
    }

    .text-who {
        float: right;
        padding-top: 20px;
    }

</style>