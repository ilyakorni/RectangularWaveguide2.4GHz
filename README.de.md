<p align="center">
  <a href="README.md">Русский</a> | <a href="README.en.md">English</a> | <b>Deutsch</b>
</p>

# Entwurf und 3D-Simulation eines Rechteckwellenleiters (2,4 GHz)

Dieses Projekt umfasst die analytische Berechnung geometrischer Abmessungen und die elektromagnetische 3D-Simulation eines Rechteckwellenleiters für eine Betriebsfrequenz von 2,4 GHz (Grundmode $TE_{10}$).

## Hauptparameter

| Parameter | Symbol | Wert |
| :--- | :--- | :--- |
| **Betriebsfrequenz** | $f_0$ | 2,4 GHz |
| **Breite der breiten Wand** | $a$ | 95,08 mm |
| **Breite der schmalen Wand** | $b$ | 47,54 mm |
| **Grenzwellenlänge** | $\lambda_{crit}$ | 190,16 mm |
| **Hohlleiterwellenlänge** | $\lambda_g$ | 165,67 mm |
| **VSWR bei $f_0$** | $VSWR$ | 1,215 |

## Simulationsergebnisse (CST Studio Suite)

### 3D-Modell des Rechteckwellenleiters (Material: Aluminium)
![Wellenleiter-Modell](docs/images/waveguide_3d_model.png)

### Stehwellenverhältnis (VSWR)-Diagramm
![VSWR-Diagramm](docs/images/vswr_plot.png)

### Spezifikation der Berechnungsergebnisse
![Simulationsübersicht](docs/images/simulation_results_table.png)

Bei der Frequenz $f = 2,4015 \text{ GHz}$ beträgt der simulierte VSWR-Wert **1,215**.

## Lizenz

Copyright (c) 2026 Ilya Kornilov

Dieses Quelldokument beschreibt Open Hardware (offene Hardware) und ist lizenziert unter der CERN-OHL-P v2.
Sie dürfen dieses Quelldokument weitergeben und verändern sowie darauf basierende Produkte herstellen,
gemäß den Bestimmungen der CERN-OHL-P v2 (https://cern.ch/cern-ohl).

Dieses Quelldokument wird OHNE JEGLICHE AUSDRÜCKLICHE ODER STILLSCHWEIGENDE GARANTIE verbreitet,
EINSCHLIESSLICH DER GARANTIE DER MARKTGÄNGIGKEIT, ZUFRIEDENSTELLENDEN QUALITÄT ODER EIGNUNG
FÜR EINEN BESTIMMTEN ZWECK. Bitte lesen Sie die CERN-OHL-P v2 für detaillierte Bedingungen.
