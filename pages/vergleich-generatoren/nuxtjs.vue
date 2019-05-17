<template>
    <div class="body">
        <div class="header-nuxtjs">
            <img class="logo-generator-hugo" src="../../assets/header-image-nuxt.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Nuxt.js</h1>
            <p class="summery-text">Nuxt.js ist eine freie Open Source Webanwendung, basiernd auf vue.js.
                Die Hauptaufgabe des Generator das Rendern der Benutzeroberfläche. Das Framework Nuxt.js bietet hohe
                Flexibilität und lässt sich als Basis für weitere Anwendungsentwicklung verwenden. Der Generator macht
                es einfach Code zwischen Client und Server auszutauschen, außerdem können universelle Apps einfach geschrieben
                werden. Im ganzen gesehen ist dieser Generator einfach zu bedienen, sehr flexibel und bietet viele Vorteile
                die dem Programmiere das Leben erleichtern.
            </p>
        </div>
        <div class="step-light">
            <img class="image-step-1" src="../../assets/merkmal-image-nuxt.jpg" alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline">Merkmale</h1>
            <p class="summery-text">
                -  Verringerte Zeit für Interaktivität <br>
                -  gute SEO Eigenschaften <br>
                -  Tool um Vue.js serverseitig zu rendern <br>
                -  Projekt kann ohne Vorwissen gestartet werden <br>
                -  zeitliche Flexibilität und Agilität <br>
                -  hervorragende Projektstruktur <br>
                -  Starter Vorlage für Anfänger in der Kommandozeile <br>
                -  automatische Codeaufteilung ( jede Route erhält eine Javascript Datei) <br>
                -  universelle App ohne Server <br>
                -  Code teilbar zwischen Server und Client <br>
            </p>
        </div>
        <div class="how-to">
            <h1 class="headline-step-by-step">Step by Step</h1>
            <p class="summery-text">
                <i>Installation und neues Projekt erstellen</i>
                <br>
                <strong>Schritt 1: </strong> ~ npx create-nuxt-app beispie-projekt <br>
                <br>
                <br>
                <i>Konfiguration des neuen projektes</i>
                <br>
                <strong>? Project name</strong> mit Enter wird der vorher definierte name übernommen <br>
                <br>
                <strong>? Project description</strong> mit Enter wird die Beschreibung in den Klammern bestätigt, wer eine andere Beschreibung möchte kann diese einfach eintippen<br>
                <br>
                <strong>? Use a custom server framework </strong> none<br>
                <br>
                <strong>? Choose features to install</strong> axious auswählen<br>
                <br>
                <strong>? Use a custom UI framework </strong> tailwind auswählen <br>
                <br>
                <strong>? Choose rendering mode </strong> universal auswählen <br>
                <br>
                <strong>? Autor name </strong> Name des Autors eintragen und mit Enter bestätigen <br>
                <br>
                <strong>? Choose a package manager </strong> npm <br>
                <br>
                <br>
                <i>Server starten</i>
                <strong>Schritt 2:</strong> ~ npm run dev<br>
                <br>
                <br>
                <strong>Seitenvorschau im Browser anzeigen</strong> <br>
                Um die Site im Browser zu sehen muss man in die URL-leiste "localhost:3000" eingeben.
                <br>
                <br>
                <strong>Generieren der Html-Dokumente</strong> <br>
                ~ generate <br>
                Die generierten Dokumente werden im "dist" Ordner gespeichert
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
                    <td>Konfigurationen und Setups sind für Anwendungsentwickler vereinfacht und nahtlos gestaltet</td>
                    <td>weniger geeignet für große Datenmengen</td>
                </tr>
                <tr>
                    <td>Nahe an Ember.js daher relativ nahbare Konvention</td>
                    <td>Dbedingt geeignet für hochdynamische Webseiten</td>
                </tr>
                <tr>
                    <td>automatisch aktualisierter Server</td>
                    <td>Suchmaschinen können durch schnelle Neuerungen auf Seite durcheinander kommen</td>
                </tr>
                <tr>
                    <td>einfaches erstellen von Datenkomponenten</td>
                    <td>Feintuning bei schnellen Änderungen komplex</td>
                </tr>
                <tr>
                    <td>einfache Übergänge zwischen Routern</td>
                    <td> </td>
                </tr>
            </table>
        </div>
        <div class="grid-overview">
            <nuxt-link class="left-1" to="hugo">
                <img class="teaser-generatoren" src="../../assets/teaser-hugo.jpg" alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
            <nuxt-link class="rechts" to="jeklly">
                <img class="teaser-generatoren" src="../../assets/teaser-jekyll.jpg" alt="Funktionen statische Website Generatoren"/>
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

    .header-nuxtjs {
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