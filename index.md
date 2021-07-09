# Welcome!

Here, we show the Multi-speaker TTS system.<br>
We add LDE Speaker Embeddings and Voice Conversion Embeddings in our Tacotron 2.<br>
And, the vocoder is DiffWave which is trained by VCTK Corpus about 500_000 iteration.
<br>
<b>The Tacotron2 system has not yet reached the best! </b>

# Seen Speaker
## Inside Text

<b>zh001.wav 在實現這些最重要也是最難的地方在於張量維度的轉換</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>        
                <audio controls>
                    <source src="audio/zh/001.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>en001.wav Do you have any tables available this evening?</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/en/001.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>

<b>cs001.wav 在實現這些model最重要也是最難的地方在於張量維度的轉換</b>
<div style="border:1px black solid;width:1002px;">
    <table>
        <tr>
            <td> Ground-truth</td>
            <td> VC Embedding</td>
            <td> LDE Embedding</td>
        </tr>
        <tr>
            <td>
                <audio controls>
                    <source src="audio/01.wav" type="audio/wav">
                </audio>
            </td>
        </tr>
    </table>
</div>
