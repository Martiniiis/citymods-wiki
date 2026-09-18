<link rel="stylesheet" href="style.css">

<img src="befehle.png" alt="CityShops – Befehle" class="wiki-banner">

# ⌨️ CityShops – Befehle

Auf dieser Seite findest du die dokumentierten Befehle von **CityShops**.

Die Befehle sind nach Bereichen sortiert, damit du schnell findest, was du für Shops, Unternehmen, Bewertungen oder Statistiken benötigst.

---

# 🛒 Shop-Befehle

## 🔗 Bewertungsschild mit Shop verbinden

```text
/chestshop link
```

Startet die Verknüpfung eines persönlichen Shops mit einem `[Bewertung]`-Schild.

### Verwendung

1. Stelle ein Schild mit `[Bewertung]` auf.
2. Führe den Befehl aus.
3. Klicke deinen Shop an.
4. Klicke anschließend das Bewertungsschild an.

Danach ist das Bewertungsschild mit dem Shop verbunden.

---

## 🏷️ Shop benennen

```text
/chestshop name <Name>
```

Ermöglicht es dir, deinem eigenen Shop einen Namen zu geben.

### Beispiel

```text
/chestshop name Martiniis Markt
```

Anschließend klickst du deinen eigenen Shop an.

Der ausgewählte Shop erhält danach den angegebenen Namen.

---

## ⭐ Shop bewerten

```text
/chestshop rate <1-5>
```

Startet eine Bewertung über einen Befehl.

Die Bewertung muss zwischen **1 und 5 Sternen** liegen.

### Beispiel

```text
/chestshop rate 5
```

Anschließend klickst du den Shop an, den du bewerten möchtest.

> Eine Bewertung ist nur nach einem echten Handel möglich. Eigene Shops beziehungsweise die eigene Firma können nicht selbst bewertet werden.

---

## 📊 Eigene Handelsstatistik

```text
/chestshop stats
```

Zeigt deine persönliche Handelsstatistik an.

CityShops zeichnet bei echten Handelsvorgängen unter anderem folgende Werte auf:

- Anzahl der Transaktionen
- gehandelte Itemmenge
- Umsatz

---

## 📜 Shop-Verlauf prüfen

```text
/chestshop history
```

Dieser Befehl ist für **OP-Spieler** vorgesehen.

Nach dem Ausführen klickst du das Shopschild an, dessen Handelsverlauf du überprüfen möchtest.

CityShops speichert pro Shop die letzten:

```text
50 Handelsvorgänge
```

---

# 🏢 Unternehmens-Befehle

CityShops besitzt ein eigenes Unternehmenssystem.

Ein Unternehmen kann gemeinsame Shops besitzen und verwendet ein eigenes MineBank-Firmenkonto.

---

## 🏢 Unternehmen erstellen

```text
/company create <Name>
```

Erstellt ein neues Unternehmen und das zugehörige MineBank-Firmenkonto.

### Beispiel

```text
/company create Martiniis Markt
```

Vorhandene persönliche Shops werden beim Gründen des Unternehmens automatisch übernommen.

Neue Shops von Unternehmensmitgliedern werden anschließend automatisch dem Unternehmen zugeordnet.

---

## ✏️ Unternehmen umbenennen

```text
/company rename <Neuer Name>
```

Ändert den Namen des Unternehmens.

Geladene Firmenshop-Schilder werden dabei ebenfalls entsprechend aktualisiert.

### Beispiel

```text
/company rename City Markt
```

Diese Funktion steht dem Firmenbesitzer zur Verfügung.

---

## ℹ️ Unternehmensinformationen

```text
/company info
```

Zeigt Informationen über dein Unternehmen an.

Dazu gehören:

- Firmenname
- Anzahl der Mitarbeiter
- Firmenkontostand

---

# 👥 Mitarbeiter verwalten

## ➕ Mitarbeiter hinzufügen

```text
/company add <Spieler>
```

Fügt einen Spieler als Mitarbeiter zum Unternehmen hinzu.

Der Spieler muss dafür **online** sein.

### Beispiel

```text
/company add Spielername
```

Die Mitarbeiterverwaltung ist dem Firmenbesitzer vorbehalten.

---

## ➖ Mitarbeiter entfernen

```text
/company remove <Spieler>
```

Entfernt einen Mitarbeiter aus dem Unternehmen.

### Beispiel

```text
/company remove Spielername
```

Auch dieser Befehl gehört zur Mitarbeiterverwaltung des Firmenbesitzers.

---

## 🚪 Unternehmen verlassen

```text
/company leave
```

Mit diesem Befehl kann ein Mitarbeiter das Unternehmen verlassen.

> Der Firmenbesitzer kann sein Unternehmen nicht einfach mit `/company leave` verlassen.

---

# 🛒 Persönlichen Shop der Firma zuweisen

```text
/company claim
```

Mit diesem Befehl kannst du einen bereits vorhandenen eigenen Shop manuell deinem Unternehmen zuweisen.

Nach dem Befehl wählst du den entsprechenden Shop aus.

Das ist besonders praktisch für Shops, die bereits vor der Unternehmenszuordnung existiert haben.

---

# 💰 Firmenkonto

CityShops verwendet für Unternehmen die Firmenkonten von **MineBank**.

Damit ist das Firmenvermögen vom privaten Spielerkonto getrennt.

---

## 💵 Geld einzahlen

```text
/company deposit <Betrag>
```

Überträgt Geld von deinem persönlichen Konto auf das Firmenkonto.

### Beispiel

```text
/company deposit 5000
```

Dadurch werden:

```text
5.000
```

vom persönlichen Konto auf das Firmenkonto übertragen.

---

## 💸 Geld auszahlen

```text
/company withdraw <Betrag>
```

Zahlt Geld vom Firmenkonto aus.

### Beispiel

```text
/company withdraw 2500
```

Die Auszahlung vom Firmenkonto ist dem **Firmenbesitzer** vorbehalten.

---

# 📋 Alle dokumentierten Befehle

| Befehl | Funktion |
| --- | --- |
| `/chestshop link` | Bewertungsschild mit einem persönlichen Shop verbinden |
| `/chestshop name <Name>` | Eigenen Shop benennen |
| `/chestshop rate <1-5>` | Shop nach einem Handel bewerten |
| `/chestshop stats` | Eigene Handelsstatistik anzeigen |
| `/chestshop history` | Handelsverlauf eines Shops als OP prüfen |
| `/company create <Name>` | Unternehmen und Firmenkonto erstellen |
| `/company rename <Neuer Name>` | Unternehmen umbenennen |
| `/company info` | Unternehmensinformationen anzeigen |
| `/company add <Spieler>` | Mitarbeiter hinzufügen |
| `/company remove <Spieler>` | Mitarbeiter entfernen |
| `/company leave` | Unternehmen als Mitarbeiter verlassen |
| `/company claim` | Eigenen Shop der Firma zuweisen |
| `/company deposit <Betrag>` | Geld auf das Firmenkonto einzahlen |
| `/company withdraw <Betrag>` | Geld vom Firmenkonto auszahlen |

---

# 👤 Spieler oder Firmenbesitzer?

Nicht jeder Unternehmensbefehl besitzt dieselben Rechte.

| Funktion | Mitarbeiter | Firmenbesitzer |
| --- | ---: | ---: |
| Firmeninformationen ansehen | ✅ | ✅ |
| Firma verlassen | ✅ | — |
| Firmenkisten verwalten | ✅ | ✅ |
| Gemeinsame Shops im Shop-PC sehen | ✅ | ✅ |
| Mitarbeiter verwalten | ❌ | ✅ |
| Unternehmen umbenennen | ❌ | ✅ |
| Geld vom Firmenkonto auszahlen | ❌ | ✅ |

Weitere Einzelheiten findest du auf der Seite:

**🔐 Berechtigungen**

---

# 👑 OP-Befehle

Der ausdrücklich als OP-Befehl dokumentierte Statistikbefehl ist:

```text
/chestshop history
```

Damit kann der gespeicherte Handelsverlauf eines Shops überprüft werden.

Zusätzlich benötigen bestimmte CityShops-Funktionen OP-Rechte, beispielsweise die Registrierung von Admin-Shops.

---

# 🪧 Funktionen ohne eigenen Befehl

Nicht jede CityShops-Funktion benötigt einen Chatbefehl.

Viele Funktionen werden direkt über:

- Schilder
- Shopkisten
- Rechtsklick
- Shop-PC
- Business OS

gesteuert.

Beispielsweise werden normale Shops über ihre Schilder erstellt und anschließend mit einem Rechtsklick registriert.

---

# 🛒 Shop-Schilder

Für normale Shops werden unter anderem folgende Schildtypen verwendet:

```text
[Verkauf]
```

Alternative:

```text
[Shop]
```

Für Ankaufsshops:

```text
[Ankauf]
```

---

# 👑 Admin-Shop-Schilder

Für Admin-Verkauf:

```text
[AdminVerkauf]
```

Alternative:

```text
[AdminShop]
```

Für Admin-Ankauf:

```text
[AdminAnkauf]
```

Admin-Shops können nur von OP-Spielern registriert werden.

---

# ⭐ Bewertungsschilder

Bewertungsschilder verwenden:

```text
[Bewertung]
```

Persönliche Bewertungsschilder werden über:

```text
/chestshop link
```

mit einem Shop verbunden.

Bei einem Unternehmen kann der Firmenbesitzer das Bewertungsschild aufstellen und per Rechtsklick mit dem Unternehmen verbinden.

---

# ❤️ Spendenschilder

CityShops unterstützt außerdem Spendenschilder.

Für Spieler beziehungsweise Unternehmen:

```text
[Spende]
```

Für die Staatskasse:

```text
[AdminSpende]
```

Diese Funktionen werden über die Schilder gesteuert und benötigen keinen eigenen `/chestshop`-Befehl.

---

# 💻 Business OS

Viele erweiterte Unternehmensfunktionen werden direkt über den **Shop-PC und das Business OS** verwaltet.

Dazu gehören beispielsweise Unternehmensübersichten, Shops, Mitarbeiter, Statistiken und weitere Geschäftsbereiche.

Dadurch muss nicht jede CityShops-Funktion über einen Chatbefehl bedient werden.

---

# ❓ Befehl funktioniert nicht?

Falls ein Befehl nicht funktioniert, überprüfe:

- Ist CityShops korrekt installiert?
- Ist MineBank installiert?
- Verwendest du Minecraft 1.20.1?
- Verwendest du eine passende Forge-Version?
- Besitzt du die benötigten Rechte?
- Bist du Mitglied beziehungsweise Besitzer des richtigen Unternehmens?
- Ist der angegebene Spieler bei `/company add` online?
- Wurde der Befehl vollständig und korrekt eingegeben?
- Verwendet der Server die passende CityShops-Version?

---

# 💡 Tipp

Minecraft zeigt beim Eingeben eines Befehls verfügbare Unterbefehle und Argumente an.

Beginne beispielsweise mit:

```text
/chestshop
```

oder:

```text
/company
```

und beachte die Vorschläge im Minecraft-Chat.

Das ist besonders hilfreich, wenn du dir die genaue Schreibweise eines Befehls nicht mehr sicher bist.

---

# 📚 Weitere CityShops-Anleitungen

Weitere Informationen findest du in den anderen Bereichen der CityShops-Wiki:

- 🚀 **Installation**
- 🛒 **Shop erstellen**
- 👑 **Admin-Shops**
- 🏢 **Unternehmen & Filialen**
- 💰 **Kaufen & Verkaufen**
- 📊 **Statistiken & Bewertungen**
- ❤️ **Spendenschilder**
- 💻 **Business OS**
- 🔐 **Berechtigungen**
- ❓ **Häufige Fragen**

---

## 🔗 Offizielle Seite

[CityShops auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/cityshops)

---

[← Business OS](cityshops-business-os.md) | [Weiter: Berechtigungen →](cityshops-berechtigungen.md)
