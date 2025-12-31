# Maerklin-BR128-mSD3-Adapter
Adapterplatiene und Schallkapsel für den Einbau eines mSD3 Decoders + HLA in die Märklin BR128
Die Platine habe ich mit KiCAD Version 7.X erstellt.
Die Schallkapsel habe ich mit einer 0.4er Düse, 0.2mm Layerhöhe und 50% Infill gedruckt.

# Materialliste / BOM:
4x Widerstand 2,2 kΩ Bauform 0207 (der normale through-hole)
1x 24 Pin Steckleiste (Push-Pull) gerade mit 1,27mm Raster
1x Keramikkondensator 1206 (3216 metrisch) 1UF
1x Märklin HLA Nachrüst Set 60941
1x Märklin mSD3 oder anderer Sounddecoder mit NEM 660 Schnitstelle.
1x 15x11x3mm Lautsprecher 4-8 Ohm

# Zusammenbau
Einbauseite immer wie Bedruckung auf der Platiene.
Die Wiederstände R1, R2, R3, R4 werden mit den 4x Widerstand 2,2 kΩ Bauform 0207 bestückt.
Die NEM660 Schnittstelle wird mit der 24 Pin Steckleiste mit 1,27mm Raster bestückt.
Der Keramikkondensator 1206 mit 1UF muss auf die Pads zwischen R1 und R3

# Pufferschaltung über mSD3 SUSI
Zusätzlich benötigte Komponenten:
2x Elko mit 500 - 1000 UF und max. 8,2 x 20 mm Radial
1x Schottkydiode mit 2 A Stromfestigkeit 25V Spannungsfestigkeit (mehr geht auch)
1x Widerstand 100 Ω
Zusammenbau:
Die beiden Elkos Paralell schalten. Dann die Scotty-Diode Parelell zum Wiederstand mit der + seite der Elkos verbinden.
Einbau:
Die Pufferschaltung dann mit +UB (+) und GND (-) auf der Adapterplatiene (bei eingebauter Platiene oben) verbinden.
Alternativ kann die Pufferschaltung auch an die Kontakte für den auf der Platiene integrierten Kondensator (bei eingebauter Platiene unten) angeschlossen werden. 
Diese Lötpads sind ebenso mit +UB und GND verbunden.
