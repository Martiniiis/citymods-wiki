<link rel="stylesheet" href="style.css">

<img src="immobilienwerte.png" alt="CityRegion – Immobilienarten & Immobilienwerte" class="wiki-banner">

# 🏷️ Immobilienarten & Immobilienwerte

CityRegion kann Grundstücke und Gebäude nach ihrer Nutzung einordnen und mit verschiedenen Immobilienwerten versehen.

Dadurch können Wohnhäuser, Gewerbeflächen, Industriegebiete, Lager, Bauland und Gemeinschaftsflächen voneinander unterschieden werden.

Zusätzlich können Lagefaktor, Gebäudewert, Richtwert, letzter Verkaufspreis und Markttrend einer Immobilie verwaltet und im **Real Estate OS** angezeigt werden.

---

## 🏷️ Immobilienarten

Administratoren können einer CityRegion eine Immobilienart zuweisen.

Zur Verfügung stehen:

- 🏠 Wohnen
- 🏪 Gewerbe
- 🏭 Industrie
- 📦 Lager
- 🏗️ Bauland
- 👥 Gemeinschaftsfläche

Die Immobilienart beschreibt, wofür ein Grundstück oder Gebäude vorgesehen ist.

---

# 🏠 Wohnen

Die Immobilienart **Wohnen** eignet sich für private Wohnimmobilien.

Beispiele:

- Einfamilienhäuser
- Mehrfamilienhäuser
- Wohnungen
- Apartments
- Wohnanlagen
- Mietwohnungen

Bei größeren Gebäuden können einzelne Wohnungen als Unterregionen angelegt werden.

Beispiel:

```text
Wohnhaus-A
├── Wohnung-01
├── Wohnung-02
├── Wohnung-03
└── Gemeinschaftsbereich
```

---

# 🏪 Gewerbe

Die Immobilienart **Gewerbe** ist für geschäftlich genutzte Immobilien vorgesehen.

Beispiele:

- Geschäfte
- Supermärkte
- Restaurants
- Büros
- Autohäuser
- Werkstätten
- Firmenzentralen
- Verkaufsflächen

Gewerbeimmobilien können zusätzlich einer CityShops-Firma beziehungsweise Filiale zugeordnet werden.

CityShops bleibt dabei eine separate Mod und ist keine Pflichtabhängigkeit von CityRegion.

---

# 🏭 Industrie

Die Immobilienart **Industrie** eignet sich für größere industrielle Flächen.

Beispiele:

- Fabriken
- Produktionshallen
- Industrieanlagen
- Logistikzentren
- große Werkstätten
- Betriebsgelände

Dadurch können Industriegrundstücke getrennt von normalen Wohn- und Gewerbeimmobilien verwaltet werden.

---

# 📦 Lager

Die Immobilienart **Lager** kann für reine Lagerflächen verwendet werden.

Beispiele:

- Lagerhallen
- Firmenlager
- Warenlager
- Containerflächen
- Logistiklager
- kleinere Lagerräume

Auch Lagerbereiche können als eigene Unterregionen innerhalb größerer Gebäude angelegt werden.

---

# 🏗️ Bauland

Die Immobilienart **Bauland** eignet sich für Grundstücke, auf denen noch gebaut werden soll.

Beispiele:

```text
Unbebautes Grundstück
        ↓
      Bauland
        ↓
    Bauprojekt
        ↓
fertige Immobilie
```

Dadurch können Grundstücke bereits verkauft oder verwaltet werden, bevor das eigentliche Gebäude fertiggestellt wurde.

---

# 👥 Gemeinschaftsfläche

Die Immobilienart **Gemeinschaftsfläche** eignet sich für Bereiche, die von mehreren Spielern beziehungsweise Bewohnern genutzt werden sollen.

Beispiele:

- Treppenhäuser
- Eingangsbereiche
- Innenhöfe
- Gemeinschaftsräume
- Flure
- öffentliche Gebäudebereiche

Gemeinschaftsbereiche können zusätzlich mit:

```text
/cityregion common true
```

als solche markiert werden.

Zum Entfernen:

```text
/cityregion common false
```

---

# 📈 Immobilienwerte

CityRegion kann verschiedene Informationen verwenden, um den Wert einer Immobilie darzustellen.

Dazu gehören:

- Grundstücksfläche
- Lagefaktor
- Gebäudewert
- Richtwert
- letzter Verkaufspreis
- Markttrend

Diese Werte können unter anderem im **Real Estate OS** angezeigt werden.

---

# 📐 Grundstücksfläche

Die Größe einer Region ist ein wichtiger Bestandteil der Immobilieninformationen.

CityRegion kennt für jede Region:

- Breite
- Höhe
- Tiefe
- gesamte Blockanzahl

Die Blockanzahl ergibt sich aus:

```text
Breite × Höhe × Tiefe
```

Beispiel:

```text
50 × 10 × 40 = 20.000 Blöcke
```

Eine einzelne CityRegion darf maximal:

```text
500.000 Blöcke
```

umfassen.

---

# 📍 Lagefaktor

Administratoren können für Immobilien einen **Lagefaktor** festlegen.

Damit kann berücksichtigt werden, dass Grundstücke an unterschiedlichen Standorten verschieden wertvoll sein können.

Beispielsweise könnte eine Immobilie:

- im Stadtzentrum
- am Stadtrand
- in einem Gewerbegebiet
- in einem Industriegebiet
- in einer besonders gefragten Lage

unterschiedlich bewertet werden.

Der Lagefaktor kann in die Immobilienbewertung einfließen.

---

## 💡 Beispiel für unterschiedliche Lagen

```text
Innenstadt
Lagefaktor: hoch

Wohngebiet
Lagefaktor: normal

Stadtrand
Lagefaktor: niedriger
```

Damit können zwei gleich große Grundstücke unterschiedliche Immobilienwerte besitzen.

---

# 🏢 Gebäudewert

Zusätzlich zum Grundstück kann ein eigener **Gebäudewert** festgelegt werden.

Dadurch kann berücksichtigt werden, dass ein bebautes Grundstück einen anderen Wert besitzt als eine unbebaute Fläche.

Beispiel:

```text
Grundstück
+
Gebäude
+
Lage
=
Immobilienbewertung
```

Ein großes fertig eingerichtetes Gebäude kann dadurch einen höheren Immobilienwert besitzen als ein gleich großes unbebautes Grundstück.

---

# 💰 Richtwert

CityRegion kann für Immobilien einen aktuellen Richtwert darstellen.

Der Richtwert dient als Orientierung für den Wert einer Immobilie.

Dabei können vorhandene Informationen wie beispielsweise:

- Grundstücksgröße
- Lagefaktor
- Gebäudewert

berücksichtigt werden.

Der Richtwert ist nicht zwingend identisch mit dem tatsächlichen Verkaufspreis.

Ein Eigentümer kann eine Immobilie beispielsweise zu einem anderen Preis verkaufen.

---

# 🧾 Letzter Verkaufspreis

CityRegion speichert den letzten Verkaufspreis einer Immobilie.

Dadurch kann später nachvollzogen werden, zu welchem Preis die Immobilie zuletzt gehandelt wurde.

Beispiel:

```text
Richtwert:            125.000
Letzter Verkauf:      118.000
```

Diese Informationen können bei der Einschätzung einer Immobilie helfen.

---

# 📊 Markttrend

CityRegion kann einen Markttrend für Immobilien darstellen.

Der Trend kann zeigen, ob sich der Immobilienwert beziehungsweise die vorhandenen Marktdaten entwickeln als:

```text
↑ steigend
↓ fallend
→ stabil
```

Diese Informationen können im Real Estate OS zusammen mit weiteren Immobiliendaten angezeigt werden.

---

# 📜 Vergangene Verkäufe

Das Real Estate OS kann Informationen über vergangene Immobilienverkäufe anzeigen.

Dadurch können Spieler und Administratoren nachvollziehen, wie sich eine Immobilie beziehungsweise deren Verkaufspreise entwickelt haben.

Mögliche Informationen sind beispielsweise:

```text
Immobilie: Wohnhaus-A

Richtwert:          125.000
Letzter Verkauf:    118.000
Markttrend:         steigend
```

---

# 💻 Immobilienwerte im Real Estate OS

Das **Real Estate OS** ist die zentrale Immobilienverwaltung von CityRegion.

Dort können unter anderem folgende Informationen angezeigt werden:

- Immobilienstatus
- Eigentümer
- Mieter
- Immobilienart
- Immobilienwert
- Markttrend
- vergangene Verkäufe
- Gebäude
- Wohnungen
- Mietverträge
- Auktionen

Dadurch befinden sich wichtige Informationen zu einer Immobilie an einer zentralen Stelle.

---

# 🧑‍💼 Immobilienmakler

Auch der Immobilienmakler greift auf die Immobilieninformationen von CityRegion zu.

Spieler können über den Makler:

- verfügbare Immobilien suchen
- eigene Immobilien anzeigen
- gemietete Immobilien anzeigen
- Immobilien besichtigen
- das Real Estate OS öffnen
- Immobilieninformationen einsehen

Dadurch können Immobilien nicht nur direkt am Grundstück, sondern auch zentral gesucht und verglichen werden.

---

# 🏗️ Bauphase

Zusätzlich zur Immobilienart kann für eine Immobilie eine Bauphase beziehungsweise ein Bauzustand verwaltet werden.

Dadurch können beispielsweise Grundstücke unterschieden werden, die:

- noch unbebaut sind
- sich in einer Bauphase befinden
- bereits fertiggestellt wurden

Die Bauphase kann ebenfalls in der Immobilienverwaltung berücksichtigt werden.

---

# 🔒 Nur zur Vermietung

Immobilien können so eingestellt werden, dass sie ausschließlich als Mietobjekt verwendet werden.

Dadurch können Serverbetreiber beispielsweise Wohnungen oder staatliche Immobilien anbieten, die nicht dauerhaft gekauft werden sollen.

Das ist besonders praktisch für:

- Mietwohnungen
- Apartments
- Gewerbemietflächen
- staatliche Immobilien

---

# 🏪 Gewerbeimmobilien und CityShops

Gewerbeimmobilien können optional einer CityShops-Firma beziehungsweise Filiale zugeordnet werden.

Dadurch kann eine Immobilie beispielsweise mit einem bestehenden Unternehmen verbunden werden.

Beispiel:

```text
Immobilie:
Hauptstraße-Shop-01

Immobilienart:
Gewerbe

Firma:
Martiniiiis Markt

Filiale:
Innenstadt
```

CityRegion funktioniert jedoch weiterhin unabhängig von CityShops.

> CityShops ist für die normale Verwendung von CityRegion nicht erforderlich.

---

# 🏛️ Staatliche Immobilien

Auch staatliche Grundstücke können Immobilienarten und Immobilienwerte besitzen.

Dadurch kann der Staat unterschiedliche Arten von Immobilien anbieten.

Beispiele:

```text
Staatliches Bauland
Staatliche Mietwohnung
Staatliche Gewerbefläche
Staatliches Lager
```

Bei staatlichen Verkäufen und Vermietungen werden die entsprechenden Einnahmen über MineBank an die Staatskasse übertragen.

---

# 🔄 Eigentümerwechsel

Bei einem privaten Verkauf bleiben Gebäude und Inhalte der Immobilie bestehen.

Der neue Eigentümer übernimmt die vorhandene Immobilie.

Die gespeicherten Immobilieninformationen können dadurch weiterhin zur Region gehören.

Bei einer Rückgabe an den Staat kann dagegen der gespeicherte Ursprungszustand wiederhergestellt werden.

---

# 🔎 Immobilieninformationen prüfen

Informationen zur Region am aktuellen Standort können mit folgendem Befehl angezeigt werden:

```text
/cityregion info
```

Damit kann geprüft werden, welche CityRegion an der aktuellen Position vorhanden ist.

Weitere Immobilieninformationen können über das **Real Estate OS** eingesehen werden.

---

# 📊 Beispiel einer Immobilienbewertung

Eine Gewerbeimmobilie könnte beispielsweise folgende Informationen besitzen:

```text
Name:                 CityShop-Innenstadt
Immobilienart:        Gewerbe
Grundstücksfläche:    25.000 Blöcke
Lagefaktor:           1,25
Gebäudewert:          80.000
Richtwert:            145.000
Letzter Verkauf:      132.500
Markttrend:           steigend
```

Eine andere Immobilie kann trotz ähnlicher Größe einen anderen Wert besitzen, wenn Lagefaktor oder Gebäudewert unterschiedlich sind.

---

# 🏙️ Beispiel verschiedener Immobilienarten

Eine Stadt könnte beispielsweise so organisiert werden:

```text
Innenstadt
├── Wohnhaus-A             → Wohnen
├── Wohnhaus-B             → Wohnen
├── CityShop-01            → Gewerbe
├── Restaurant-01          → Gewerbe
└── Rathausplatz           → Gemeinschaftsfläche

Industriegebiet
├── Fabrik-01              → Industrie
├── Lagerhalle-01          → Lager
└── Grundstück-Industrie-3 → Bauland

Wohngebiet
├── Einfamilienhaus-01     → Wohnen
├── Einfamilienhaus-02     → Wohnen
└── Spielplatz             → Gemeinschaftsfläche
```

Dadurch können unterschiedliche Bereiche einer Stadt sauber voneinander getrennt und verwaltet werden.

---

# ❗ Häufige Fragen

## Muss jede Immobilie eine Immobilienart besitzen?

Die Immobilienarten dienen der besseren Einordnung und Verwaltung von Grundstücken.

Administratoren können damit festlegen, für welchen Zweck eine Immobilie vorgesehen ist.

---

## Ist der Richtwert automatisch der Verkaufspreis?

Nein.

Der Richtwert dient als Immobilienbewertung beziehungsweise Orientierung.

Der tatsächliche Verkaufspreis kann davon abweichen.

---

## Warum haben zwei gleich große Grundstücke unterschiedliche Werte?

Neben der Größe können weitere Informationen wie:

- Lagefaktor
- Gebäudewert
- bisherige Immobilieninformationen

eine Rolle spielen.

Dadurch müssen gleich große Grundstücke nicht automatisch denselben Wert besitzen.

---

## Kann eine Gewerbeimmobilie ohne CityShops verwendet werden?

Ja.

CityRegion funktioniert unabhängig von CityShops.

Die Firmen- beziehungsweise Filialzuordnung ist eine zusätzliche Möglichkeit für Server, auf denen CityShops ebenfalls verwendet wird.

---

## Kann eine Wohnung einen eigenen Wert besitzen?

Eine Wohnung ist eine eigene Unterregion und kann innerhalb des CityRegion-Systems getrennt verwaltet werden.

Dadurch können Wohnungen innerhalb eines größeren Gebäudes als eigene Immobilienbereiche behandelt werden.

---

# 💡 Beispiel: Neue Gewerbeimmobilie vorbereiten

### 1. Region erstellen

```text
/cityregion pos1
/cityregion pos2
/cityregion selection
/cityregion preview
/cityregion create Gewerbe-01
```

### 2. Immobilieninformationen festlegen

Der Administrator kann anschließend die entsprechenden Immobilieninformationen wie:

- Immobilienart
- Lagefaktor
- Gebäudewert
- Bauphase
- Mietstatus

über die dafür vorgesehenen CityRegion-Adminfunktionen verwalten.

### 3. Real Estate OS prüfen

Anschließend können die hinterlegten Immobilieninformationen über das Real Estate OS kontrolliert werden.

### 4. Immobilie anbieten

Je nach gewünschter Verwendung kann die Immobilie anschließend:

- verkauft
- vermietet
- versteigert
- als reine Mietimmobilie geführt
- oder optional einer CityShops-Firma zugeordnet

werden.

---

[← Zurück: Gebäude & Wohnungen](cityregion-gebaeude-wohnungen.md) | [Weiter: Immobilienauktionen →](cityregion-auktionen.md)
