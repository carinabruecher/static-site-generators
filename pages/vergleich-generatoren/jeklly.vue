<template>
    <div class="body">
        <div class="header-jeklly">
            <img class="logo-generator-hugo" src="../../assets/header-image-jekyll.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Jeklly</h1>
            <p class="summery-text">Jekyll wurde von GitHub-Gründer Tom Preston-Werner ins Leben gerufen und ist Grund für
                die steigende Beliebtheit der statischen Website Generatoren. Jekyll verfügt über eine Integration mit Git.
                Ruby ist die Sprache die für den Generator verwendet wird. Jekyll kann in allen Bereichen der Webentwicklung
                verwendet werden, da es sowohl für Firmenseiten, aber auch anderen alle Anforderungen gewachsen ist.
                Überzeugt die User durch eine stabile Laufleistung, verschiedene Möglichkeiten zur generation von Webseiten
                stehen als Vorlage zur Verfügung. </p>
        </div>
        <div class="step-light">
            <img class="image-step-1" src="../../assets/merkmal-image-jekyll.jpg" alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline">Merkmale</h1>
            <p class="summery-text">
                -  alle Inhalte werden in Textdateien gespeichert <br>
                -  sehr gut für Blogs <br>
                -  Inhalte werden im Stammverzeichnis als Markdown oder HTML gespeichert  <br>
                -  Dateien können mit Front-Mark-Feldern versehen werden <br>
                -  schnelle Performance für Suchmaschinen Optimierung <br>
                -  keine weiteren Datenbanken notwendig <br>
                -  unkomplizierte Umzug von Webseiten <br>
                -  Plug Ins auf Git verfügbar <br>
                -  keine Sicherheitslücken <br>
                -  kaum Wartungsarbeiten <br>
            </p>
        </div>
        <div class="how-to">
            <h1 class="headline-step-by-step">Step by Step</h1>
            <p class="summery-text">
                <i>Installation Ruby Umgebung</i>
                <br>
                <strong>Schritt 1: </strong> ~ brew install ruby <br>
                <br>
                <i>Prüfen ob es funktioniert hat</i>
                <br>
                <strong>Schritt 2: </strong>  ~ which ruby <br>
                <br>
                <strong>Schritt 3: </strong> ~ ruby -v <br>
                <br>
                <i>Installation Jekyll</i>
                <br>
                <strong>Schritt 4: </strong> ~ gem install --user-install bundler jekyll <br>
                <br>
                <strong>Schritt 5: </strong> ~ ruby -v<br>
                <br>
                <strong>Schritt 6: </strong> ~ export PATH=$Home/.gem/ruby/X.X.0/bin:$PATH <br>
                (die beiden X werden durch die ersten beiden Zahlen der Ruby Version ersetzt)
                <br>
                <i>Neue Jekyll Seite erstellen</i>
                <br>
                <strong>Schritt 7: </strong> ~ jekyll new beispiel-seite <br>
                (beispiel-seite durch den Namen der Seite ersetzten)
                <br>
                <i>Inhalt hinzufügen</i>
                <br>
                <strong>Schritt 8: </strong> ~ hugo new posts/my-first-post.md <br>
                (hugo new datei-die-angelegt-werden-soll)
                <br>
                <br>
                <i>Localen Server starten um die Site im Browser zu sehen</i>
                <br>
                <strong>Schritt 9: </strong> ~ cd beispiel-seite <br>
                (beispielseite wieder durch den Seitennamen ersetzten)
                <br>
                <br>
                <strong>Schritt 10: </strong> ~ bundle exec jekyll serve<br>
                <br>
                <br>
                <strong>Vorschau der Site im Browser sehen</strong> <br>
                Um die Vorschau der Site im Browser zu sehen muss man zu der URL "localhost:4000" gehen
                <br>
                <br>
                <strong>Generieren der Html-Dokumente</strong> <br>
                ~ Jekyll build <br>
            </p>
        </div>
        <div class="step-light-table">
            <table id="pros-cons-hugo">
                <tr>
                    <th>Vorteile</th>
                    <th>Nachteile</th>
                </tr>
                <tr>
                    <td>viele kostenlose Themes</td>
                    <td>Basiert auf Ruby (erfordert Ruby-Umgebung auf Rechner)</td>
                </tr>
                <tr>
                    <td>Designs können einfach installiert werden</td>
                    <td>langsame Buildzeiten</td>
                </tr>
                <tr>
                    <td>einfache und flexible Template-Engine</td>
                    <td>fehlende integrierte Funktion</td>
                </tr>
                <tr>
                    <td>reichhaltige Themenbibliothek</td>
                    <td>fehlende Erstanbieter - Funktionen für bessere Integration und Unterstützung </td>
                </tr>
                <tr>
                    <td>Tool und Formatunabhänig</td>
                    <td>komplizierte Installation</td>
                </tr>
                <tr>
                    <td>GitHub Pages Integration</td>
                    <td>nur Befehlszeile möglich</td>
                </tr>
                <tr>
                    <td>kaum Serverlast</td>
                    <td>viele Programmierkenntnisse notwendig (Html, CSS, Javascript, Ruby)</td>
                </tr>
                <tr>
                    <td>einfache Entwicklung und Pflege</td>
                    <td>keine Echtzeit Plugins</td>
                </tr>
            </table>
        </div>
        <div class="grid-overview">
            <nuxt-link class="left-1" to="hugo">
                <img class="teaser-generatoren" src="../../assets/teaser-hugo.jpg" alt="Funktionen statische Website Generatoren"/>
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

    .header-jeklly {
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