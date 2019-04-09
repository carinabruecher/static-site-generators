<template>
    <div class="body">
        <div class="slider">
            <img class="slider-image" src="../assets/Slider.jpg" alt="slider"/>
        </div>

        <div class="content-allgemeines">
            <img class="image-allgemeines" src="../assets/Slider.jpg" alt="allgemeines zu statische Website Generatoren"/>
            <h1 class="content-headline">Allgemeines</h1>
            <p class="summery-text">Überall dieselbe alte Leier. Das Layout ist fertig, der Text lässt auf sich warten. Damit das Layout nun
                nicht nackt im Raume steht und sich klein und leer vorkommt, springe ich ein: der Blindtext. Genau zu
                diesem Zwecke erschaffen, immer im Schatten meines großen Bruders »Lorem Ipsum«, freue ich mich jedes
                Mal, wenn Sie ein paar Zeilen lesen. Denn esse est percipi - Sein ist wahrgenommen werden. Und weil Sie
                nun schon die Güte haben, mich ein paar weitere Sätze lang zu begleiten, möchte ich diese Gelegenheit
                nutzen, Ihnen nicht nur als Lückenfüller zu dienen, sondern auf etwas hinzuweisen, das es ebenso verdient
                wahrgenommen zu werden: Webstandards nämlich. Sehen Sie, Webstandards sind das Regelwerk, auf dem Webseiten
                aufbauen. </p>
            <nuxt-link class="button" to="/allgemeines">Read more</nuxt-link>
        </div>
        <div class="content-function">
            <h1 class="content-headline">Funktion</h1>
        </div>
    </div>
</template>


<script>
export default {

}
</script>


<style>

    .button {
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

    .button:hover {
        background-color: #22a8b4;
        box-shadow: 0px 1px 3px 0px grey;
    }

    .content-allgemeines {
        padding-bottom: 50px;
        box-shadow: 0 8px 5px -6px grey;
        position: relative;
        z-index: 0;
    }

    .content-function {
        background-color: #d0d0d0;
        position: relative;
        z-index: 100;
    }

    .image-allgemeines {
        /*hier muss nachher der Box-Shadow rein der auf den Slider fällt*/
    }

    .content-headline {
        padding-top: 20px;
        font-size: 20pt;
        color: #1d707c;
    }

    .image-allgemeines {
        height: 320px;
        padding-top: 20px;
        padding-left: 55px;
        padding-right: 20px;
        padding-bottom: 30px;
        width: 550px;
        float: left;
    }

    .slider-image {
        position: relative;
        z-index: 0;
    }

    .summery-text {
        text-align: justify;
        padding-top: 15px;
        padding-right: 85px;
        padding-left: 50px;
    }

</style>
