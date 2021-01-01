+++
title = "New Goals 2021"
date = 2021-01-01T21:22:10+02:00
draft = "true"
tags = ["english","languages"]
disableToc = "false"
show_comments = false
lastmod = "2021-01-01T21:22:10+02:00"
publishDate = "2021-01-01T21:22:10+02:00"
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
    <th class="tg-rvyq"><img src="/flags/uk32.png" alt="eng"></th>
    <th class="tg-4erg"></th>
    <th class="tg-4erg">Time</th>
    <th class="tg-4erg">Notes</th>
  </tr>
  <tr>
    <td class="tg-7btt">1.</td>
    <td class="tg-fymr">Grammar/Lessons</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-7btt">2.</td>
    <td class="tg-fymr">Reading</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-7btt">3.</td>
    <td class="tg-fymr">Listening</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-fymr">4.</td>
    <td class="tg-fymr">Writing</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-fymr">5.</td>
    <td class="tg-fymr">Speaking</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-fymr">6.</td>
    <td class="tg-fymr">Vocabulary</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    </tr>
  <tr>
    <td class="tg-fymr">7.</td>
    <td class="tg-fymr">Phonetic drills</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
  </tr>
</table>


<audio controls="" class="audio_controls" preload="metadata" style="">
<source src="/portuguese/na-classe/na-classe.mp3">
Your browser does not support the audio element
</audio>

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
wavesurfer.load('/posts/.mp3');</script>
