+++
title = "Galician"
date = 2020-02-21T23:28:33+02:00
draft = "false"
tags = ["galician","languages"]
disableToc = "false"
show_comments = false
lastmod = "2020-02-21T23:28:33+02:00"
publishDate = "2020-02-21T23:28:33+02:00"
summary = ""
+++

<!-- main wavesurfer.js lib -->
<script src="//cdnjs.cloudflare.com/ajax/libs/wavesurfer.js/2.0.5/wavesurfer.min.js"></script>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;}
.tg .tg-4erg{font-weight:bold;font-style:italic;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-rvyq{font-weight:bold;font-style:italic;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-7btt{font-weight:bold;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-fymr{font-weight:bold;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-rvyq"><img src="/flags/galego32.png" alt="eng"></th>
    <th class="tg-4erg">minutos</th>
    <th class="tg-4erg">Tempo</th>
      <th class="tg-4erg">Notas</th>
  </tr>
  <tr>
    <td class="tg-7btt">1.</td>
    <td class="tg-fymr">Gramática/Leccións</td>
    <td class="tg-0pky">180</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-7btt">2.</td>
    <td class="tg-fymr">Ler</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-7btt">3.</td>
    <td class="tg-fymr">Escoitar</td>
    <td class="tg-0pky">10</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-fymr">4.</td>
    <td class="tg-fymr">Escribir</td>
    <td class="tg-0pky">30</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-fymr">5.</td>
    <td class="tg-fymr">Falar</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-fymr">6.</td>
    <td class="tg-fymr">Vocabulario</td>
    <td class="tg-0pky">30</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-fymr">7.</td>
    <td class="tg-fymr">Exercicios fonéticos</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
</table>


O meu primeiro contacto co galego

Non me lembro cando souben a existencia da lingua galega. Cando estaba no ensino medio, había un mapa de autonomía en España na cuarta lección do libro de texto, pero non había ningunha explicación. Cando estiven na universidade interesoume pola historia, cultura e literatura de España e logo lin sobre a poesía galega na Idade Media. Despois descubrín sobre Santiago de Compostela, sobre Camiño, que na Galicia tocan gaitas (ao longo de Hevia), que antes vivían os celtas e que nesta rexión de España hai unha cultura, historia e literatura moi ricas. Cando descubrín que Galicia tiña o seu idioma, tiven moita curiosidade en escoitalo. Gústame moito a lingua galega.


<div id="waveform"></div>
<style> .btn{
  background-color: #57cc8a; /* Green */
  border: none;
  color: black;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  transition-duration: 0.4s;
  cursor: pointer;
  border-radius: 40px;
}
  .btn:hover {
  background-color: white; /* Green */
  color: black;

}
</style>
<div style="text-align: center">
  <button class="btn " onclick="wavesurfer.playPause()">
    <i class="glyphicon glyphicon-play"></i>
    Play
  </button>
</div>
<script>
var wavesurfer = WaveSurfer.create({
  container: '#waveform',
  waveColor: '#57cc8a',
  progressColor: 'red'
});
wavesurfer.load('/galician/galician.mp3');</script>
