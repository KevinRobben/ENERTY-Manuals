# Handleiding Module‑M en Module‑B

## Veiligheidsinstructies

{{< alert title="Waarschuwing" color="warning" >}}
Deze aanwijzingen zijn uitsluitend bedoeld voor gekwalificeerd personeel.

De installatie van Enerty‑producten vindt vaak plaats in de nabijheid van elektrische installaties zoals meterkasten, batterijen en omvormers. Volg altijd de instructies van de betreffende fabrikant wanneer een Enerty‑product hiermee wordt verbonden. Houd u te allen tijde aan de geldende normen, zoals NEN 1010.
{{< /alert >}}

## Beschrijving
Module‑M staat voor meterkastmodule, Module‑B staat voor batterijmodule. De letters M en B geven dus de locatie aan waar elk apparaat geplaatst moet worden.

## LED‑indicaties
Op elke module zijn twee LED‑indicatoren aanwezig:

- Rood: activiteit op een van de bekabelde verbindingen (zenden/ontvangen).
- Groen: activiteit op de draadloze verbinding tussen Module‑M en Module‑B.

![Rood LED – bedrade communicatie](/img/manuals/module-m/Module-M&B_red_light.png)
![Groen LED – draadloze link](/img/manuals/module-m/Module-M&B_green_light.png)

## Draadloze verbinding
De draadloze verbinding is met obstakels betrouwbaar getest tot circa 150 m (bijvoorbeeld op een bedrijventerrein). In open veld, met directe zichtlijn tussen de twee modules, is een afstand tot circa 700 m mogelijk.

Richtwaarden voor wat doorgaans haalbaar is:

- 3 verdiepingsvloeren, of
- 5 stenen muren, of
- 1 damwand/stalen wand.

Moet de verbinding grotere afstanden of meer obstakels overbruggen? Test dit dan vooraf met een set Module‑M en Module‑B. Plaats de Module‑M in de slimme meter en voorzie de Module‑B van voeding via een laptop of powerbank. Wanneer het groene LED niet langer regelmatig knippert, bevindt u zich buiten het betrouwbare bereik.

## Bediening
Elke module heeft één drukknop. Deze is tijdens de installatie niet nodig. Lang indrukken zet de module in firmware‑updatemodus. Om deze modus te verlaten, onderbreekt u kort de voedingsspanning (power‑cycle).

## Installatie

### Module‑M
De Module‑M kan op twee manieren worden aangesloten. De voorkeursoptie is aansluiten op een bestaande DSMR5‑slimme meter. Als dit niet mogelijk is, plaatst u een Carlo Gavazzi ET340‑meter.

#### Hoe herken ik een DSMR5‑slimme meter?
Op elke DSMR5‑meter staat de aanduiding SMR5, ESMR5 of DSMR5. Vrijwel elke slimme meter heeft een knop om door de schermen te bladeren; aan het einde ziet u de SMR‑versie. Ontbreekt een scherm of knop, dan betreft het geen DSMR5. U kunt het typenummer ook controleren in dit overzicht: [Overzicht slimme meters](https://smartgateways.nl/overzicht-slimme-meters/).

{{< alert title="Goed om te weten" color="info" >}}
Ongeveer 30% van de Nederlandse huishoudens heeft een SMR 5.0‑meter en circa 40% een DSMR 4.x‑meter. Enerty ondersteunt uitsluitend DSMR5.
{{< /alert >}}

#### Installatie met een DSMR5‑meter
1. Gebruik de meegeleverde platte RJ12‑kabel.
2. Steek de RJ12‑kabel in de Module‑M `zoals hieronder weergegeven en de andere zijde in de DSMR5‑slimme meter.
3. Na korte tijd gaat het groene LED knipperen: er wordt data verzonden.
![RJ12‑aansluiting](/img/manuals/module-m/Module-M_RJ12_insertion.png)

#### Installatie met een Carlo Gavazzi ET340‑meter
1. Installeer de ET340 volgens de handleiding van de fabrikant.
   - Aansluitvolgorde: netaansluiting boven, lasten onder.
2. Verbind een UTP‑kabel met de ET340 zoals hieronder weergegeven.

![UTP naar ET340 – RJ45‑aansluiting](/img/manuals/module-m/ET340_RJ45_insertion.png)

3. Monteer de Module‑M in de meterkast en sluit de UTP‑kabel van de ET340 aan op de Module‑M zoals hieronder weergegeven.

![UTP naar Module‑M – RJ45‑aansluiting](/img/manuals/module-m/Module-M&B_RJ45_insertion.png)

4. Voorzie de Module‑M van voeding via een van de volgende opties:
   - RJ12‑kabel naar een DSMR4.x‑meter om voeding te leveren.
     {{< alert title="Let op" color="warning" >}}Dit werkt niet met DSMR2‑ of DSMR3‑meters.{{< /alert >}}
   - Een USB‑C‑voeding (niet meegeleverd). Verbind een USB‑C‑kabel met de USB‑C‑ingang van de Module‑M. Deze bevindt zich naast de RJ12‑aansluiting voor de slimme meter.

### Module‑B
1. Monteer de Module‑B in de nabijheid van de Victron Cerbo GX of de MultiPlus‑II GX.
2. Gebruik de meegeleverde USB‑C‑kabel. Steek één zijde in de USB‑ingang van de Cerbo GX of MultiPlus‑II GX en de andere zijde in de Module‑B, zoals hieronder weergegeven.

![USB‑C naar Module‑B – aansluiting](/img/manuals/module-m/Module-B_USB-c_insertion.png)

{{< alert title="Let op" color="warning" >}}
USB‑kabels zijn gevoelig voor elektromagnetische interferentie (EMI). Bundel een overschot aan kabel niet in de behuizing van een MultiPlus‑II GX en leg USB‑kabels bij voorkeur niet parallel aan krachtkabels in dezelfde kabelgoot.
{{< /alert >}}

Na enkele seconden knippert het rode LED snel zodra er verbinding is met de GX‑unit. Het groene LED knippert wanneer er data uit de meterkast wordt ontvangen.

## Configuratie
Niet van toepassing voor Module‑M.