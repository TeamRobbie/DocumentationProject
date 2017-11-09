# Initieel verslag Nieuwpoort 9/11/17 TeamRobbie

## Opdracht
We maken een robot/voertuig dat een raceparcour zo snel mogelijk autonoom kan afleggen.
Het parcour bestaat uit een zwarte baan afgebakend met volle witte lijnen, in het midden van deze baan is er een witte stippelijn.
Op het parcour bevinden zich RFID tags die we zullen moeten scannen.
Voor dit te realiseren maken we gebruik van een Arduino om te prototypen en ontwerpen we daarna een custom board.
Uiteindelijk zullen we ook nog communicatie voorzien tussen de Arduino en een Raspberry Pi d.m.v. Bluetooth.
Deze RPI zal dan over Wi-Fi gegevens van ons voertuig versturen naar een server.

## Afspraken
+ Gebruik maken van Eagle voor PCB-design voor meer toegang tot libraries
+ Communicatie tussen Arduino en RPI via bluetooth doen (alternatief Wi-Fi moeilijk te programmeren in het geval van enterprise-netwerk Odisee)

## Opzoekwerk, planning en algemene idee�n
+ Soorten sensoren opzoeken (infra-rood sensoren voor wit/zwart detectie)
+ Mogelijkheden voor line tracking opzoeken => PID-regeltechniek gebruiken om de lijn zo
nauwkeurig mogelijk te volgen
+ DC motor speed measurement-technieken opzoeken (Hall-sensor)?
+ Arduino-PCB-design modulair opbouwen om te kunnen testen
+ RFID-readers bekijken => voorzien dat we ID van start/finish kunnen opslaan zodat we weten wanneer we een lap gecomplete hebben
+ Eventueel mogelijkheden bekijken om sensoren van andere wagentjes te storen (lage prioriteit)
+ Youtube, instructables, arduino-forum,... gebruiken voor info op te zoeken

## Prioriteiten planning
+ Zeker op tijd beginnen aan PCB-design 