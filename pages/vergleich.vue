<template>
    <div class="body">
        <div class="header">
            <img class="vergleich-headerimage" src="../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
            <h1 class="content-headline-vergleich">Vergleich</h1>
            <p class="summery-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten. </p>
        </div>
        <div class="short-vergleich">
            <h2 class="subheadline">Kurzübersicht über die Static-Site Generatoren</h2>
            <p class="short-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun nicht<br>
                nackt im Raume steht und sich klein und leer vorkommt, springe ich ein.</p>
            <img class="vergleich-tabelle" src="../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
        </div>
        <div class="grid-overview">
            <nuxt-link class="left-1" to="vergleich-generatoren/hugo">
                <img class="teaser-generatoren" src="../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
            <nuxt-link class="rechts" to="/vergleich-generatoren/jeklly">
                <img class="teaser-generatoren" src="../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
            <br>
            <nuxt-link class="left-2" to="/vergleich-generatoren/nuxtjs">
                <img class="teaser-generatoren" src="../assets/Slider.jpg" alt="Funktionen statische Website Generatoren"/>
            </nuxt-link>
        </div>
    </div>
</template>

<style>

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
        padding-bottom: 50px;
        box-shadow: inset 0px 0px 5px 2px grey;
    }

    .grid-overview {
        background-color: #e3e3e3;
        position: relative;
        z-index: 0;
        padding-bottom: 50px;
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