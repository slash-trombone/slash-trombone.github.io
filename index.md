# Pink trombone audios

#### Authors: Mateo Cámara, Zhiyuan Xu, Yisu Zong, and David Südholt.

#### Abstract: The abstract...

## Pink Trombone audios without variation (3.2.1)

Reference audio:


<audio controls=""> 
    <source src="audio/1_step_ref.wav">
</audio>

Produced audio after optimization:

<audio controls=""> 
    <source src="audio/1_step_pred.wav">
</audio>


## Pink Trombone audios without variation with Gaussian Noise (3.2.2)

PLEASE MIND THE VOLUME, IT COULD BE VERY LOUD

<div class="figure">
    <table>
        <tbody><tr>
            <th>SNR (dB)</th>
            <th>Original Audio</th>
            <th>Produced Audio after optimization</th>
        </tr>
        <tr>
            <td><b>inf</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/1_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/1_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>10</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/10db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/10db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>0</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/1db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/1db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>-10</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/-10db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/-10db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>-20</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/-20db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/-20db_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>-30</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/-30db_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/-30db_pred.wav">
                </audio>
            </td>
        </tr>
    </tbody>
</table>
</div>

## Pink Trombone audios with variation (3.2.3)

<div class="figure">
    <table>
        <tbody><tr>
            <th>Steps</th>
            <th>Original Audio</th>
            <th>Produced Audio after optimization</th>
        </tr>
        <tr>
            <td><b>1</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/1_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/1_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>2</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/2_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/2_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>3</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/3_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/3_step_pred.wav">
                </audio>
            </td>
        </tr>
        <tr>
            <td><b>10</b></td>
            <td>
                <audio controls=""> 
                    <source src="audio/10_step_ref.wav">
                </audio>
            </td>
           <td>
                <audio controls=""> 
                    <source src="audio/10_step_pred.wav">
                </audio>
            </td>
        </tr>
    </tbody>
</table>
</div>

## Real audios (3.2.3)

Reference audio: a man saying "A":

<audio controls=""> 
    <source src="audio/aaa_yo.wav">
</audio>

Predicted audio after optimization:

<audio controls=""> 
    <source src="audio/mio_a.wav">
</audio>

<br>

Reference audio: a man saying "AO":

<audio controls=""> 
    <source src="audio/ao_yo.wav">
</audio>

Predicted audio after optimization:

<audio controls=""> 
    <source src="audio/mio_ao.wav">
</audio>

<br>

Reference audio: a man yawning:

<audio controls=""> 
    <source src="audio/real_yawning_chunk.wav">
</audio>

Predicted audio after optimization at once (no windowing) without Savinzky-Galoy filter:

<audio controls=""> 
    <source src="audio/predicted_yawn_atonce.wav">
</audio>

Predicted audio after optimization with 100 ms window without Savinzky-Galoy filter:

<audio controls=""> 
    <source src="audio/0.wav">
</audio>

Predicted audio after optimization with 20 ms window without Savinzky-Galoy filter:

<audio controls=""> 
    <source src="audio/predicted_yawn_notprocessed.wav">
</audio>

Predicted audio after optimization with 20 ms window with Savinzky-Galoy filter:

<audio controls=""> 
    <source src="audio/predicted_yawn.wav">
</audio>