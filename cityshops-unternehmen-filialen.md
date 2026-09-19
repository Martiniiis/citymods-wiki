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
- 🆔 feste Shop-IDs zur eindeutigen Verwaltung zu verwenden
- 🏷️ interne Shop-Namen zu vergeben
- 🗂️ Shops in Abteilungen zu organisieren
- 📋 Shop-Vorlagen zu speichern und anzuwenden
- 📜 Mitarbeiteraktivitäten nachzuverfolgen

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

# 🆔 Feste Shop-IDs

Seit **CityShops 2.3.0** erhält jeder Firmenshop automatisch eine eindeutige interne Shop-ID.

Beispiele:

```text
SHOP-0001
SHOP-0002
SHOP-0003
```

Die Shop-ID dient dazu, einen Shop innerhalb des Unternehmens eindeutig zu identifizieren.

Die ID bleibt gleich, wenn:

- der Shop-Name geändert wird
- der Preis geändert wird
- die Abteilung geändert wird
- die Filiale geändert wird

Wird ein Shop vollständig gelöscht und anschließend neu erstellt, erhält der neu erstellte Shop eine neue ID.

> 💡 Bereits vorhandene Firmenshops erhalten beim Update auf CityShops 2.3.0 automatisch eine feste Shop-ID.

---

# 🏷️ Interne Shop-Namen

Zusätzlich zur festen Shop-ID kann ein Firmenshop einen eigenen **internen Shop-Namen** erhalten.

Der interne Name dient der Verwaltung und muss nicht mit dem sichtbaren Namen auf dem Shopschild übereinstimmen.

Dadurch können besonders Unternehmen mit vielen Shops ihre Verkaufsstellen leichter auseinanderhalten.

### Internen Shop-Namen festlegen

```text
/company shop internalname Getränke-01
```

Anschließend klickst du das gewünschte Shopschild an.

### Beispiele

```text
Baumarkt-Holz-03
Getränke-01
Lager-Ankauf-02
```

Die internen Shop-Namen werden auch für die Verwaltung im **Business OS** verwendet.

---

# 🗂️ Abteilungen

Seit **CityShops 2.3.0** können Unternehmen ihre Shops in verschiedene Abteilungen einteilen.

Damit lassen sich große Unternehmen mit vielen unterschiedlichen Shops übersichtlicher organisieren.

Beispiele für mögliche Abteilungen:

- Lebensmittel
- Getränke
- Werkzeuge
- Baustoffe
- Rohstoffe

---

## ➕ Abteilung erstellen

Eine neue Abteilung erstellst du mit:

```text
/company department create Getränke
```

Damit wird die Abteilung **Getränke** erstellt.

---

## 🛒 Shop einer Abteilung zuordnen

Mit:

```text
/company department assign Getränke
```

startest du die Zuordnung.

Anschließend klickst du das gewünschte Shopschild an.

Der Shop wird danach der ausgewählten Abteilung zugeordnet.

---

# 📋 Shop-Vorlagen

Mit **Shop-Vorlagen** können Einstellungen eines bestehenden Shops gespeichert und anschließend auf weitere Shops derselben Firma übertragen werden.

Das ist besonders praktisch, wenn viele Shops mit ähnlichen Einstellungen eingerichtet werden sollen.

---

## 💾 Shop-Vorlage speichern

Mit:

```text
/company template save Standard16
```

erstellst du eine neue Vorlage.

Anschließend klickst du den Shop an, dessen Einstellungen als Vorlage gespeichert werden sollen.

Eine Vorlage übernimmt:

- Ankauf oder Verkauf
- Menge pro Klick
- Preis
- Abteilung

---

## 📥 Shop-Vorlage anwenden

Mit:

```text
/company template apply Standard16
```

wählst du eine gespeicherte Vorlage aus.

Anschließend klickst du den gewünschten Zielshop an.

Die gespeicherten Einstellungen werden auf diesen Shop übertragen.

> ⚠️ Das **Item des Zielshops wird nicht geändert**. Die Vorlage übernimmt nur die gespeicherten Shop-Einstellungen.

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

Seit **CityShops 2.3.0** können Mitarbeiter über Rollen und einzelne Mitarbeiterrechte deutlich genauer verwaltet werden.

Der Firmenbesitzer besitzt automatisch sämtliche Rechte und benötigt keine zusätzliche Rolle.

---

# 👥 Mitarbeiterrollen

CityShops unterstützt **Mitarbeiterrollen**, mit denen Unternehmen ihren Mitarbeitern unterschiedliche Aufgaben innerhalb der Firmenstruktur zuweisen können.

Verfügbare Rollen:

```text
geschaeftsfuehrer
filialleiter
lagerist
einkaeufer
verkaeufer
buchhalter
pruefer
```

Eine Rolle vergibst du mit:

```text
/company role set SPIELER filialleiter
```

`SPIELER` wird durch den Minecraft-Namen des gewünschten Mitarbeiters ersetzt.

### Beispiel

```text
/company role set Spielername filialleiter
```

Die Rollenverwaltung ist außerdem in das **CityShops Business OS** integriert.

> 💡 Der Firmenbesitzer besitzt automatisch sämtliche Rechte und benötigt keine zusätzliche Mitarbeiterrolle.

---

# 🔑 Einzelne Mitarbeiterrechte

Zusätzlich zu den Mitarbeiterrollen können einzelne Rechte gezielt vergeben oder entzogen werden.

| Recht | Bedeutung |
| --- | --- |
| `shops` | Shops verwalten |
| `prices` | Preise bearbeiten |
| `stock` | Warenbestand verwalten |
| `templates` | Shop-Vorlagen speichern und anwenden |
| `departments` | Abteilungen verwalten |
| `statistics` | Firmenstatistiken ansehen |
| `activity` | Aktivitätsprotokoll ansehen |

---

## ➕ Mitarbeiterrecht vergeben

Mit:

```text
/company permission set SPIELER templates true
```

wird dem Mitarbeiter das entsprechende Recht erteilt.

### Beispiel

```text
/company permission set Spielername templates true
```

---

## ➖ Mitarbeiterrecht entziehen

Mit:

```text
/company permission set SPIELER templates false
```

wird dem Mitarbeiter das entsprechende Recht wieder entzogen.

### Beispiel

```text
/company permission set Spielername templates false
```

Damit können Unternehmen genau festlegen, welche Mitarbeiter auf bestimmte Verwaltungsfunktionen zugreifen dürfen.

---

# 📜 Aktivitätsprotokoll

Seit **CityShops 2.3.0** besitzt das Firmensystem ein Aktivitätsprotokoll.

Damit können wichtige Verwaltungsaktionen innerhalb des Unternehmens nachvollzogen werden.

Das Protokoll erfasst unter anderem:

- Shop erstellt
- Shop gelöscht
- internen Shop-Namen geändert
- Abteilung zugewiesen
- Vorlage gespeichert
- Vorlage angewendet
- Mitarbeiterrolle geändert
- Mitarbeiterrecht geändert

Das Aktivitätsprotokoll zeigt dabei unter anderem den **Ersteller, den Zeitpunkt und die ausgeführte Aktion**.

### Aktivitätsprotokoll anzeigen

```text
/company activity
```

Das Aktivitätsprotokoll ist außerdem im **Business OS** im Bereich **„Verwaltung“** sichtbar.

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

Seit **CityShops 2.3.0** besitzt das Business OS zusätzlich den neuen Bereich **„Verwaltung“**.

Dort werden angezeigt:

- 🗂️ Abteilungen
- 🆔 feste Shop-IDs
- 🏷️ interne Shop-Namen
- 📋 Shop-Vorlagen
- 📜 Mitarbeiteraktivitäten

Lange Listen innerhalb der Verwaltung können mit dem **Mausrad gescrollt** werden.

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
| `/company shop internalname <Name>` | Internen Shop-Namen festlegen |
| `/company department create <Name>` | Neue Abteilung erstellen |
| `/company department assign <Name>` | Shop einer Abteilung zuordnen |
| `/company template save <Name>` | Shop-Vorlage speichern |
| `/company template apply <Name>` | Shop-Vorlage anwenden |
| `/company activity` | Aktivitätsprotokoll anzeigen |
| `/company role set <Spieler> <Rolle>` | Mitarbeiterrolle vergeben |
| `/company permission set <Spieler> <Recht> true` | Einzelnes Mitarbeiterrecht vergeben |
| `/company permission set <Spieler> <Recht> false` | Einzelnes Mitarbeiterrecht entziehen |

---

# ⚠️ Wichtige Regeln

Beim CityShops-Firmensystem solltest du Folgendes beachten:

- Jeder Spieler kann nur **einer Firma gleichzeitig** angehören.
- Eine Firma kann **beliebig viele Shopkisten** besitzen.
- Beim Gründen werden vorhandene persönliche Shops automatisch übernommen.
- Neue Shops von Firmenmitgliedern werden automatisch der Firma zugeordnet.
- Alle Firmenshops teilen sich den Firmennamen und das Firmenkonto.
- Firmenshops erhalten automatisch eine eindeutige Shop-ID.
- Die Shop-ID bleibt bei Änderungen an Name, Preis, Abteilung oder Filiale erhalten.
- Interne Shop-Namen dienen der Verwaltung und müssen nicht dem sichtbaren Shop-Namen entsprechen.
- Shops können verschiedenen Abteilungen zugeordnet werden.
- Shop-Vorlagen können auf weitere Shops derselben Firma angewendet werden.
- Shop-Vorlagen verändern nicht das Item des Zielshops.
- Mitarbeiter können über Rollen und einzelne Rechte verwaltet werden.
- Der Firmenbesitzer besitzt automatisch sämtliche Rechte.
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
- Wurde nach `/company shop internalname` das richtige Shopschild angeklickt?
- Wurde nach `/company department assign` das richtige Shopschild angeklickt?
- Wurde beim Speichern oder Anwenden einer Shop-Vorlage der richtige Shop angeklickt?
- Wurde der Rollenname korrekt geschrieben?
- Wurde das gewünschte Mitarbeiterrecht korrekt geschrieben?

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
- 📋 **Versionen & Changelog**

---

## 🔗 Offizielle Seiten

- **[CityShops auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/cityshops)**
- **[MineBank auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/minebank)**

---

[← Admin-Shops](cityshops-admin-shops.md) | [Weiter: Kaufen & Verkaufen →](cityshops-kaufen-verkaufen.md)
