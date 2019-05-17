<template>
    <div class="body">
        <div class="header-hugo">
            <img class="logo-generator-hugo" src="../../assets/header-image-hugo.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Hugo</h1>
            <p class="summery-text">Mit Hugo haben wir das schnellste Framework das derzeit auf dem Markt zu finden ist.
                Es zeigt hohe Qualitäten in punkto Geschwindigkeit und Flexibilität. Außerdem ist Hugo ein kostenloser
                Open Source Generator für statische Webseiten. Hugo kann mit vorgefertigten Vorlagen arbeiten und bietet
                damit eine vielzahl an Möglichkeiten. Über 300 sehr einfach installierbare Themes hat Hugo zur Verfügung,
                diese ermöglichen es Webseiten einfach und schnell zu erstellen. Der Generator basiert auf der Sprache GO.
            </p>
        </div>
        <div class="step-light">
            <img class="image-step-1" src="../../assets/merkmal-image-hugo.jpg" alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline">Merkmale</h1>
            <p class="summery-text">
                -  extrem schnelle Bauzeiten <br>
                -  das System ist plattformübergreifend und kann ganz einfach auf Mac OS und Windows Systemen installiert werden <br>
                -  das Hosten der Site ist überall möglich <br>
                -  anpassbare URLs und Unterstützung sprechender URLs <br>
                -  einfache Organisation für Projekte und einfach Wartung <br>
                -  Unterstützung für konfigurierbare Taxonomien  <br>
                -  SEO fähig <br>
                -  verschiedene Ausgaben möglich (JSON oder AMP) <br>
                -  Genau zu diesem Zwecke erschaffen, immer im Schatten meines großen Bruders <br>
                -  geeignet für Blogs, Unternehmenswebseiten oder einer Landing Page <br>
            </p>
        </div>
        <div class="how-to">
            <h1 class="headline-step-by-step">Step by Step</h1>
            <p class="summery-text">
                <i>Installation Hugo</i>
                <br>
                <strong>Schritt 1: </strong> ~ brew install hugo <br>
                <br>
                <strong>Schritt 2: </strong>  ~ hugo version <br>
                <br>
                <i>Neue Seite erstellen</i>
                <br>
                <strong>Schritt 3: </strong> ~ hugo new site SEITENNAMEN<br>
                <br>
                <i>Neues Theme hinzufügen</i>
                <br>
                <strong>Schritt 4: </strong> ~ cd SEITENNAME <br>
                <br>
                <strong>Schritt 5: </strong> ~ git init<br>
                <br>
                <strong>Schritt 6: </strong> ~ git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke <br>
                (git submodule add pfad-zum-gewünschten-theme theme-pfad-im-projekt)
                <br>
                <br>
                <strong>Schritt 7: </strong> ~ echo 'theme = "ananke"' >>config.taml <br>
                <br>
                <i>Inhalt hinzufügen</i>
                <br>
                <strong>Schritt 8: </strong> ~ hugo new posts/my-first-post.md <br>
                (hugo new datei-die-angelegt-werden-soll)
                <br>
                <br>
                <i>Hugo Server starten</i>
                <br>
                <strong>Schritt 9: </strong> ~ hugo server -D <br>
                <br>
                <br>
                <strong>Seitenvorschau anschauen</strong> <br>
                Um eine Vorschau der Seite im Browser zu sehen muss man auf die URL <i>localhost:1313</i> gehen
                <br>
                <br>
                <strong>Inhalte einfügen oder verändern</strong> <br>
                Um Inhalte zu ändern oder einzufügen kann man das gesamte Projekt also in diesem Fall den Ordner quickstart
                in einer Entwicklungsumgebung wie PHP Storm öffnen oder man öffnet die Dateien in einem Texteditor.
                <br>
                <br>
                <strong>Generieren der Html-Dokumente</strong> <br>
                ~ hugo <br>
                mit dem command hugo werden die Html-Dokumente generiert, nach dem ausführen erscheint ein neuer Ordner
                "public" in diesem befinden sich die generierten Dokumente. Um die Website nun zu hosten muss nur dieser Ordner
                auf den Server des Hostinganbieters geladen werden. <br>
                <i>Wichtig: bevor man den Command "hugo" erneut ausführt sollte man den Ordner public löschen</i> <br>
            </p>
        </div>
        <div class="step-light-table">
                <table id="pros-cons-hugo">
                    <tr>
                        <th>Vorteile</th>
                        <th>Nachteile</th>
                    </tr>
                    <tr>
                        <td>schnellstes Werkzeug seiner Art</td>
                        <td>komplexe Wartung</td>
                    </tr>
                    <tr>
                        <td>einfache Markdown Syntax</td>
                        <td>benötigt Vorkenntnisse mit der Arbeit an der Konsole und solide Grundkenntnisse beim Programmieren</td>
                    </tr>
                    <tr>
                        <td>umfassende Unterstützung</td>
                        <td>Installation von Git und andere Entwicklungsebenen für GO nötig</td>
                    </tr>
                    <tr>
                        <td>Ausgabe in verschiedenen Formaten</td>
                        <td>manuelle Codierung setzt Verständnis voraus</td>
                    </tr>
                    <tr>
                        <td>plattformübergreifend</td>
                        <td>komplex eigene Themes zu erstellen</td>
                    </tr>
                    <tr>
                        <td>einfach Menüerstellung</td>
                        <td></td>
                    </tr>
                    <tr>
                        <td>viele Themes</td>
                        <td></td>
                    </tr>
                    <tr>
                        <td>manuelle Codierung</td>
                        <td></td>
                    </tr>
                    <tr>
                        <td>keine Abhängigkeiten von Datenbanken</td>
                        <td></td>
                    </tr>

                </table>
        </div>
        <div class="grid-overview">
            <nuxt-link class="left-1" to="jeklly">
                <img class="teaser-generatoren" src="../../assets/teaser-jekyll.jpg" alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
            <nuxt-link class="rechts" to="nuxtjs">
                <img class="teaser-generatoren" src="../../assets/teaser-nuxt.jpg" alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
        </div>
    </div>
</template>


<script>

</script>


<style>

    .headline-step-by-step {
        padding-top: 40px;
        padding-left: 60px;
        font-size: 20pt;
        color: #1d707c;
    }

    .content-headline-

    table {
        border-collapse: collapse;
        width: 100%;
    }

    #pros-cons-hugo td, #pros-cons-hugo th {
        border: 1px solid #ddd;
        padding: 8px;
    }

    #pros-cons-hugo tr:nth-child(even) {
        background-color: #f2f2f2
    }

    #pros-cons-hugo tr:hover {
        background-color: #ddd;
    }

    #pros-cons-hugo th {
        padding-top: 12px;
        padding-bottom: 12px;
        text-align: left;
        background-color: #1d707c;
        color: white;
    }

    .step-light-table {
        padding-bottom: 40px;
        padding-top: 20px;
        padding-left: 60px;
        padding-right: 75px;
        box-shadow: 0 8px 5px -6px grey;
        position: relative;
        z-index: 100;
    }

    .header-hugo {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 40px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .how-to {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 130px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .logo-generator-hugo {
        height: 230px;
        padding-top: 30px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 30px;
        width: 650px;
        float: left;
    }

    .console-picture {
        height: 600px;
        padding-top: 30px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 30px;
        width: 400px;
        float: left;
    }
</style>