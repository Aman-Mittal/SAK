################################################################################################################################
### DEUTSCHE BESCHREIBUNG
################################################################################################################################

********************************************************************************************************************************
*** Switch Army Knife (SAK) by kempa - Dezember 2018
********************************************************************************************************************************

Version: beta v0.6
Ver�ffentlicht auf psxtools.de

ICH (kempa) �bernehme keine Verantwortung f�r Sch�den/Bricks jeglicher Art.
Die durch XCI's oder bei der sp�teren Installation auf der Switch von NSP's auftreten k�nnen!
Nutzt stets eure eigenen Spiele, die ihr auch legal besitzt!
So habt ihr sp�ter auch keine Probleme.

*** Ich unterst�tze kein Warez!!! ***

********************************************************************************************************************************

Urheberrecht:
Der Code wurde komplett von mir pers�nlich entwickelt.
So kann das Tool v�llig frei und legal angeboten werden!

Voraussetzung daf�r:
Das 7zip Archiv darf nicht ver�ndert werden
Immer mit Quellenangabe zum original Forum-Thread (siehe nachfolgenden Support Link)

Wichtige Infos: (hinzugef�gte Tools die nicht von mir sind):
4NXCI - Hier gilt das Danke an The-4n und SciresM f�r die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/The-4n/4NXCI

hactool - Hier gilt das Danke an SciresM f�r die Entwicklung und das bereitstellen des Tools.
Quelle: https://github.com/SciresM/hactool

FAT32 Format - Danke geht an Ridgecrop Consultants Ltd f�r die GUI Version vom FAT32 Format Tool.
Quelle: http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm

********************************************************************************************************************************

Support: Auf psxtools.de (https://psxtools.de/index.php/Thread/77281)

********************************************************************************************************************************
*** Funktionen
********************************************************************************************************************************

Mit diesem Switch Taschenmesser k�nnt ihr eure Inhalt XCI/NSP von eurer Switch einfach jonglieren.

- XCI splitten / zusammenf�gen
- XCI nach NSP konvertieren
- NSP splitten
- SD Karte in FAT32 formatieren

*** Generell gilt:
Alle Dateien werden immer im Ordner von SAK erstellt.
Es werden nur XCI + NSP Dateien >= 4GB zum splitten akzeptiert.
Alle < 4GB macht dass splitten ja auch kein Sinn!

*** F�r XCI splitten gilt:
XCI k�nnen in voller Gr��e oder getrimmt gesplittet werden.
Getrimmt bedeutet, dass der leere Speicherplatz am Ende entfernt wird.
Dadurch gibt es einen kleinen Speicherplatz gewinn f�r das XCI Abbild.

Der neue Dateiname wird mit "_splitted" erg�nzt.

K�nnen auch direkt auf die �SD Karte via USB Reader gesplittet werden.

*** XCI zusammenf�gen gilt:
Dateiendungen.xc0 und .xci.00 werden akzeptiert

*** F�r XCI nach NSP konvertieren gilt:
keys.dat/prod.keys wird ben�tigt
Wie ihr die von euerer Switch erhaltet, schaut dazu hier vorbei
psxtools.de/index.php/Thread/76547

*** F�r NSP splitten gilt:
Die gesplitteten Dateien werden in einem Ordner mit fortlaufender Nummer abgelegt.
Als Bezug f�r den Ordnername, wird der aktuelle NSP Dateiname genommen und mit "splitted" erg�nzt

K�nnen nun auch direkt auf die �SD Karte via USB Reader gesplittet werden.

Das Archivbit wird automatisch gesetzt.

*** FAT32 Format:
Wenn du beim formatieren der SD Karte einen Fehler erh�lst.
(Failed to opene device) vergewissere dich, dass nichts auf die SD zugreift.
Schon alleine der ge�ffnete Windows Explorer reicht hierzu aus.

So sollte es immer gehen:
Starte FAT32 Format und stecke jetzt erst die SD Karte in Kartenleser.
Danach die SD Karte ausw�hlen und formatieren klicken.

********************************************************************************************************************************
*** �nderungshistorie
********************************************************************************************************************************

Beta v0.2.1: (25.11.2018)
Mit diesem Tool k�nnt ihr eure eigenen NSP Files f�r FAT32 SD-Karten splitten.
Damit ihr diese auf eurer Switch �ber die SD-Karte einfach installieren k�nnt.

- Es werden nur NSP Dateien >= 4GB akzeptiert.
  Alle < 4GB macht dass splitten ja auch kein Sinn! ;-)

- Die gesplitteten Dateien werden in einem Ordner mit fortlaufender Nummer abgelegt.
  Als Bezug f�r den Ordnername, wird der aktuelle NSP Dateiname genommen und mit "splitted" erg�nzt

- Das Archivbit wird automatisch gesetzt.

Beta v0.3: (26.11.2018)
- Mehrfachauswahl f�rs splitten nun m�glich

- Freier Speicherplatz wird bei jedem Titel vorher gepr�ft

Beta v0.4: (01.12.2018)
- Direktes splitten auf die SD-Karte

Beta v0.5: (12.12.2018)
- XCI teilen
- XCI zusammenf�gen
- XCI in NSP konvertieren (keys.dat erforderlich)
- FAT32 Format eingef�gt
- Update Funktion

Beta v0.5.1: (18.12.2018)
- M�glichkeit prod.keys f�r 4NXCI zu verwenden
- *please wait* Nachricht beim konvertieren von XCI nach NSP

Beta v0.6: (28.12.2018)
- Entpacke Firmware Update aus XCI
- XCI to NSP converting changes:
  - Dateiname automatisch umbenannt
  - M�glichkeit direkt f�r FAT32 zu splitten
  - M�glichkeit direkt auf USB zu splitten

********************************************************************************************************************************
*** Switch Army Knife in Betrieb nehmen
********************************************************************************************************************************

Voraussetzung:
- Windows PC
- Gedumpte keys.dat/prod.keys von deiner Switch Konsole - um deine Keys zu bekommen schaue hier -> (https://psxtools.de/index.php/Thread/76547)

7zip entpacken:
- Switch keys (keys.dat/prod.keys) im "bin" Ordner bei der 4nxci.exe ablegen
- fertig

################################################################################################################################
### ENGLISH DESCRIPTION
################################################################################################################################

********************************************************************************************************************************
*** Switch Army Knife (SAK) by kempa - December 2018
********************************************************************************************************************************

Version: beta v0.6
Published on psxtools.de

I (kempa) take no responsibility for damages/bricks of any kind.
Which can occur from XCI's or during the installation of the NSP's on the switch!
Always use your own games, which you legally own!
So you have no problems later.

*** I don't support warez !!! ***

********************************************************************************************************************************

Copyright:
The code was completely developed by me.
So the tool can be published completely free and legal!

Prerequisite for this:
The 7zip archive must not be changed
Always with reference to the original forum thread (see Support Link below)

Important notices: (included tools that are not from me):
4NXCI - The respect goes to The-4n and SciresM for developing and providing the tool.
Source: https://github.com/The-4n/4NXCI

hactool - The respect goes to SciresM for developing and providing the tool.
Quelle: https://github.com/SciresM/hactool

FAT32 Format - Thanks goes to Ridgecrop Consultants Ltd for FAT32 Format as GUI version
Source: http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm

********************************************************************************************************************************

Support: On psxtools.de (https://psxtools.de/index.php/Thread/77281)

********************************************************************************************************************************
*** Functions
********************************************************************************************************************************

With Switch Army Knife you can easily juggle XCI / NSP content from your switch.

- Split / merge XCI
- Convert XCI to NSP
- Split NSP
- Format the SD card in FAT32

*** Generally:
All files are always created in the folder of SAK.
Only XCI + NSP files >= 4GB are accepted for splitting.
All files < 4GB makes splitting no sense!

*** Split XCI:
XCI can be split in full size or trimmed.
Trimmed means that the empty space at the end will be removed.
This will saves you a lot of space for the XCI image.

The new file name will be append with "_splitted".

Can also be split directly to the ?SD card over the USB card reader.

*** Merge XCI :
Extensions.xc0 and .xci.00 are accepted

*** Converting XCI to NSP:
keys.dat / prod.keys is required
How to get the keys from your switch, look here psxtools.de/index.php/Thread/76547

*** Split NSP:
The split files are stored in a folder with a sequential number.
As reference for the folder name, the current NSP file name is taken and added with "splitted"

Can now be split directly to the ?SD card over USB card reader.

The archive bit is set automatically.

*** FAT32 Format:
If you get an error when formatting the SD card.
(Failed to open device) make sure nothing access the SD card.
Already opening the windows explorer is enough to get the error.

This is how it should always be:
Start FAT32 Format and now insert the SD card in the card reader.
Then select the SD card and format it.

********************************************************************************************************************************
*** Changelog
********************************************************************************************************************************

Beta v0.2.1: (25.11.2018)
With this tool you can split your own NSP files for FAT32 SD cards.
So you can easily install them on your switch via the SD card.

- Only NSP files >= 4GB are accepted.
  All < 4GB files makes no sense to split! ;-)

- The splitted files are stored in a folder with a sequential number.
  As reference for the folder name, the current NSP file name is taken and added with "splitted"

- The archive bit is set automatically.

Beta v0.3: (26.11.2018)
- Multiple selection for splitting is now possible

- Free space will be checked for each title

Beta v0.4: (01.12.2018)
- Directly splitting on the sd-card

Beta v0.5: (12.12.2018)
- XCI split
- XCI merge
- XCI to NSP converting (keys.dat required)
- FAT32 Format implemented
- Update feature

Beta v0.5.1: (18.12.2018)
- possibility to use prod.keys for 4NXCI
- added *please wait* message at converting XCI to NSP process

Beta v0.6: (28.12.2018)
- Extract firmware update from XCI
- XCI to NSP converting changes:
  - filename auto renaming
  - possibility to directly split for FAT32
  - possibility to directly split to USB

********************************************************************************************************************************
*** Put Switch Army Knife into operation
********************************************************************************************************************************

Requirement:
- Windows PC
- Dumped keys.dat/prod.keys from your Switch console - to get your keys look here -> (https://psxtools.de/index.php/Thread/76547)

Unzip 7zip:
- Switch keys (keys.dat/prod.keys) copy it to the "bin" dir near 4nxci.exe
- finished
