<template>
    <div id="footer" class="footer-cdm">
        <section class="footer-black">
            <h1 class="typo-logo">LA COUR DES MIRACLES</h1>
            <p><b>©</b>Tous droits réservés</p>
            <span>1 Rue Delacroix : </span><a slot="activator" href="tel:+33561539255">05 61 53 92 55</a><br>       
            <span>10 Rue Malbec : </span><a slot="activator" href="tel:+330984011269">09 84 01 12 69</a><br>       
            <a href="contact@thebigvoodoo.com">contact@lacourdesmiracles.tattoo</a><br>
            <span class="body-1">Réalisé avec <b>&hearts;</b> par <a target="_blank" href="https://influx-agence.fr">Influx</a></span>
        </section>
    </div>
</template>

<style>
    #footer .footer-black {
        width: 100%;
        float: left;
        background:#000000;
        color:#ffffff;
        text-align:center;
        padding: 40px;
    }
    #footer .footer-black p{
        text-align: center;
        color: #a8a8a8;
    }
    #footer .footer-black span{
        color: #FFFFFF;
    }
    #footer .footer-black b{
        color:#FFFFFF;
    }
    #footer .footer-black a{
        color:#a8a8a8;
        text-decoration: underline;
        -webkit-text-decoration-color: #ffffff;
        text-decoration-color: #ffffff;
    }
    #footer .footer-black #logoF {
      width: 70px;
      height: 70px;
      position: relative;
      display: block;
      margin: 0 auto;
    }
    @media only screen and (min-width:960px) and (max-width:1264px){
    }
    @media only screen and (min-width:600px) and (max-width:959px){
    }
    @media only screen and (max-width:599px){
        .footer-black {
            padding: 15px 0;
        }
    }
</style>
