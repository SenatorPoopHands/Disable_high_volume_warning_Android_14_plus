<h1>Disable high volume warning</h1>

<div>The European Committee for Electrotechnical Standarisation regulates all media playback devices sold in the European Union to have an output volume warning at 85dB:<br>
<br> 
<p align="center">
  <img width="256" height="142" src="https://i.imgur.com/oNm9wXy.png">
</p>
<br>
Users can increase the volume to a maximum of 100dB by accepting the warning, yet the warning reappears after 20hours of music playback.<br>
<br>
This Magisk module sets the build.prop 'audio.safemedia.bypass' to status 'true' to disable that warning.</div>
<br>
<h1>Fork Additions (Disable automatic volume lowering on android 14+)</h1>
<br>
Additionally sets 'audio.safemedia.force' to false and'audio.safemedia.csd.force' to false in order to address the Android 14+ automatic volume lowering and 'Volume lowered to a safer level' message that happens after 5 minutes of playing at max volume. 
<br>
The changes are highlighted in this article: https://www.androidpolice.com/android-14-headphone-loud-sound-alert/
