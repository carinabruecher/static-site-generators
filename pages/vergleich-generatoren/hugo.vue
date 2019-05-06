<template>
    <div class="body">
        <div class="header-hugo">
            <img class="logo-generator-hugo" src="../../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Hugo</h1>
            <p class="summery-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten. </p>
        </div>
        <div class="step-light">
            <img class="image-step-1" src="../../assets/Slider.jpg" alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline">Merkmale</h1>
            <p class="summery-text">
                -  Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. <br>
                -  Genau zu diesem Zwecke erschaffen, immer im Schatten meines großen Bruders <br>
                -  Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun nicht nackt <br>
                -  Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. <br>
                -  Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun nicht nackt <br>
                -  Genau zu diesem Zwecke erschaffen, immer im Schatten meines großen Bruders <br>
                -  Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun nicht nackt <br>
                -  Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. <br>
                -  Genau zu diesem Zwecke erschaffen, immer im Schatten meines großen Bruders <br>
                -  Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun nicht nackt <br>
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
                        <td>Bastards are born of passion, aren't they?</td>
                        <td>Winter is coming.</td>
                    </tr>
                    <tr>
                        <td>We don't despise them in Dorne.</td>
                        <td>Dunc the Lunk, thick as a castle wall.</td>
                    </tr>
                    <tr>
                        <td>Fire and blood.</td>
                        <td>The Knight of Lemonwood.</td>
                    </tr>
                    <tr>
                        <td>King in the North.</td>
                        <td>Each should have its own reward.</td>
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