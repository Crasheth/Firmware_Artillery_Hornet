#Requisiti
1. Firmware Compilato
1. Software  [STM32CubeProgrammer](https://www.st.com/en/development-tools/stm32cubeprog.html#get-software)
1. Cavviavite
1. Cavetti per effettuare un ponte, preferibilmente con morsetti già inseriti.


##Bootloader
La scheda Artillery Ruby non permette via software il flashing del bootloader, ma basta alimentare il boot con 3.3 volt e magicamente possiamo flashare il bootloader...
Procedere scolleganto tutta l'alimentazione, sia cavo dell'alimentazione sia cavo usb.


Svitiamo le tre viti sotto la scocca della stampante.
![Alt text](/Assets/pictures/print1.jpg)
Individuiamo i pin di boot e i pin dei 3.3volt ed effettuiamo un ponte.
![Alt text](/Assets/pictures/boot.jpg)
![Alt text](/Assets/pictures/jump.jpg)



##Installazione Firmware
Colleghiamo la stampante via USB e avremo il display della stampante illuminato ma vuoto.
![Alt text](/Assets/pictures/display.jpg)
A questo punto passiamo al software STM32CubeProgrammer.
Avviato il software ci troviamo davanti questa schermata
![Alt text](/Assets/pictures/schermata1.png)
Se tutto è andato secondo i piani dovremmo trovare come porta USB e quindi potremmo procedere a premere Connect
![Alt text](/Assets/pictures/schermata2.png)
Una volta collegato appare connesso in alto come mostrato in figura
![Alt text](/Assets/pictures/connect.png)
a questo punto clicchiamo sul tab Open File e carichiamo il nostro firmware
![Alt text](/Assets/pictures/firmware.png)
Una volta caricato premere su download e attendere il caricamento. 
Premere ok, disconnettere il programma, spegnere la stampante eliminare il ponte e avviare la stampante.
![Alt text](/Assets/pictures/completed.png)
Se tutto è andato secondo i piani, avrete il vostro bel firmware caricato.
![Alt text](/Assets/pictures/done.jpg)

#English Version

#Requirements
1. Firmware compiled
1. Software [STM32CubeProgrammer](https://www.st.com/en/development-tools/stm32cubeprog.html#get-software)
1. Screwdriver
1. Wire dupont

##Boot loader
The Artillery Ruby card does not allow flashing the bootloader via software, but it is enough to power the boot with 3.3 volts and magically we can flash the bootloader...
Proceed by unplugging all power, both the power and the USB cable.
We unscrew the three screws under the body of the printer.
![Alt text](/Assets/pictures/print1.jpg)
We identify the boot pins and the 3.3 volt pins and make a bridge.
![Alt text](/Assets/pictures/boot.jpg)
![Alt text](/Assets/pictures/jump.jpg)


##Firmware Installation
We connect the printer via USB and we will have the printer display lit but empty.
![Alt text](/Assets/pictures/display.jpg)
At this point we pass to the STM32CubeProgrammer software.
Once the software has been started, we find ourselves in front of this screen
![Alt text](/Assets/pictures/screen1.png)
If all went according to plan you would like to find as USB port and then proceed to press connect
![Alt text](/Assets/pictures/screen2.png)
Once connected it appears connected at the top as shown in the figure
![Alt text](/Assets/pictures/connect.png)
at this point click on the Open File tab and load our firmware
![Alt text](/Assets/pictures/firmware.png)
Once uploaded, click on download and wait for it to load.
Press ok, disconnect the program, turn off the printer, delete the bridge and start the printer.
![Alt text](/Assets/pictures/completed.png)
If all went according to plan, you'll have your nice firmware loaded.
![Alt text](/Assets/pictures/done.jpg)