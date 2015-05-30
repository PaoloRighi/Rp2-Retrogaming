# Rp2-Retrogaming
<p align=center><b>Mame Console su Raspberry Pi 2 </b></p>

<p align=center><b> Come creare una console per MAME (e altri emulatori) usando un Raspberry Pi2 </b></p>
  
<b>Premessa</b>: non so nulla di elettronica, non sono bravo a saldare, non sono un programmatore! <br>
tutto quello che vi serve per costruire la vosta M.A.M.E. console lo potete trovare in rete dall'hardware al software, hardware a parte, è tutto gratuito.<br>
Un minimo di dimestichezza con Linux aiuta!
<p> L'idea mi è venuta vedendo questo progetto sul sito di <a href="https://learn.adafruit.com/retro-gaming-with-raspberry-pi/overview"> Adafruit </a> </p>


<p><b>Scopo Del Progetto</b></p>
<ol>
<li> Volevo farmi una console per videogiochi arcade da portare con me quando vado in vacanza, magari con la possibilità di usarla anche come PC di emergenza per l'uso di internet, lo streaming video e le applicazioni office.</li>

<li> Divertirsi :O </li>
</ol>


<p><b>Componenti Di Base</b></p>
<ul>
<li>1 Raspberry Pi2 (Amazon)</li>
<li> Micro SD da almeno 8gb (ne ho in casa una manciata :D) </li>
<li>1 Adafruit Small Arcade Joystick (Amazon)</li>
<li>6 Pulsanti di tipo Adafruit Arcade Button 30mm (colori a scelta Amazon)</li>
<li>1 confezione di Premium Female/Female Jumper Wires (Amazon)</li>
</ul>

<p><b>Componenti Opzionali</b></p>
<ul>
<li>1 Microsoft All-in-One Media Keyboard (Amazon)</li>
<li>1 Adattatore USB Wifi per Raspberry Pi (Amazon)</li>
<li>3D printed case per Rpi2 (di cui uso solo la base)</li>
<li> qualche tipo di "scatola" per assemblare il tutto </li>
</ul>

<p><b>Iniziamo!</b></p>
<ol>
<li><b> Setup del Raspberry Pi2 </b></li>
    <p>Per il Setup di base potete attenervi alle istruzioni che trovate sul sito, siccome "NOOBS" e "Raspbian" erano un po' scarne ho scelto "Ubuntu Mate" che ha un desktop piu carino, le istruzioni per creare l'immagine sulla MicroSD le trovate sul sito di<a href="https://ubuntu-mate.org/raspberry-pi/">Mate</a> ma in pratica è il solito: scarica, scompatta e usa dd per creare l'immagine :P , ovviamente è tutto piu semplice se avete gia una macchina con linux installato che vede il lettore SD.</p>
    <p>Dopo il primo avvio è d'obbligo il solito apt-get update && apt-get upgrade oltre all'aggiornamento del software di configurazione del RasPi2 <p>
    <p> Fatto questo potete procedere al download e all'installazione dell'emulatore, nel mio caso ho scaricato il software da <a href="http://sourceforge.net/projects/mame4allpi/"> Source Forge </a> le istruzioni per l'installazione si limitano a "lancia lo script install.sh" quindi ampiamente alla portata di tutti :D
    <p>Caricate le vostre ROM e mettetele nella cartella /usr/local/bin/indiecity/InstalledApps/mame4all/Full/roms/ </p>
    <p>Avviate M.A.M.E e provate le vostre ROM per vedere se vanno, altrimenti provate a convertirle con il programma che trovate su <a href="http://mamedev.emulab.it/clrmamepro/"> Emulab.it </a>
    

