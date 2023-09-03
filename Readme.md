#Requisiti
1. Firmware Compilato
1. Software  [STM32CubeProgrammer](https://www.st.com/en/development-tools/stm32cubeprog.html#get-software)
1. Cavviavite
1. Cavetti per effettuare un ponte, preferibilmente con morsetti già inseriti.


##Bootloader
La scheda Artillery Ruby non permette via software il flashing del bootloader, ma basta alimentare il boot con 3.3 volt e magicamente possiamo flashare il bootloader...
Procedere scolleganto tutta l'alimentazione, sia cavo dell'alimentazione sia cavo usb.


Svitiamo le tre viti sotto la scocca della stampante.
<picture><srcset="/assets/pictures/print1.jpg"></picture>
Individuiamo i pin di boot e i pin dei 3.3volt ed effettuiamo un ponte.
<picture><srcset="assets/picture/boot.jpg"></picture>
<picture><srcset="assets/picture/jump.jpg"></picture>


##Installazione Firmware
Colleghiamo la stampante via USB e avremo il display della stampante illuminato ma vuoto.
<picture><srcset="/assets/pictures/display.jpg"></picture>
A questo punto passiamo al software STM32CubeProgrammer.
Avviato il software ci troviamo davanti questa schermata
<picture><srcset="/assets/pictures/schermata1.png"></picture>
Se tutto è andato secondo i piani dovremmo trovare come porta USB e quindi potremmo procedere a premere Connect
<picture><srcset="/assets/pictures/schermata2.png"></picture>
Una volta collegato appare connesso in alto come mostrato in figura
<picture><srcset="/assets/pictures/connect.png"></picture>
a questo punto clicchiamo sul tab Open File e carichiamo il nostro firmware
<picture><srcset="/assets/pictures/firmware.png"></picture>
Una volta caricato premere su download e attendere il caricamento. 
Premere ok, disconnettere il programma, spegnere la stampante eliminare il ponte e avviare la stampante.
<picture><srcset="/assets/pictures/completed.png"></picture>
Se tutto è andato secondo i piani, avrete il vostro bel firmware caricato.
<picture><srcset="/assets/pictures/done.jpg"></picture>



#Requirements
1. Firmware compiled
1. Software [STM32CubeProgrammer](https://www.st.com/en/development-tools/stm32cubeprog.html#get-software)
1. Screwdriver
1. Wire dupont

##Boot loader
The Artillery Ruby card does not allow flashing the bootloader via software, but it is enough to power the boot with 3.3 volts and magically we can flash the bootloader...
Proceed by unplugging all power, both the power and the USB cable.
We unscrew the three screws under the body of the printer.
<picture><srcset="/assets/pictures/print1.jpg"></picture>
We identify the boot pins and the 3.3 volt pins and make a bridge.
<picture><srcset="assets/picture/boot.jpg"></picture>
<picture><srcset="assets/picture/jump.jpg"></picture>


##Firmware Installation
We connect the printer via USB and we will have the printer display lit but empty.
<picture><srcset="/assets/pictures/display.jpg"></picture>
At this point we pass to the STM32CubeProgrammer software.
Once the software has been started, we find ourselves in front of this screen
<picture><srcset="/assets/pictures/screen1.png"></picture>
If all went according to plan you would like to find as USB port and then proceed to press connect
<picture><srcset="/assets/pictures/screen2.png"></picture>
Once connected it appears connected at the top as shown in the figure
<picture><srcset="/assets/pictures/connect.png"></picture>
at this point click on the Open File tab and load our firmware
<picture><srcset="/assets/pictures/firmware.png"></picture>
Once uploaded, click on download and wait for it to load.
Press ok, disconnect the program, turn off the printer, delete the bridge and start the printer.
<picture><srcset="/assets/pictures/completed.png"></picture>
If all went according to plan, you'll have your nice firmware loaded.
<picture><srcset="/assets/pictures/done.jpg"></picture>