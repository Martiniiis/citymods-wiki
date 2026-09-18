<link rel="stylesheet" href="style.css">

<img src="unternehmen.png" alt="CityShops – Unternehmen & Filialen" class="wiki-banner">

# 🏢 CityShops – Unternehmen & Filialen

Mit **CityShops** kannst du nicht nur persönliche Shops betreiben, sondern ein vollständiges **Unternehmen mit gemeinsamen Shops, Mitarbeitern und Filialen** aufbauen.

Unternehmen verwenden ein gemeinsames **MineBank-Firmenkonto** und können ihre Shops zentral über das CityShops Business OS verwalten.

---

## 🧭 Unternehmen im Überblick

Ein CityShops-Unternehmen ermöglicht dir unter anderem:

- 🏢 eine eigene Firma zu gründen
- 💳 ein gemeinsames MineBank-Firmenkonto zu verwenden
- 🛒 mehrere Firmenshops zu betreiben
- 👥 Mitarbeiter aufzunehmen
- 🔐 Mitarbeiterrollen zu verwalten
- 🏬 Filialen aufzubauen
- 📜 Firmenlizenzen zu verwenden
- 📦 vorhandene persönliche Shops zu übernehmen
- 💰 Geld auf das Firmenkonto einzuzahlen
- 💵 Geld vom Firmenkonto auszuzahlen
- 💻 Unternehmen über das Business OS zu verwalten
- 📊 gemeinsame Shops im Shop-PC anzuzeigen

> 💡 Jeder Spieler kann immer nur **einer Firma gleichzeitig** angehören.

---

# 🏢 Unternehmen gründen

Eine neue Firma erstellst du mit:

```text
/company create <Name>
```

### Beispiel

```text
/company create Martiniis Market
```

Beim Erstellen wird zusammen mit der Firma ein entsprechendes **MineBank-Firmenkonto** angelegt.

Dieses Konto wird anschließend für die finanziellen Vorgänge der Firma verwendet.

---

# 💳 Das Firmenkonto

CityShops verwendet **MineBank** für die Firmenkonten.

Dadurch besitzt das Unternehmen ein eigenes Konto, das getrennt vom persönlichen Konto des Firmenbesitzers verwaltet wird.

Das Firmenkonto wird unter anderem für die Geldbewegungen der Firmenshops verwendet.

---

## 💰 Geld auf das Firmenkonto einzahlen

Mit:

```text
/company deposit <Betrag>
```

kannst du Geld von deinem persönlichen Konto auf das Firmenkonto übertragen.

### Beispiel

```text
/company deposit 5000
```

Damit werden **5000** vom persönlichen Konto auf das Firmenkonto eingezahlt.

---

## 💵 Geld vom Firmenkonto auszahlen

Der Firmenbesitzer kann mit:

```text
/company withdraw <Betrag>
```

Geld vom Firmenkonto auszahlen.

### Beispiel

```text
/company withdraw 1000
```

> 🔐 Das Auszahlen von Geld vom Firmenkonto ist eine Funktion des **Firmenbesitzers**.

---

# 📊 Firmeninformationen anzeigen

Mit:

```text
/company info
```

kannst du Informationen über deine Firma anzeigen.

Dazu gehören unter anderem:

- Firmenname
- Mitarbeiterzahl
- Firmenkontostand

So kannst du schnell überprüfen, wie deine Firma aktuell aufgestellt ist.

---

# 🏷️ Unternehmen umbenennen

Der Firmenbesitzer kann seine Firma mit:

```text
/company rename <Neuer Name>
```

umbenennen.

### Beispiel

```text
/company rename Martiniis Group
```

CityShops aktualisiert dabei auch die geladenen Shop-Schilder der Firma.

---

# 🛒 Firmenshops

Eine Firma kann **beliebig viele Shopkisten** besitzen.

Alle Shops des Unternehmens verwenden gemeinsam:

- den Firmennamen
- das MineBank-Firmenkonto
- die Firmenverwaltung

Dadurch können mehrere Shops gemeinsam unter einem Unternehmen betrieben werden.

---

# 🔄 Vorhandene Shops übernehmen

Wenn du eine Firma gründest und bereits persönliche CityShops besitzt, werden vorhandene persönliche Spielershops beim Gründen der Firma automatisch übernommen.

Dadurch musst du deine bestehenden Shops nicht komplett neu erstellen.

---

# ➕ Neue Shops von Firmenmitgliedern

Neue Shops, die von Firmenmitgliedern erstellt werden, werden automatisch der Firma zugeordnet.

Damit können mehrere Mitarbeiter am gemeinsamen Shopnetz des Unternehmens arbeiten.

Die Firmenshops verwenden anschließend das gemeinsame Firmenkonto.

---

# 📦 Persönlichen Shop manuell übernehmen

Falls ein vorhandener persönlicher Shop manuell einer Firma zugewiesen werden soll, verwendest du:

```text
/company claim
```

Anschließend klickst du den gewünschten eigenen Shop an.

CityShops weist diesen Shop danach der Firma zu.

---

# 👥 Mitarbeiter

Unternehmen können Mitarbeiter aufnehmen.

Mitarbeiter können gemeinsam am Unternehmen arbeiten und auf dafür vorgesehene Firmenfunktionen zugreifen.

---

## ➕ Mitarbeiter hinzufügen

Mit:

```text
/company add <Spieler>
```

kann der Firmenbesitzer einen Mitarbeiter hinzufügen.

### Beispiel

```text
/company add Spielername
```

Der Spieler muss dabei **online** sein.

---

## ➖ Mitarbeiter entfernen

Mit:

```text
/company remove <Spieler>
```

kann ein Mitarbeiter wieder aus der Firma entfernt werden.

### Beispiel

```text
/company remove Spielername
```

---

# 🚪 Unternehmen verlassen

Ein Mitarbeiter kann die Firma mit:

```text
/company leave
```

verlassen.

> ⚠️ Der **Firmenbesitzer** kann die eigene Firma nicht einfach über diesen Befehl verlassen.

---

# 🔐 Rechte innerhalb einer Firma

Nicht jeder Mitarbeiter besitzt automatisch dieselben Verwaltungsrechte wie der Firmenbesitzer.

Mitarbeiter können:

- Firmenkisten verwalten
- gemeinsame Shops im Shop-PC sehen
- innerhalb der vorgesehenen Firmenstruktur mitarbeiten

Bestimmte Funktionen bleiben dem Firmenbesitzer vorbehalten.

Nur der Firmenbesitzer kann:

- Mitarbeiter verwalten
- die Firma umbenennen
- Geld vom Firmenkonto auszahlen

---

# 👥 Mitarbeiterrollen

CityShops unterstützt zusätzlich **Mitarbeiterrollen**.

Damit können Unternehmen ihre Mitarbeiter innerhalb der Firmenstruktur organisieren und unterschiedliche Aufgabenbereiche abbilden.

Die Rollenverwaltung ist in das **CityShops Business OS** integriert.

> 💻 Die ausführliche Bedienung der Rollenverwaltung erklären wir separat auf der Wiki-Seite zum **Business OS**.

---

# 🏬 Filialen

CityShops unterstützt **Filialen**.

Damit können Unternehmen ihre verschiedenen Verkaufsstellen innerhalb der Firma organisieren.

Ein Unternehmen kann dadurch beispielsweise mehrere Standorte betreiben und seine Shops übersichtlicher strukturieren.

### Beispiel

Ein Unternehmen könnte seine Shops beispielsweise aufteilen in:

```text
Martiniis Market
│
├── Zentrale
├── Filiale Innenstadt
├── Filiale Bahnhof
└── Filiale Industriegebiet
```

Die Filialverwaltung ist Bestandteil des **CityShops Business OS**.

---

# 💻 Unternehmen im Business OS

Der CityShops Shop-PC dient als zentrale Verwaltungsoberfläche für das Unternehmen.

Mitarbeiter sehen dort die gemeinsamen Shops des Unternehmens.

Darüber hinaus enthält das Business OS weitere Firmenfunktionen wie:

- 🏢 Firmenverwaltung
- 🛒 Firmenshops
- 🏬 Filialen
- 👥 Mitarbeiter
- 🔐 Mitarbeiterrollen
- 📜 Firmenlizenzen
- 📊 Firmenstatistiken
- 📈 Marktberichte
- 🏭 Produktionsanalyse

> 💡 Die komplette Bedienung des Shop-PCs und des Business OS findest du auf der separaten Wiki-Seite **Business OS**.

---

# 📜 Firmenlizenzen

CityShops unterstützt **kombinierbare Firmenlizenzen**.

Diese Lizenzen gehören zum erweiterten Unternehmenssystem und können innerhalb des Business OS verwaltet werden.

Lizenzkäufe werden über das **MineBank-Firmenkonto** bezahlt.

Damit bleiben persönliche Finanzen und Firmenausgaben sauber voneinander getrennt.

---

# 📦 Lieferverträge

CityShops enthält außerdem **Lieferverträge** als Bestandteil des erweiterten Firmen- und Wirtschaftssystems.

Diese erweitern die Möglichkeiten für Unternehmen über die normalen Shopfunktionen hinaus.

Weitere Verwaltungsfunktionen dazu können über die entsprechenden Bereiche des Business OS genutzt werden.

---

# ⭐ Firmenbewertungen

CityShops unterstützt Bewertungen nicht nur für einzelne persönliche Shops, sondern auch für Unternehmen.

Ein Unternehmen kann mit einem entsprechenden **Bewertungsschild** verbunden werden.

Die genaue Einrichtung und Verwendung erklären wir separat unter:

**📊 Statistiken & Bewertungen**

---

# 💰 Geldfluss bei Firmenshops

Firmenshops verwenden das gemeinsame Firmenkonto.

Bei einem **Verkaufsshop** gehen die Einnahmen auf das zugehörige Firmenkonto.

Bei einem **Ankaufsshop** wird die Bezahlung über das Firmenkonto abgewickelt.

Dadurch laufen die Geschäfte des Unternehmens nicht über die privaten Konten der einzelnen Mitarbeiter.

---

# 📋 Firmenbefehle im Überblick

| Befehl | Funktion |
| --- | --- |
| `/company create <Name>` | Neue Firma und MineBank-Firmenkonto erstellen |
| `/company rename <Neuer Name>` | Firma umbenennen |
| `/company info` | Firmeninformationen anzeigen |
| `/company add <Spieler>` | Online-Spieler als Mitarbeiter hinzufügen |
| `/company remove <Spieler>` | Mitarbeiter entfernen |
| `/company leave` | Firma als Mitarbeiter verlassen |
| `/company claim` | Eigenen Shop manuell der Firma zuweisen |
| `/company deposit <Betrag>` | Privates Geld auf das Firmenkonto einzahlen |
| `/company withdraw <Betrag>` | Als Firmenbesitzer Geld vom Firmenkonto auszahlen |

---

# ⚠️ Wichtige Regeln

Beim CityShops-Firmensystem solltest du Folgendes beachten:

- Jeder Spieler kann nur **einer Firma gleichzeitig** angehören.
- Eine Firma kann **beliebig viele Shopkisten** besitzen.
- Beim Gründen werden vorhandene persönliche Shops automatisch übernommen.
- Neue Shops von Firmenmitgliedern werden automatisch der Firma zugeordnet.
- Alle Firmenshops teilen sich den Firmennamen und das Firmenkonto.
- Mitarbeiter können Firmenkisten verwalten.
- Mitarbeiter können gemeinsame Shops im Shop-PC sehen.
- Nur der Firmenbesitzer kann Mitarbeiter verwalten.
- Nur der Firmenbesitzer kann die Firma umbenennen.
- Nur der Firmenbesitzer kann Geld vom Firmenkonto auszahlen.
- Der Firmenbesitzer kann die Firma nicht einfach mit `/company leave` verlassen.

---

# ❓ Unternehmen funktioniert nicht?

Falls eine Firmenfunktion nicht wie erwartet funktioniert, überprüfe zunächst:

- Ist **CityShops** korrekt installiert?
- Ist **MineBank** korrekt installiert?
- Besitzt du bereits eine Firma?
- Gehörst du möglicherweise bereits einer anderen Firma an?
- Ist der Spieler beim Hinzufügen eines Mitarbeiters online?
- Bist du der Firmenbesitzer, wenn du eine Besitzerfunktion verwendest?
- Besitzt das Firmenkonto ausreichend Guthaben?
- Gehört der gewünschte Shop bereits einer Firma?
- Wurde bei `/company claim` anschließend der richtige Shop angeklickt?

---

# 📚 Weitere CityShops-Anleitungen

Weitere Funktionen findest du in den anderen Bereichen der CityShops-Wiki:

- 🛒 **Shop erstellen**
- 👑 **Admin-Shops**
- 💰 **Kaufen & Verkaufen**
- 📊 **Statistiken & Bewertungen**
- ❤️ **Spendenschilder**
- 💻 **Business OS**
- ⌨️ **Befehle**
- 🔐 **Berechtigungen**
- ❓ **Häufige Fragen**

---

## 🔗 Offizielle Seiten

- **[CityShops auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/cityshops)**
- **[MineBank auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/minebank)**

---

[← Admin-Shops](cityshops-admin-shops.md) | [Weiter: Kaufen & Verkaufen →](cityshops-kaufen-verkaufen.md)
