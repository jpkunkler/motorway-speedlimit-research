# Possible Stuff
- Vor- & nachgelagerte Kanten bis zur nächsten Autobahnabfahrt (motorway_junction) oder nächsten Messpunkt einfärben
- Bundesstraßen zusätzlich analysieren

# Fragen
- Netzdichte in alle Richtungen gleich?
- Durchschnittliche Netzdichte/Netzabdeckung (avg distance between two charging points)

# additional info
- Raststätten? --> wie viele Raststätten auf Strecke und wie viele davon mit Charger?
- Wahrscheinlichkeitsverteilung für Wartezeit
- Zusätzliche Data Provider für Streckenauslastung
- TomTom Reachable Range for EV? --> Engpässe identifizieren an denen alle Nutzer auf einer Strecke mit hoher Wahrscheinlichkeit tanken müssen
- https://developer.tomtom.com/traffic-stats TomTom Traffic Stats für zusätzliche Infos auf Kanten --> Problem: Wie viele Autos nutzen TomTom Navis?


# Quellen
- http://www.mdpi.com/2032-6653/8/4/754/pdf

# Ideas
- Impact of speed limitations on the German Autobahn --> Netzwerk mit OSM Speed Limits + Netzwerk mit TomTom Traffic Info (avg. speed) --> bestimmen, zu welchem Prozentteil Straßen gemessen an ihrer relativen Geschwindigkeit betroffen wären & deren Auslastung --> Infos nötig wenn 120 kmh dann Co2 emissionen pro 100km gegenüber 160 etc.
- LKW Rastplatz Netzabdeckung --> Analyse gemäß Straßenauslastung --> wo Engpässe/Ballungsgebiete