<a href="pictures/stknx_breakout_brd_top_v14.png"><img src="pictures/stknx_breakout_brd_top_small_v14.png" alt="STKNX Breakout Board Top" align="left" width="250" ></a>
<a href="pictures/stknx_breakout_brd_bot_v14.png"><img src="pictures/stknx_breakout_brd_bot_small_v14.png" alt="STKNX Breakout Board Top" width="250" ></a>


<img align="left" src="https://selfbus.org/wiki/images/icons/exclamation-triangle.svg" height="80px" width="80px" />
<h2>Vorsicht!</h2>
Dieses Teilprojekt wurde aus dem alten hardware-incubation Repository übernommen. Viele dieser Projekte sind nicht ausgereift!

Um verschiedene Probleme in der Synchronisation der beiden Repositorys in Zukunft zu vermeiden, wurde aber auch dieser Ordner / dieses Stück Hardware in das eine "Hardware" Repository übernommen.

Du hast Ideen, wie man es weiterentwickeln / fertigstellen könnte? Lass es uns wissen und werde Teil unserer Community!
<br />--> https://selfbus.org
<br />--> https://selfbus.org/forum
<br />--> https://selfbus.org/chat 

<hr>

<img align="left" src="https://selfbus.org/wiki/images/icons/exclamation-triangle.svg" height="80px" width="80px" />
<h2>Attention!</h2>
This sub-project was taken from the old hardware-incubation repository. Many of these projects are not mature!
In order to avoid various problems in the synchronization of the two repositories in the future, this folder / this piece of hardware was also merged to the one "hardware" repository.
<hr><hr>
Do you have ideas on how to further develop / finish it? Let us know and become part of our community!
 
# STKNX Breakout Board
Es handelt sich hierbei um den noch ***ungetesteten*** Entwurf eines Breakout Boards für das KNX TP1-256 Frontend [STKNX](https://www.st.com/en/interfaces-and-transceivers/stknx.html) der Firma STMicroelectronics im etwas unhandlichen QFN Gehäuse.

Der STKNX trennt die Versorgungsspannung von den auf dem KNX-Bus übertragenen Daten, welche er als Bitstrom ausgibt. Er enthält keinen eigenen Controller, dafür aber einen von 1 - 12V einstellbaren Step-Down-Konverter (max. 150mA) sowie einen auf 3.3V bzw. 5V einstellbaren Linearregulator (max. 20mA).

**Achtung: Der Jumper SJ2 darf nur überbrückt werden (Linearregler aus), wenn Vout nicht größer als 5V ist!!**

## V1.3 - Initiale Version
<a href="pictures/stknx_breakout_3D.png"><img src="pictures/stknx_breakout_3D.png" alt="STKNX Breakout Board 3D" width="200" ></a>

[Schaltplan](docs/stknx_breakout_sch.pdf) \
[Eagle-Dateien](eagle)

<a href="pictures/stknx_breakout_brd_top.png"><img src="pictures/stknx_breakout_brd_top_small.png" alt="STKNX Breakout Board Top" align="left" width="250" ></a>
<a href="pictures/stknx_breakout_brd_bot.png"><img src="pictures/stknx_breakout_brd_bot_small.png" alt="STKNX Breakout Board Top" width="250" ></a>

## V1.4
- R1 geändert auf SMD 2512
- einige Bauteile neu platziert
- Hinweis zu Jumper SJ2 eingefügt (nur überbrücken, wenn Vout <= 5V)
- Schaltplan: Hinweis für Spannungsfestigkeit C11 

<a href="pictures/stknx_breakout_3D_v14.png"><img src="pictures/stknx_breakout_3D_v14.png" alt="STKNX Breakout Board 3D" width="200" ></a>

[Schaltplan](docs/stknx_breakout_sch_v14.pdf) \
[Eagle-Dateien](eagle)


