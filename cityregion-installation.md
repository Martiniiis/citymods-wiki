<link rel="stylesheet" href="style.css">

<img src="cittyinstall.png" alt="CityRegion – Installation" class="wiki-banner">

# 🚀 CityRegion installieren 

Diese Anleitung erklärt die Installation von **CityRegion 2.1.0** für Minecraft 1.20.1 mit Forge.

---

## 📦 Voraussetzungen

Für CityRegion werden folgende Komponenten benötigt:

| Komponente | Benötigte Version |
|---|---:|
| Minecraft | 1.20.1 |
| Forge | 47.4.10 oder neuer innerhalb 1.20.1 |
| CityRegion | 2.1.0 |
| MineBank / BankMod | 1.0.2 oder neuer |
| WorldEdit | Optional |

> ⚠️ **Wichtig:**  
> MineBank ist eine Pflichtabhängigkeit von CityRegion.  
> Ohne MineBank startet CityRegion nicht.

WorldEdit ist **nicht erforderlich**. CityRegion besitzt eine eigene Zwei-Punkte-Auswahl zum Erstellen von Regionen.

---

## 🖥️ Installation

CityRegion wird auf **Client und Server** installiert.

### 1. Forge installieren

Installiere Minecraft **1.20.1** mit einer passenden Forge-Version.

Empfohlen wird:

```text
Forge 47.4.10 oder neuer innerhalb Minecraft 1.20.1
```

---

### 2. MineBank installieren

Lege **MineBank 1.0.2 oder neuer** in den `mods`-Ordner.

Beispiel:

```text
.minecraft/
└── mods/
    └── MineBank-1.0.2.jar
```

Auf einem Server gehört MineBank ebenfalls in den dortigen `mods`-Ordner.

---

### 3. CityRegion installieren

Lege anschließend die CityRegion-JAR in denselben `mods`-Ordner.

Für CityRegion 2.1.0:

```text
cityregion-2.1.0-forge-1.20.1.jar
```

Beispiel:

```text
.minecraft/
└── mods/
    ├── MineBank-1.0.2.jar
    └── cityregion-2.1.0-forge-1.20.1.jar
```

> ⚠️ Achte darauf, dass sich **nur eine CityRegion-Version** im `mods`-Ordner befindet.

Eine alte und eine neue CityRegion-JAR dürfen nicht gleichzeitig installiert sein.

---

## 🌍 Optional: WorldEdit

CityRegion kann auch zusammen mit **WorldEdit** verwendet werden.

Ist WorldEdit installiert, kann eine vorhandene WorldEdit-Auswahl mit folgendem Befehl übernommen werden:

```text
/cityregion worldedit
```

WorldEdit ist jedoch **keine Pflichtabhängigkeit**.

Ohne WorldEdit können Regionen mit der integrierten CityRegion-Auswahl erstellt werden:

```text
/cityregion pos1
/cityregion pos2
```

---

## 🔄 CityRegion aktualisieren

Vor einem Update sollte immer ein Backup erstellt werden.

### Update durchführen

1. Server beziehungsweise Minecraft vollständig beenden.
2. Backup der Welt und CityRegion-Daten erstellen.
3. Alte CityRegion-JAR aus dem `mods`-Ordner entfernen.
4. Neue CityRegion-JAR in den `mods`-Ordner kopieren.
5. Prüfen, ob MineBank weiterhin in der benötigten Version installiert ist.
6. Server beziehungsweise Minecraft starten.
7. Funktionen nach dem Update testen.

> ⚠️ **Nicht einfach mehrere CityRegion-Versionen gleichzeitig im `mods`-Ordner lassen.**

---

## 💾 Backup vor einem Update

Vor jedem CityRegion-Update sollten mindestens folgende Daten gesichert werden:

- kompletter Weltordner
- `data/cityregion_regions.dat`
- CityRegion-Rücksetzungsdaten
- CityRegion-Abhollagerdaten
- MineBank-Daten

Dadurch können wichtige Grundstücks-, Eigentümer-, Miet- und Finanzdaten bei Problemen wiederhergestellt werden.

---

## ✅ Nach der Installation testen

Nach dem ersten Start sollte geprüft werden, ob CityRegion korrekt geladen wurde.

Als Administrator kann beispielsweise eine Auswahl erstellt werden:

```text
/cityregion pos1
/cityregion pos2
```

Anschließend kann die Auswahl überprüft werden:

```text
/cityregion selection
```

Optional kann die grafische Vorschau aktiviert werden:

```text
/cityregion preview
```

Wenn beide Auswahlpunkte gesetzt wurden, kann eine Testregion erstellt werden:

```text
/cityregion create Testgrundstück
```

---

## 🏦 MineBank prüfen

Da CityRegion MineBank für Zahlungen und die staatliche Finanzverwaltung verwendet, sollte auch MineBank korrekt geladen sein.

Der eigene Kontostand kann mit folgendem Befehl geprüft werden:

```text
/regionmoney
```

Administratoren können für Tests oder Verwaltungszwecke Geld vergeben:

```text
/regionmoney give <Spieler> <Betrag>
```

---

## ❗ Häufige Installationsprobleme

### CityRegion startet nicht

Prüfe:

- Ist Minecraft 1.20.1 installiert?
- Wird eine passende Forge-Version verwendet?
- Ist MineBank 1.0.2 oder neuer installiert?
- Befinden sich CityRegion und MineBank im `mods`-Ordner?
- Befindet sich nur **eine** CityRegion-JAR im Ordner?

---

### MineBank-Abhängigkeitsfehler

CityRegion 2.1.0 benötigt:

```text
MineBank / BankMod 1.0.2 oder neuer
```

Eine fehlende oder zu alte MineBank-Version kann verhindern, dass CityRegion geladen wird.

---

### WorldEdit fehlt

Das ist kein Fehler.

WorldEdit ist optional und wird für CityRegion nicht zwingend benötigt.

Verwende stattdessen:

```text
/cityregion pos1
/cityregion pos2
```

---

## 🧪 Nach einem Update testen

Nach einem CityRegion-Update sollten mindestens folgende Systeme einmal überprüft werden:

- Grundstück erstellen
- Grundstück kaufen
- Grundstück verkaufen
- Vermietung
- Mietverlängerung
- Grundstücksschilder
- Mitglieder und Rechte
- Auktionen
- Staatskasse
- Rückgabe an den Staat
- Abhollager
- Real Estate OS
- vollständiger Serverneustart

---

[← Zurück zu CityRegion](cityregion.md) | [Weiter: Grundstücke erstellen & schützen →](cityregion-grundstuecke.md)
