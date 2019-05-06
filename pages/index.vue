<template>
    <div class="body">

        <div class="content-top-slider">
            <img class="slider-image" src="../assets/top-slider.jpg" alt="slider"/>
        </div>

        <div class="content-allgemeines">
            <img class="image-allgemeines" src="../assets/teaser-bild-allgemeines.jpg"
                 alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline-allgemeines">Allgemeines</h1>
            <p class="summery-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten.
                Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten, möchte ich diese Gelegenheit
                nutzen, Ihnen nicht nur als Lückenfüller zu dienen, sondern auf etwas hinzuweisen. </p>
            <nuxt-link class="button-allgemeines" to="/allgemeines">Read more</nuxt-link>
        </div>

        <div class="content-function">
            <img class="image-functions" src="../assets/teaser-bild-funktion.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-function">Funktion</h1>
            <p class="summery-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten.
                Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten, möchte ich diese Gelegenheit
                nutzen, Ihnen nicht nur als Lückenfüller zu dienen, sondern auf etwas hinzuweisen, das es ebenso
                verdient
            </p>
            <nuxt-link class="button-function" to="/funktion">Read more</nuxt-link>
        </div>

        <div class="content-vergleich">
            <img class="image-vergleich" src="../assets/teaser-bild-vergleich.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Vergleich</h1>
            <p class="summery-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten.
                Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten, möchte ich diese Gelegenheit
                nutzen, Ihnen nicht nur als Lückenfüller zu dienen, sondern auf etwas hinzuweisen, das es ebenso
                verdient
                wahrgenommen zu werden. </p>
            <nuxt-link class="button-vergleich" to="/vergleich">Read more</nuxt-link>
        </div>

        <div class="content-umsetzung">
            <img class="image-umsetzung" src="../assets/teaser-bild-umsetzung.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-umsetzung">Umsetzung</h1>
            <p class="summery-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten.
                Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten, möchte ich diese Gelegenheit
                nutzen, Ihnen nicht nur als Lückenfüller zu dienen, sondern auf etwas hinzuweisen. </p>
            <nuxt-link class="button-umsetzung" to="/umsetzung">Read more</nuxt-link>
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