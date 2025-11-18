---
title: "Installatie"
weight: 40
summary: "Montage, bekabeling en inbedrijfstelling"
---

De Module‑M kan op twee manieren worden aangesloten. De voorkeursoptie is aansluiten op een bestaande DSMR5‑slimme meter. Als dit niet mogelijk is, plaatst u een Carlo Gavazzi ET340‑meter.

## Hoe herken ik een DSMR5‑slimme meter?
Op elke DSMR5‑meter staat de aanduiding SMR5, ESMR5 of DSMR5. Vrijwel elke slimme meter heeft een knop om door de schermen te bladeren; aan het einde ziet u de SMR‑versie. Ontbreekt een scherm of knop, dan betreft het geen DSMR5. U kunt het typenummer ook controleren in dit overzicht: [Overzicht slimme meters](https://smartgateways.nl/overzicht-slimme-meters/).

{{< alert title="Goed om te weten" color="info" >}}
Ongeveer 30% van de Nederlandse huishoudens heeft een SMR 5.0‑meter en circa 40% een DSMR 4.x‑meter. Enerty ondersteunt uitsluitend DSMR5.
{{< /alert >}}

## Installatie met een DSMR5‑meter
1. Gebruik de meegeleverde platte RJ12‑kabel.
2. Steek de RJ12‑kabel in de Module‑M zoals hieronder weergegeven en de andere zijde in de DSMR5‑slimme meter.
3. Na korte tijd gaat het groene LED knipperen: er wordt data verzonden.

<img src="/img/module-m/Module-M_RJ12_insertion.png" alt="RJ12‑aansluiting" style="max-height:300px;">

## Installatie met een Carlo Gavazzi ET340‑meter
1. Installeer de ET340 volgens de handleiding van de fabrikant.
   - Aansluitvolgorde: netaansluiting boven, lasten onder.
2. Verbind een UTP‑kabel met de ET340 zoals hieronder weergegeven.

<img src="/img/module-m/ET340_RJ45_insertion.png" alt="UTP naar ET340 – RJ45‑aansluiting" style="max-height:300px;">

3. Monteer de Module‑M in de meterkast en sluit de UTP‑kabel van de ET340 aan op de Module‑M zoals hieronder weergegeven.

<img src="/img/module-m/Module-M&B_RJ45_insertion.png" alt="UTP naar Module‑M – RJ45‑aansluiting" style="max-height:300px;">

4. Voorzie de Module‑M van voeding via een USB‑C‑voeding (niet meegeleverd). Verbind de USB‑C‑kabel met de USB‑C‑ingang van de Module‑M. Deze bevindt zich naast de RJ12‑aansluiting voor de slimme meter.

## Module‑B
1. Monteer de Module‑B in de nabijheid van de Victron Cerbo GX of de MultiPlus‑II GX.
2. Gebruik de meegeleverde USB‑C‑kabel. Steek één zijde in de USB‑ingang van de Cerbo GX of MultiPlus‑II GX en de andere zijde in de Module‑B, zoals hieronder weergegeven.

<img src="/img/module-m/Module-B_USB-c_insertion.png" alt="USB‑C naar Module‑B – aansluiting" style="max-height:300px;">

{{< alert title="Let op" color="warning" >}}
USB‑kabels zijn gevoelig voor elektromagnetische interferentie (EMI). Bundel een overschot aan kabel niet in de behuizing van een MultiPlus‑II GX en leg USB‑kabels bij voorkeur niet parallel aan krachtkabels in dezelfde kabelgoot.
{{< /alert >}}

Na enkele seconden knippert het rode LED snel zodra er verbinding is met de GX‑unit. Het groene LED knippert wanneer er data uit de meterkast wordt ontvangen.

{{< manuals-topnav >}}


