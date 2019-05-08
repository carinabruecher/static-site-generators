<template>
    <div class="body">
        <div class="header-jeklly">
            <img class="logo-generator-hugo" src="../../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Jeklly</h1>
            <p class="summery-text">Jekyll wurde von GitHub-Gründer Tom Preston-Werner ins Leben gerufen und ist Grund für
                die steigende Beliebtheit der statischen Website Generatoren. Jekyll verfügt über eine Integration mit Git.
                Ruby ist die Sprache die für den Generator verwendet wird. Jekyll kann in allen Bereichen der Webentwicklung
                verwendet werden, da es sowohl für Firmenseiten, aber auch anderen alle Anforderungen gewachsen ist.
                Überzeugt die User durch eine stabile Laufleistung, verschiedene Möglichkeiten zur generation von Webseiten
                stehen als Vorlage zur Verfügung. </p>
        </div>
        <div class="step-light">
            <img class="image-step-1" src="../../assets/Slider.jpg" alt="allgemeines zu statische Website Generatoren"/>
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
            <img class="console-picture" src="../../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Step by Step</h1>
            <p class="summery-text">
                <strong>Schritt 1: </strong> Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. <br>
                <br>
                <strong>Schritt 2: </strong>  Damit das Layout nun nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. <br>
                <br>
                <strong>Schritt 3: </strong>  Genau zu diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«,
                freue ich mich jedes Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. <br>
                <br>
                <strong>Schritt 4: </strong> Und weil Sie nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten,
                möchte ich diese Gelegenheit nutzen, Ihnen nicht nur als Lückenfüller zu dienen, sondern auf etwas hinzuweisen,
                das es ebenso verdient wahrgenommen zu werden: Webstandards nämlich. <br>
                <br>
                <strong>Schritt 5: </strong> Sehen Sie, Webstandards sind das Regelwerk, auf dem Webseiten aufbauen.
                So gibt es Regeln für HTML, CSS, JavaScript oder auch XML;<br>
                <br>
                <strong>Schritt 6: </strong> Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. <br>
                <br>
                <strong>Schritt 7: </strong>  Genau zu diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«,
                freue ich mich jedes Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. <br>
                <br>
                <strong>Schritt 8: </strong>  Damit das Layout nun nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. <br>
                <br>
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