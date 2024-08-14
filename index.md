# Rano

## Architecture
<p align="justify">

</p>

<div style="text-align: center;">
<img src="assets/rano_frame.png" width = 1000 />
</div>
<p align="center">The Architecture of Rano</p>
<p>&nbsp;</p> 

## Audio Samples
<script>
function pauseOthers(ele) {
    $("audio").not(ele).each(function (index, audio) {audio.pause();});
}
</script>

<style>
.main-content table {
    display: inline-table;
}
table {
    table-layout:fixed;
    width: 100%;
    overflow: hidden;
}
#player{
    width: 100%;
}
</style>


<table>
    <CAPTION>Speaker Anonymization via Rano</CAPTION>
    Original utterances in I~III are from the same speaker while IV-VI are from another speaker. Two keys are assigned to all the utterances from these two speakers, respectively.
<tr>
<td>  </td>
<td> Original Speech </td>
<td> Anonymized Speech </td>
<td> Restored Speech </td>
</tr>

<tr>
<td rowspan="2"> I </td>
<td colspan="3"> "Please call Stellar." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig225001.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/ano225001.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res225001.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> II </td>
<td colspan="3"> "Ask her to bring these things with her from the store." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig225002.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/ano225002.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res225002.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> III </td>
<td colspan="3"> "We also need a small plastic snake and a big toy frog for the kids." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig225004.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/ano225004.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res225004.mp3" type="audio/mpeg"></audio> </td>
</tr>	

<tr>
<td rowspan="2"> IV </td>
<td colspan="3"> "They said she was stable." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig246046.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/ano246046.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res246046.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> V </td>
<td colspan="3"> "Is a drug dealer?" </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig246047.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/ano246047.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res246047.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> VI </td>
<td colspan="3"> "The State would provide." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig246049.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/ano246049.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res246049.mp3" type="audio/mpeg"></audio> </td>
</tr>
</table>

<p>&nbsp;</p> 


## Mel-Spectrogram of the Above Tasks

<div style="text-align: center;">
<img src="assets/mel/225001.png" width = 600 />
</div>
<p align="center">Task I</p>

<div style="text-align: center;">
<img src="assets/mel/225002.png" width = 600 />
</div>
<p align="center">Task II</p>

<div style="text-align: center;">
<img src="assets/mel/225004.png" width = 600 />
</div>
<p align="center">Task III</p>

<div style="text-align: center;">
<img src="assets/mel/246046.png" width = 600 />
</div>
<p align="center">Task IV</p>

<div style="text-align: center;">
<img src="assets/mel/246047.png" width = 600 />
</div>
<p align="center">Task V</p>

<div style="text-align: center;">
<img src="assets/mel/246049.png" width = 600 />
</div>
<p align="center">Task VI</p>

<p>&nbsp;</p> 



<p>&nbsp;</p> 



