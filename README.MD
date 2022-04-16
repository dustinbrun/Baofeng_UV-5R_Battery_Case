# Baofeng UV-5R Battery Case
A simple battery case for the Baofeng UV-5R (and maybe some other Baofeng models) radio.

It was inspired by commercial battery adapters, which can be bought online:

<img src="pictures/Original.jpg" width="40%">
(Source: https://i.ebayimg.com/images/g/b9gAAOSwS9BdGHeZ/s-l1600.jpg

The 3D-model of the case can be downloaded from this Github repository. The original model was made by  jameslee522 (https://www.thingiverse.com/thing:4607617 / CC BY 4.0). I customized it using Tinkercad, where you can also find this model:  https://www.tinkercad.com/things/dRWLIG0PLxn

<img src="pictures/3D-model.png" width="30%">

## Original Battery Pack
The nominal voltage is 7.4V (Li-ion cell)

pinout: 
<img src="pictures/Battery_Pack.jpg" width="30%">

## Electronics
I designed the case in a way, that it can be plugged into a USB-5V source like a powerbank. For this purpose it uses a step-up converter, which you can easily find online. There is also a capacitor to provide a stable voltage at current spikes (for example in the transmit mode).

The battery connection poles can be created using some strip grid circuit board with some drops of solder on it (see pictures).

You can also modify the design to work with a 12V power source (like a car socket) by using a step-down converter.

The output voltage must be set to 7.4V!!

<img src="pictures/Baofeng_Step_UP_Circuit_Steckplatine.png" width="100%">

## Final design
<img src="pictures/Case_Bottom.jpg" width="40%">
<img src="pictures/Battery_Poles.jpg" width="40%">


<br><br>
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:cc="http://creativecommons.org/ns#" class="license-text">This work by <span property="cc:attributionName">Dustin Brunner</span> is licensed under <a rel="license" href="https://creativecommons.org/licenses/by/4.0">CC BY 4.0<img style="height:15px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" /><img style="height:15px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" /></a></p>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Dieses Werk von <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Dustin Brunner</span> ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Namensnennung 4.0 International Lizenz</a>.
