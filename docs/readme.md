# Examonbrowser – handleiding voor eindgebruikers (ChatGpt generated)

Examonbrowser is een Windows-toepassing om sneller examonbeelden te bekijken, te beoordelen en waar nodig te rapporteren. U kunt per kandidaat alle vastgelegde momentopnames (snapshots), klembordactiviteiten en procesinformatie raadplegen, snel filteren op relevante gebeurtenissen en een rapport genereren.


Wat u nodig hebt
- Windows 10 of 11
- Toegang tot de Examon-omgeving met de juiste rechten
- Een stabiele internetverbinding (voor het laden van sessies). De app gebruikt ook lokale caching om sneller te werken


Snelstart
1) Start het programma en ga naar het startscherm met sessies.
2) Zoek of selecteer een kandidaat/sessie in de lijst links.
3) Bekijk rechts de details: info, aantal anomalieën en de tijdlijn met gebeurtenissen.
4) Open snapshots door erop te klikken om de details te zien.
5) Gebruik filters (alleen klembord, alleen processen, minimale tekstlengte) om ruis te verminderen.
6) Genereer indien nodig een rapport via de knop Rapport generator.


Overzicht van het hoofdscherm
- Bovenbalk
  - Terug naar startscherm (sessies): navigeert terug naar het overzicht.
  - Legende/handleiding: opent een korte uitleg over iconen en kleuren.
  - Rapport generator: maakt een rapport aan voor de huidige selectie.
  - Vergelijk (2): vergelijk twee geselecteerde sessies naast elkaar.
- Linkerpaneel (sessies)
  - Zoeken: filtert de lijst met sessies/kandidaten.
  - Lijst met sessies: elke rij toont
    - Een gekleurd bolletje met het aantal anomalieën
    - De naam/omschrijving van de sessie
    - Een 📋-badge met het aantal snapshots met klembordinhoud
    - Een film-icoon om beschikbare schermopname(s) te openen (indien aanwezig)
- Rechterpaneel (details)
  - Info: korte samenvatting van de geselecteerde sessie
  - Anomalieën: totaal aantal gevonden afwijkingen
  - Filterbalk:
    - Only clipboardevents: toon alleen snapshots met klembordactiviteit
    - Minimale lengte: Alle, ≥ kort (20+), ≥ medium (1000+), ≥ lang (5000+)
    - Only processes: toon alleen proces-/toepassingsgebeurtenissen (metadata)
    - Sortering: wissel tussen recentste eerst of oudste eerst
  - Snapshots-overzicht: miniaturen met tijdstip. Klik om te openen; zweven over een rood/oranje tekstlabel toont volledige klembord- of metadata-inhoud
  - Tijdlijn: visueel overzicht van de sessie met markeringen voor belangrijke gebeurtenissen. Klik op een marker om naar het bijbehorende snapshot te gaan


Werken met sessies
- Selecteren: klik één sessie om details te bekijken. Meerdere selecties zijn mogelijk voor vergelijken.
- Zoeken: typ in het vak Zoeken om snel kandidaten of sessies te vinden.
- Vergelijken: selecteer twee sessies in de lijst en klik Vergelijk (2).


Kleuren en iconen (legende)
- Gekleurde cirkel + getal: aantal anomalieën (kleur geeft ernst/waarschuwing aan)
- 📋-badge: aantal snapshots met klembordinhoud in de sessie
- Rood label in snapshot: klembordinhoud aanwezig (klik/hover voor details)
- Oranje label in snapshot: proces/metadata-informatie aanwezig (klik/hover voor details)


Rapportage
- Klik Rapport generator om een samenvattend rapport te maken van de geselecteerde sessie.
- Volg de aanwijzingen op het scherm om het rapport op te slaan en te delen volgens uw procedure.


Tijdlijn gebruiken
- De tijdlijn toont de hele sessieduur met markeringen voor kopieeracties en andere gebeurtenissen.
- Klik een marker om het corresponderende snapshot te openen.


Cache en offline gedrag
- De statusbalk onderaan toont de cache-status. De applicatie bewaart lokaal gegevens om sneller te kunnen werken.
- Bij verbindingsproblemen kan een sessie nog deels zichtbaar zijn dankzij caching. Voor de meest recente informatie is een internetverbinding nodig.


Probleemoplossing
- Geen sessies zichtbaar
  - Controleer netwerkverbinding en uw rechten binnen de Examon-omgeving
- Geen miniaturen of weinig resultaten
  - Controleer of filters (Only clipboardevents/Only processes/minimale lengte) niet te strikt zijn
- Vergelijkknop blijft grijs
  - Zorg dat precies twee sessies geselecteerd zijn
- Rapport kan niet worden opgeslagen
  - Controleer schijfruimte en bestandsrechten op de gekozen locatie


Privacy en veiligheid
- Verwerk sessiegegevens uitsluitend voor toetsing en toezicht binnen uw organisatiebeleid.
- Deel rapporten en gegevens volgens de geldende privacyrichtlijnen en bewaartermijnen.

