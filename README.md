<h1>Selfbus Hardware</h1>
<h2>Main-Branch</h2>
This branch contains <b>all</b> Selfbus hardware items which are needed to build up KNX devices: different types of PCBs, 3D printable tools and enclosures. 

<h2>Other Branches</h2>
Experimental development shall be done within a seperate branch to prevent the main branch getting spammed with dev-commits. 

<h3>Folder structure</h3>
<ul>
<li> addons - item / part / pcb which adds additional functions to a controller, application or module 
<li> applications - applications/devices that require an additional controller board
<li> controller - controller boards
<li> module - devices that do not require a controller board. The controller and the app are merged within one PCB. 
<li> misc - other stuff that is not an EIB bus device
<li> tool - helpers with no functionality without another item
</ul>

<h3>Abbreviations</h3>
<ul>
<li>FM - flush mount (UP Unterputz)
<li>DIN - din rail mountable (für Hutschieneninstallation)
<li>MU - module units (TE Teilungseinheiten); indicates how much space a DIN rail device needs 
<li>*lpc922* - module or controller with lpc922 µC
<li>*lpc1115* - module or controller with lpc1115 µC
<li>TOP / MID / BOT - position where in a DIN rail enclosure a PCB will be mounted
</ul>

<h2>Releases</h2>
The unversioned *.sch and *.brd files indicate development files. 
Once a new version is released, a corresponding folder will be created and copy of the files with the release version appended to the file name will be stored in that folder as well as all other files connected directly to that version (iBom, labels, etc.).

<b>Example: </b>https://github.com/selfbus/hardware-merged/tree/main/modules_lpc1115/smokedetector <br/>
But keep in mind, that this is not implemented in each and every project. In fact it's the exception today (11.05.2023) since a lot of projects are existing within this repository. 
  
<h2>Identify mature hardware</h2>
A warning hint within the readme.md was placed in nearly all projects taken over from hardware-incubation. A folder without that hint contains most likely a stable version taken over from the "hardware" repository. If you are not sure: search for documentation for that device or item at https://selfbus.org or ask the community via https://selfbus.org/forum or https://selfbus.org/chat.
