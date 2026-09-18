<link rel="stylesheet" href="style.css">

<img src="spenden.png" alt="CityShops – Spendenschilder" class="wiki-banner">


# ❤️ CityShops – Spendenschilder

Mit den **Spendenschildern** erweitert CityShops das Wirtschaftssystem um eine einfache Möglichkeit, Geld an Unternehmen oder die Staatskasse zu spenden.

CityShops unterscheidet dabei zwischen zwei Arten von Spendenschildern:

| Spendenschild | Ziel |
| --- | --- |
| ❤️ `[Spende]` | Spende an ein Unternehmen |
| 🏛️ `[AdminSpende]` | Spende an die Staatskasse |

Die Geldverwaltung erfolgt über **MineBank**.

---

# ❤️ Firmenspende

Mit einem Firmenspendenschild können Spieler ein Unternehmen finanziell unterstützen.

Dafür wird ein Schild mit:

```text
[Spende]
```

verwendet.

Das Spendenschild gehört zum CityShops-Firmensystem und ermöglicht Spenden zugunsten eines Unternehmens.

---

## 🏢 Wohin geht das Geld?

Eine Firmenspende ist mit dem Wirtschaftssystem des Unternehmens verbunden.

CityShops verwendet für Unternehmen die über MineBank verwalteten **Firmenkonten**.

Dadurch bleiben private Spielerkonten und das Firmenvermögen voneinander getrennt.

---

# 🏛️ Staatliche Spenden

Neben Firmenspenden unterstützt CityShops auch Spenden an den Staat.

Dafür gibt es das Schild:

```text
[AdminSpende]
```

Diese Variante ist für die **MineBank-Staatskasse** vorgesehen.

---

## 💰 Die Staatskasse

Die Staatskasse wird von CityShops auch für andere wirtschaftliche Funktionen verwendet.

Beispielsweise:

- Admin-Verkaufsshops zahlen Einnahmen in die Staatskasse ein.
- Admin-Ankaufsshops bezahlen Spieler aus der Staatskasse.
- `[AdminSpende]` ermöglicht zusätzlich staatliche Spenden.

Damit können verschiedene Bereiche der Serverwirtschaft über eine gemeinsame Staatskasse laufen.

---

# 🔄 Unterschied der Spendenschilder

| Funktion | `[Spende]` | `[AdminSpende]` |
| --- | --- | --- |
| ❤️ Spenden möglich | ✅ | ✅ |
| 🏢 Für Unternehmen | ✅ | ❌ |
| 🏛️ Für die Staatskasse | ❌ | ✅ |
| 🏦 MineBank-Integration | ✅ | ✅ |

---

# 🏦 MineBank-Integration

CityShops verwendet **MineBank** als Pflichtabhängigkeit für sein Geldsystem.

MineBank stellt unter anderem die Konten bereit, die CityShops für seine Wirtschaftsfunktionen verwendet.

Dazu gehören:

- 👤 Spielerkonten
- 🏢 Firmenkonten
- 🏛️ Staatskasse

Dadurch sind die Spendenschilder direkt in die bestehende CityShops-Wirtschaft integriert.

> 💡 MineBank ist eine externe Pflichtabhängigkeit und kein Bestandteil der CityMods.

---

# 🏢 Spendenschilder und Unternehmen

Das normale:

```text
[Spende]
```

ist Teil des erweiterten Firmensystems von CityShops.

Dadurch können Unternehmen neben ihren normalen Einnahmen aus Shops zusätzliche finanzielle Unterstützung erhalten.

Das kann beispielsweise für serverinterne Projekte oder gemeinschaftlich finanzierte Vorhaben eines Unternehmens verwendet werden.

---

# 🏛️ Spendenschilder für Serverbetreiber

Mit:

```text
[AdminSpende]
```

steht Serverbetreibern eine getrennte Variante für die Staatskasse zur Verfügung.

Dadurch müssen staatliche Spenden nicht über einen normalen Spielershop oder ein Unternehmen abgewickelt werden.

Die staatliche Wirtschaft bleibt damit vom normalen Firmenvermögen getrennt.

---

# 🔐 Wirtschaftssystem

Die Spendenschilder verwenden das vorhandene CityShops- und MineBank-System.

Dadurch werden die verschiedenen Geldbereiche klar voneinander getrennt:

```text
Spieler
   │
   ├── [Spende]
   │      ↓
   │   Unternehmen
   │      ↓
   │   Firmenkonto
   │
   └── [AdminSpende]
          ↓
       Staatskasse
```

---

# ❓ Welche Variante brauche ich?

Wenn Spieler ein **Unternehmen unterstützen** sollen, verwendest du:

```text
[Spende]
```

Wenn Spieler Geld an die **Staatskasse** geben sollen, verwendest du:

```text
[AdminSpende]
```

---

# ⚠️ Voraussetzungen

Damit das Spendensystem verwendet werden kann, müssen die für CityShops benötigten Mods korrekt installiert sein.

Dazu gehören:

- Minecraft 1.20.1
- Minecraft Forge
- CityShops
- MineBank

CityShops und MineBank müssen entsprechend der CityShops-Installation auf Server und Client vorhanden sein.

---

# 💡 Ideen für den Server

Spendenschilder können an unterschiedlichen Stellen einer Stadt eingesetzt werden.

Beispiele:

- ❤️ Unterstützung eines Unternehmens
- 🏗️ Finanzierung gemeinsamer Firmenprojekte
- 🏛️ Unterstützung der Staatskasse
- 🏙️ Spendenbereiche in öffentlichen Gebäuden

So können Spendenschilder sichtbar in die Wirtschaft und das Stadtleben eines Servers eingebaut werden.

---

# ❓ Spende funktioniert nicht?

Überprüfe zuerst:

- Ist CityShops korrekt installiert?
- Ist MineBank installiert?
- Ist das richtige Spendenschild verwendet worden?
- Soll die Spende an ein Unternehmen oder an die Staatskasse gehen?
- Ist das Unternehmen beziehungsweise das benötigte Konto vorhanden?
- Verwenden Server und Client die passenden Mod-Versionen?

Bei Firmenspenden muss:

```text
[Spende]
```

verwendet werden.

Bei staatlichen Spenden muss:

```text
[AdminSpende]
```

verwendet werden.

---

# 📚 Weitere CityShops-Anleitungen

Weitere Informationen findest du in den anderen Bereichen der CityShops-Wiki:

- 🛒 **Shop erstellen**
- 👑 **Admin-Shops**
- 🏢 **Unternehmen & Filialen**
- 💰 **Kaufen & Verkaufen**
- 📊 **Statistiken & Bewertungen**
- 💻 **Business OS**
- ⌨️ **Befehle**
- 🔐 **Berechtigungen**
- ❓ **Häufige Fragen**

---

## 🔗 Offizielle Seite

[CityShops auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/cityshops)

---

[← Statistiken & Bewertungen](cityshops-statistiken-bewertungen.md) | [Weiter: Business OS →](cityshops-business-os.md)
