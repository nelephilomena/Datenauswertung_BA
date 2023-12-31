# Datenauswertung

Das Respository Datenauswertung enthält den Datensatz und die Funktionen, um die Daten auszuwerten 
und zu analysieren. Der Datensatz besteht aus Positionsdaten von Versuchen mit Fischen, die in der Nähe der One Tree Islands gesammelt wurden. Diese Fische wurden in kreisrunde Becken untersucht. Alle 30 Sekunden wurde deren Positionsdaten aufgenommen und in Tabellen festgehalten.

## Funktionen
CircStat2012a
- circ_ang2rad           -> Winkel von Winkelmaß in Bogenmaß
- circ_rad2ang           -> Winkel von Bogenmaß in Winkelmaß
- circ_mean              -> Zirkulärer Mittelwert in Winkelmaß
- circ_r                 -> Durchschnittliche Resultantlänge
- circ_rtest             -> Rayleigh Test </p>
P. Berens, CircStat: A Matlab Toolbox for Circular Statistics, Journal of Statistical Software, Volume 31, Issue 10, 2009
http://www.jstatsoft.org/v31/i10

Eigene Funktionen
- find_ind_files         -> Finden der Indexe für die Datein von allen Versuchen mit diesem Fisch
- find_ind_group         -> Finden der Indexe für die Datein von allen Versuchen mit der Fischgruppe
- plot_daten             -> Plot der Schwimmbewegung der Fischen über die Zeit
- read_tab_group         -> Einlesen der Tabellen mit den Positionen (x,y) der Fischgruppen
- read_tab_single_phi    -> Einlesen der Tabelle mit allen Positionswinkel von allen einzelnen Fischen
- read_tab_single_xy     -> Einlesen der Tabellen mit den Positionen (x,y) der einzelnen Fischen

## Skript
main_datenauswertung     -> Auswertung der Daten der Versuche mit einzelnen Fischen und Fischgruppen

## Daten
### Dodos
- 'Dodos_angles_all_Gabi.xlsx'
  - Tabelle mit den Winkeln in den Spalten pro Beobachtungszeitpunkt 
  - Für jeden Versuch und für alle einzeln geteste Fische der Art 
- '4.D.G2.3_47B.3D11D12D13D14.3.xlsx'
  - 215 einzelne Tabellen mit den x- und y-Werten der Positionen der Fische 
  für jeden Beobachtungszeitpunkt
  - Jeweils die ersten x- und y-Werte geben das Zentrum des Beckens an
  - Nicht vollständig (nicht für jeden Versuch von einem Fisch vorhanden)

### Fischgruppen
- 49 Tabellen mit jeweils den x-und y-Werten der Positionen der Fischgruppe
  - Es lassen sich nicht die Datenpunkte exakt einem Fisch zuordnen 
     aufgrund der Zeit zwischen den Beobachtungszeitpunkten
  - Jeweils die ersten x- und y-Werte geben das Zentrum des Beckens an

##
Nele Schuff
18.12.2023















