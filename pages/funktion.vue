<template>
    <div class="body">
        <div class="step-dark">
            <img class="image-umsetzung-header" src="../assets/header-bild-funktion.jpg"
                 alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline">Funktion</h1>
            <p class="summery-text-top">Statische Webseiten-Generatoren sind Codegerüste mit deren Hilfe statische
                Webseiten
                erstellt werden können. Der HTML-Code wird lokal auf dem Rechner erzeugt, bei der Nutzung sind also
                keine
                Datenbanken oder serverseitige Sprachen, wie PHP, nötig. Die Generatoren müssen über die Kommandozeile
                sowohl installiert als auch bedient werden, da die große Mehrheit der Generatoren keine
                Benutzeroberfläche hat.</p>
        </div>
        <div class="step-light">
            <img class="image-step-1" src="../assets/Slider.jpg" alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline">Technische Details</h1>
            <p class="summery-text">
                Alle Komponenten für die Seite liegen in einem Verzeichnis, wo sie getrennt nach Layout und Content
                gespeichert
                sind. Der Content wird in Markdown-Dateien geschrieben. Markdown ist eine vereinfachte
                Auszeichnungssprache,
                die leicht zu schreiben und auch ohne Konvertierung leicht zu lesen ist. Für das Layout gibt es eine
                Template-Engine,
                mit der Vorlagen erstellt werden. Der Content wird dann in das vordefinierte Template geparst und ein
                Converter
                transformiert dann alles in einen HTML Code. Oft kann man den lokalen Server zum testen und debuggen
                verwenden,
                so das man bei Änderungen eine Art Vorschau hat. Datenformate wie JSON oder YAML können für Metadaten
                benutzt
                werden, die dann an verschiedenen Stellen auf der Website verwendet werden können. Des weiteren kann man
                Plugins
                und Erweiterungen benutzen, um mehr Funktionen hinzuzufügen. Dabei kann man entweder schon vorhandene
                Plugins
                downloaden, oder ein eigenes schreiben.</p>
        </div>
        <div class="step-dark">
            <h1 class="content-headline">Marktüberblick</h1>
            <div class="overview">
                <p>Top 10 der Static Site Generators (nach Sternen auf GitHub)</p>
                <br>
                <table id="table-overview">
                    <tr>
                        <th></th>
                        <th>Lizenz</th>
                        <th>Sprache</th>
                        <th>Template-Engine</th>
                        <th>Merkmale</th>
                    </tr>
                    <tr>
                        <td class="merkmal">Jekyll</td>
                        <td>MIT</td>
                        <td>Ruby</td>
                        <td>Liquid</td>
                        <td>
                            <ul>
                                <li>Fokus liegt auf Einfachheit</li>
                                <li>Mit GitHub Pages können Seiten direkt aus dem Repository gehostet werde</li>
                                <li>Für Blogs</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Next.js</td>
                        <td>MIT</td>
                        <td>JavaScript</td>
                        <td>React</td>
                        <td>
                            <ul>
                                <li>React Framework</li>
                                <li>Seiten werden auf dem Server gerendert</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Hugo</td>
                        <td>Apache 2.0</td>
                        <td>Go</td>
                        <td>Go</td>
                        <td>
                            <ul>
                                <li>Entwickelt von Google</li>
                                <li>Ausgelegt auf Schnelligkeit und Einfachheit</li>
                                <li>Für alle Arten von Websites</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Gatsby</td>
                        <td>MIT</td>
                        <td>JavaScript</td>
                        <td>React</td>
                        <td>
                            <ul>
                                <li>Neueste Technologien und viele Plugins</li>
                                <li>Progressive Web Apps Generator (resultiert in schnellere Seiten)</li>
                                <li>Für alle Arten von Websites</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Hexo</td>
                        <td>MIT</td>
                        <td>JavaScript</td>
                        <td>EJS, Pug, Haml, Swig, Nunjucks, Mustache, Handlebars, Twig, Marko</td>
                        <td>
                            <ul>
                                <li>Basiert auf Node.js</li>
                                <li>Schnelles generieren von Dateien</li>
                                <li>Unterstützt die meisten Plugins, CSS Präprozessoren und Template-Sprachen</li>
                                <li>Für Blogs</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">GitBook</td>
                        <td>Apache 2.0</td>
                        <td>JavaScript</td>
                        <td>Jinja2</td>
                        <td>
                            <ul>
                                <li>Für Bücher</li>
                                <li>Bücher im Editor schreiben und mit Git veröffentlichen</li>
                                <li>Bücher können auch direkt verkauft werden</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Nuxt.js</td>
                        <td>MIT</td>
                        <td>JavaScript</td>
                        <td>Vue</td>
                        <td>
                            <ul>
                                <li>Basiert auf Vue.js</li>
                                <li>Server-seitiges rendering</li>
                                <li>Statische Seiten basierend auf Vue Anwendungen</li>
                                <li>Single Page Applications</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">VuePress</td>
                        <td>MIT</td>
                        <td>JavaScript</td>
                        <td>Vue</td>
                        <td>
                            <ul>
                                <li>Standard Theme ist optimiert für technische Dokumentationen</li>
                                <li>Minimalistisch, Fokus auf Markdown</li>
                                <li>Single Page Apps</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Docusaurus</td>
                        <td>MIT</td>
                        <td>JavaScript</td>
                        <td>Markdown</td>
                        <td>
                            <ul>
                                <li>Für Code-Dokumentationen</li>
                                <li>Einfach und Funktionell</li>
                                <li>Übersetzung der Inhalte einfach gemacht</li>
                                <li>Versionierung</li>
                                <li>Suchfunktion</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td class="merkmal">Pelican</td>
                        <td>APGL v3.0</td>
                        <td>Python</td>
                        <td>Jinja 2</td>
                        <td>
                            <ul>
                                <li>Für Blogs</li>
                                <li>Content kann in reStructuredText, Markdown oder AsciiDoc geschrieben werden</li>
                                <li>Output ist komplett statisch für einfaches Hosting</li>
                                <li>Code syntax highlighting</li>
                                <li>Plugin Repository</li>
                                <li>Import von WordPress o.a. möglich</li>
                            </ul>
                        </td>
                    </tr>
                </table>
            </div>
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

    .summery-text-1 {
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