### **Node-List Länder:**

**id:**
= Ländernamen
Eu-Länder; Türkei

**einwohner:**
= Anzahl Einwohner/innen (Angabe in Millionen)

**bip:**
= BIP/Kopf 2020 (Angabe in USD)

**Lage innerhalb der EU → lage:**
1 - EU-Außengrenze
2 - EU-Inland

**Lage am Mittelmeer → meer:**

1 - ja
2 - nein

**Neuansiedlungszusagen 2020 → zusage:**

0-6.000 Zusagen

**Nimmt Geflüchtete auf (in % zu Einwohnerzahl) → aufnahme:**

1 - wenig 
2 - mittel
3 - viel
→ Wenig, mittel, viel muss noch definiert werden.

### Node-List NGO´s:

**Name der NGO → id:**

Jugend rettet, Louise Michel, Mediterranea Saving Humans, Mission Lifeline, Proactiva Open Arms, Salvamento Marìtimo Humanitario, Sea-Eye, Sea-Watch, SOS Méditerrandée

→ nur NGO´s die zuständig sind im zentralen Mittelmeer

**Gründung → start:**

2015-2020

**Anzahl der Schiffe → schiffe:**

1-4

**Mitarbeitende → mitarbeiter:**

vom Crewmitglied bis Management (gerundeter Mittelwert)

**Rettungseinsätze 2020 → rettungen:**

**Gerettete Personen 2020 → gerettet:**

**Aktuelle Lage → aktuell:**

1 = Schiff wurde festgesetzt

2= in Reperatur, um neue Auflagen der Regierung zu erfüllen

3= wegen Corona-Auflagen nicht im Einsatz

4 = Beschlagnahmung/Aufgegeben

5 = Verschrottung

6 = Strafverfolgung

7 = für den Einsatz in Vorbereitung, Registrierung läuft noch

8 = im Einsatz/befindet sich auf einer Mission

9 = verschenkt/an Besitzer zurückgegeben

### Edge-List:

Art der Unterstützung (gerichtet) → relationship:

1 - Geflüchtete aufnehmen
2 - leistet finanzielle Unterstützung
3 - Kontrollfunktion
4 - Schiff fährt unter Länderflagge
5 - Schiff fährt Land als Erstaufnahmeland an → Daten? evtl. noch streichen

→ zu wenig Edge-Attribute?
→ evtl. gewichtet, wenn wir Daten dazu finden
