# Kodi addon för carpc-controller
Detta addon låter dig starta carpc-controller skapad av Andrei direkt i kodi.
Plasera detta i /home/pi/.kodi/addons mappen (Eventuellt att du har en annan sökväg)

Ändra i service.py filen sökvägen till start filen som finns i Andreis carpc-controller
Ändra detta: os.system("sh /opt/carpc/startup/StartCarPC"); till rätt sökväg.

carpc-controller skall placeras i /usr/bin mappen
