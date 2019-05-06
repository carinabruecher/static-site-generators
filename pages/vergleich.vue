<template>
    <div class="body">
        <div class="header">
            <img class="vergleich-headerimage" src="../assets/header-bild-vergleich.jpg"
                 alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Vergleich</h1>
            <p class="summery-text-vergleich">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf
                sich warten. Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten. </p>
        </div>
        <div class="short-vergleich">
            <h2 class="subheadline">Kurzübersicht über die Static-Site Generatoren</h2>
            <p class="short-text">Welcher Generator kann eigentlich was? Wofür sind die unterschiedlichen Generatoren
                geeignet?
                Welchen sollte ich für mein Projekt verwenden? <br>
                Die Antwort dieser Fragen ist natürlich einerseits Geschmackssache. Als Entscheidungshilfe haben wir in
                dieser Tabelle
                die wichtigsten Unterschiede einiger static-site Generator zusammengefasst.
            </p>
            <div class="overview">
                <table id="table-overview">
                    <tr>
                        <th>  </th>
                        <th>Hugo</th>
                        <th>Jeklly</th>
                        <th>Nuxt.js</th>
                    </tr>
                    <tr>
                        <td class="merkmal">Vorkenntnisse</td>
                        <td>
                            - Consolenvorkenntnisse <br>
                            - Grundkenntnisse im Programmieren <br>
                        </td>
                        <td>
                            - Git-Kenntnisse <br>
                            - HTML + CSS <br>
                            - Ruby
                        </td>
                        <td>
                            - HTML + CSS <br>
                            - Consolenvorkenntnisse <br>
                            - Vue Gundkenntnisse <br>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Installation</td>
                        <td>
                            sehr einfach
                        </td>
                        <td>
                            schwierig
                        </td>
                        <td>
                            mittelschwer
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Installations Vorraussetzungen</td>
                        <td>
                            - Git <br>
                            - Texteditor oder Entwicklungsumgebung
                        </td>
                        <td>
                            - Ruby Entwickungsumgebung
                        </td>
                        <td>
                            - Git <br>
                            - Texteditor oder Entwickungsumgebung
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">allgemeiner Schwierigkeitsgrad</td>
                        <td>
                            leicht
                        </td>
                        <td>
                            schwer
                        </td>
                        <td>
                            mittel
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Kosten</td>
                        <td>
                            keine
                        </td>
                        <td>
                            keine
                        </td>
                        <td>
                            keine
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Harware kompatibilität</td>
                        <td>
                            Mac, Windows und Linux
                        </td>
                        <td>
                            Mac, Windows und Linux
                        </td>
                        <td>
                            Mac, Windows und Linux
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Anwendungsbereiche</td>
                        <td>
                            - größere Websites <br>
                            - Blogs
                        </td>
                        <td>
                            - einfache Websites <br>
                            - Blogs
                        </td>
                        <td>
                            - universelle Anwendungen
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Zielgruppe</td>
                        <td>
                            - Webdesigner <br>
                            - Webentwickler <br>
                            - Programmiereinsteiger
                        </td>
                        <td>
                            - Blogger <br>
                            - Programmiereinsteiger
                        </td>
                        <td>
                            - Programmierer
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Ladezeiten</td>
                        <td>
                            schnell
                        </td>
                        <td>
                            langsam
                        </td>
                        <td>
                            schnell
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Wartung</td>
                        <td>
                            schwer
                        </td>
                        <td>
                            mittel
                        </td>
                        <td>
                            schwer
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Installation von Themes</td>
                        <td>
                            Ja
                        </td>
                        <td>
                            Ja
                        </td>
                        <td>
                            Nein
                        </td>
                    </tr>
                </table>
            </div>
        </div>
        <div class="grid-overview">
            <nuxt-link class="left-1" to="vergleich-generatoren/hugo">
                <img class="teaser-generatoren" src="../assets/teaser-hugo.jpg"
                     alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
            <nuxt-link class="rechts" to="/vergleich-generatoren/jeklly">
                <img class="teaser-generatoren" src="../assets/teaser-jekyll.jpg"
                     alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
            <br>
            <nuxt-link class="left-2" to="/vergleich-generatoren/nuxtjs">
                <img class="teaser-generatoren" src="../assets/teaser-nuxt.jpg"
                     alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
        </div>
    </div>
</template>

<style>

    .overview {
        padding-top: 20px;
        padding-right: 80px;
        padding-left: 60px;
    }

    #table-overview {
        border-collapse: collapse;
        width: 100%;
    }

    #table-overview .merkmal {
        background-color: rgba(29, 112, 124, 0.15);
    }

    #table-overview td, #table-overview th {
        border: 1px solid #ddd;
        padding: 8px;
    }

    #table-overview tr:nth-child(even) {
        background-color: #f2f2f2
    }

    #table-overview tr:hover {
        background-color: #ddd;
    }

    #table-overview th {
        padding-top: 12px;
        padding-bottom: 12px;
        text-align: left;
        background-color: #1d707c;
        color: white;
    }

    .summery-text-vergleich {
        padding-bottom: 30px;
        padding-right: 80px;
        padding-top: 15px;
        text-align: justify;
    }

    .teaser-generatoren {
        width: 600px;
        height: 400px;
        padding-top: 20px;
    }

    .left-1 {
        padding-left: 60px;
    }

    .left-2 {
        padding-left: 60px;

    }

    .rechts {
        padding-left: 20px;
    }

    .header {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .grid-overview {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 40px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .subheadline {
        padding-top: 40px;
        padding-left: 60px;
        color: #1d707c;
    }

    .vergleich-tabelle {
        padding-top: 20px;
        padding-left: 60px;
        width: 1200px;
    }

    .short-text {
        padding-left: 60px;
        padding-top: 10px;
    }

    .short-vergleich {
        padding-bottom: 40px;
    }

    .vergleich-headerimage {
        height: 230px;
        padding-top: 30px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 30px;
        width: 650px;
        float: left;
    }
</style>