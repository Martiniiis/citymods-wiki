<link rel="stylesheet" href="style.css">

<img src="berechtigung.png" alt="CityShops – Berechtigungen" class="wiki-banner">

# 🔐 CityShops – Berechtigungen

CityShops unterscheidet zwischen verschiedenen Rollen und Zugriffsrechten.

Dadurch können normale Spieler ihre eigenen Shops verwalten, Mitarbeiter gemeinsam in einem Unternehmen arbeiten und Firmenbesitzer wichtige Unternehmensfunktionen kontrollieren.

Seit **CityShops 2.3.0** können Mitarbeiter zusätzlich über feste Mitarbeiterrollen und einzelne Berechtigungen gezielt für bestimmte Unternehmensaufgaben freigeschaltet werden.

Bestimmte Verwaltungsfunktionen sind ausschließlich für **Server-Administratoren beziehungsweise OP-Spieler** vorgesehen.

---

# 👥 Rollen im Überblick

In CityShops sind vor allem folgende Rollen wichtig:

| Rolle | Beschreibung |
| --- | --- |
| 👤 Spieler | Verwaltet seine eigenen Shops und handelt bei anderen Shops |
| 👥 Mitarbeiter | Arbeitet zusätzlich in einem Unternehmen und dessen Shops |
| 👑 Firmenbesitzer | Verwaltet das Unternehmen, Mitarbeiter und wichtige Firmenfunktionen |
| 🛡️ Admin / OP | Besitzt Zugriff auf administrative CityShops-Funktionen |

> Ein Spieler kann gleichzeitig Besitzer seiner persönlichen Shops und Mitarbeiter eines Unternehmens sein.

Innerhalb eines Unternehmens können Mitarbeiter seit CityShops 2.3.0 zusätzlich eine eigene **Mitarbeiterrolle** erhalten.

---

# 👤 Normale Spieler

Jeder normale Spieler kann das grundlegende Shopsystem von CityShops verwenden.

Dazu gehören insbesondere:

- eigene Verkaufsshops erstellen
- eigene Ankaufsshops erstellen
- eigene Shops verwalten
- Waren kaufen
- Waren verkaufen
- eigene Shops benennen
- eigene Handelsstatistiken ansehen
- andere Shops nach einem echten Handel bewerten
- Bewertungsschilder für eigene Shops verwenden
- Spendenschilder verwenden

---

# 🛒 Eigene Shops

Ein normaler Spieler darf grundsätzlich nur seine **eigenen Shops** verwalten.

Dazu gehören beispielsweise Shops mit:

```text
[Verkauf]
```

oder:

```text
[Shop]
```

sowie Ankaufsshops mit:

```text
[Ankauf]
```

Die zugehörige Shopkiste und das Shopschild bilden gemeinsam den Shop.

---

# 🔒 Fremde Shops

Ein Spieler erhält durch CityShops nicht automatisch Verwaltungsrechte für Shops anderer Spieler.

Dadurch soll verhindert werden, dass fremde Spieler:

- Shop-Einstellungen verändern
- Shops übernehmen
- geschützte Shop-Inhalte verwalten
- fremde Unternehmensfunktionen benutzen

Die Besitzverhältnisse eines Shops bestimmen, wer ihn verwalten darf.

---

# 👥 Mitarbeiter eines Unternehmens

Wird ein Spieler zu einem Unternehmen hinzugefügt, erhält er Zugriff auf die für Mitarbeiter vorgesehenen Unternehmensfunktionen.

Ein Mitarbeiter kann dadurch gemeinsam mit anderen Spielern innerhalb eines Unternehmens arbeiten.

Seit **CityShops 2.3.0** können die Möglichkeiten eines Mitarbeiters genauer über:

- Mitarbeiterrollen
- einzelne Mitarbeiterrechte

festgelegt werden.

Dadurch muss nicht mehr jeder Mitarbeiter automatisch dieselben Verwaltungsrechte besitzen.

---

# 🏢 Gemeinsame Unternehmensshops

Unternehmensmitglieder können mit den Shops ihres Unternehmens arbeiten, sofern sie die dafür benötigten Rechte besitzen.

Neue Shops von Unternehmensmitgliedern können dem Unternehmen zugeordnet werden.

Bereits vorhandene persönliche Shops können über:

```text
/company claim
```

dem Unternehmen zugewiesen werden.

---

# 💻 Business OS für Mitarbeiter

Mitarbeiter können das **Business OS** beziehungsweise die Unternehmensbereiche des Shop-PCs verwenden, soweit die jeweilige Funktion für ihre Rolle beziehungsweise ihre Berechtigungen vorgesehen ist.

Dadurch können Unternehmensinformationen zentral eingesehen und gemeinsame Geschäftsbereiche verwendet werden.

Seit CityShops 2.3.0 enthält das Business OS zusätzlich den Bereich **„Verwaltung“**.

Dort können abhängig von den vorhandenen Rechten unter anderem folgende Bereiche verwendet beziehungsweise eingesehen werden:

- Abteilungen
- feste Shop-IDs
- interne Shop-Namen
- Shop-Vorlagen
- Mitarbeiteraktivitäten

---

# 🚪 Unternehmen verlassen

Ein normaler Mitarbeiter kann das Unternehmen mit:

```text
/company leave
```

verlassen.

Der Firmenbesitzer selbst kann sein Unternehmen nicht einfach über diesen Mitarbeiter-Befehl verlassen.

---

# 👑 Firmenbesitzer

Der Firmenbesitzer besitzt zusätzliche Verwaltungsrechte.

Er trägt die Verantwortung für die zentrale Verwaltung seines Unternehmens.

Dazu gehören insbesondere:

- Mitarbeiter hinzufügen
- Mitarbeiter entfernen
- Unternehmen umbenennen
- Firmeninformationen verwalten
- Unternehmensshops verwalten
- vorhandene Shops dem Unternehmen zuweisen
- Firmenkonto verwalten
- Geld vom Firmenkonto auszahlen
- Mitarbeiterrollen verwalten
- einzelne Mitarbeiterrechte verwalten
- Abteilungen verwalten
- Shop-Vorlagen verwenden
- Aktivitätsprotokoll einsehen
- Unternehmensbereiche im Business OS verwalten

> 💡 Der Firmenbesitzer besitzt automatisch sämtliche Unternehmensrechte und benötigt keine zusätzliche Mitarbeiterrolle.

---

# ➕ Mitarbeiter hinzufügen

Der Firmenbesitzer kann einen Spieler mit:

```text
/company add <Spieler>
```

zum Unternehmen hinzufügen.

### Beispiel

```text
/company add Spielername
```

Der entsprechende Spieler muss dafür online sein.

---

# ➖ Mitarbeiter entfernen

Mit:

```text
/company remove <Spieler>
```

kann der Firmenbesitzer einen Mitarbeiter aus seinem Unternehmen entfernen.

### Beispiel

```text
/company remove Spielername
```

---

# ✏️ Unternehmen umbenennen

Der Firmenbesitzer kann sein Unternehmen mit:

```text
/company rename <Neuer Name>
```

umbenennen.

### Beispiel

```text
/company rename City Markt
```

---

# 👥 Mitarbeiterrollen

Seit **CityShops 2.3.0** können Mitarbeitern feste Rollen innerhalb des Unternehmens zugewiesen werden.

Dadurch können verschiedene Aufgabenbereiche innerhalb einer Firma übersichtlicher organisiert werden.

Folgende Rollen stehen zur Verfügung:

| Rolle | Rollenname |
| --- | --- |
| Geschäftsführer | `geschaeftsfuehrer` |
| Filialleiter | `filialleiter` |
| Lagerist | `lagerist` |
| Einkäufer | `einkaeufer` |
| Verkäufer | `verkaeufer` |
| Buchhalter | `buchhalter` |
| Prüfer | `pruefer` |

---

## 🏷️ Mitarbeiterrolle vergeben

Eine Rolle wird mit folgendem Befehl vergeben:

```text
/company role set SPIELER filialleiter
```

### Beispiel

```text
/company role set Spielername filialleiter
```

Damit erhält der Mitarbeiter die entsprechende Rolle innerhalb des Unternehmens.

> 💡 Der Firmenbesitzer selbst benötigt keine Rolle, da er automatisch sämtliche Rechte besitzt.

---

# 🔑 Einzelne Mitarbeiterrechte

Zusätzlich zu den Mitarbeiterrollen unterstützt CityShops 2.3.0 **einzelne Berechtigungen**.

Damit kann genauer festgelegt werden, auf welche Unternehmensfunktionen ein Mitarbeiter zugreifen darf.

Folgende Rechte stehen zur Verfügung:

| Recht | Funktion |
| --- | --- |
| `shops` | Shops verwalten |
| `prices` | Preise bearbeiten |
| `stock` | Warenbestand verwalten |
| `templates` | Shop-Vorlagen speichern und anwenden |
| `departments` | Abteilungen verwalten |
| `statistics` | Firmenstatistiken ansehen |
| `activity` | Aktivitätsprotokoll ansehen |

---

## ✅ Einzelnes Recht vergeben

Mit:

```text
/company permission set SPIELER templates true
```

kann einem Mitarbeiter ein bestimmtes Recht gegeben werden.

### Beispiel

```text
/company permission set Spielername templates true
```

Damit erhält `Spielername` das Recht:

```text
templates
```

und kann die dafür vorgesehenen Funktionen verwenden.

---

## ❌ Einzelnes Recht entziehen

Ein Recht kann wieder entzogen werden mit:

```text
/company permission set SPIELER templates false
```

### Beispiel

```text
/company permission set Spielername templates false
```

Danach besitzt der Mitarbeiter dieses einzelne Recht nicht mehr.

---

# 🧩 Rollen und einzelne Rechte

Mitarbeiterrollen und einzelne Berechtigungen ermöglichen eine genauere Aufgabenverteilung innerhalb eines Unternehmens.

Beispielsweise kann ein Mitarbeiter eine bestimmte Rolle besitzen und zusätzlich gezielt für einzelne Funktionen freigeschaltet werden.

Dadurch können Unternehmen ihre Mitarbeiter passend zu ihren Aufgaben einsetzen, ohne jedem Mitarbeiter vollständigen Zugriff auf sämtliche Verwaltungsfunktionen zu geben.

Der Firmenbesitzer besitzt unabhängig davon automatisch alle Unternehmensrechte.

---

# 🛒 Shop-Verwaltung

Das Recht:

```text
shops
```

betrifft die Verwaltung von Unternehmensshops.

Damit kann der Zugriff auf die Shopverwaltung gezielt gesteuert werden.

---

# 💵 Preise bearbeiten

Das Recht:

```text
prices
```

betrifft die Bearbeitung von Shoppreisen.

Dadurch kann ein Mitarbeiter beispielsweise Zugriff auf die Preisverwaltung erhalten, ohne automatisch sämtliche anderen Unternehmensfunktionen verwenden zu können.

---

# 📦 Warenbestand verwalten

Das Recht:

```text
stock
```

betrifft die Verwaltung des Warenbestands.

Damit kann der Zugriff auf die Bestandsverwaltung getrennt von anderen Unternehmensrechten gesteuert werden.

---

# 📋 Shop-Vorlagen

Das Recht:

```text
templates
```

erlaubt die Verwendung der Shop-Vorlagen.

Shop-Vorlagen können mit:

```text
/company template save Standard16
```

gespeichert und mit:

```text
/company template apply Standard16
```

auf einen anderen Shop derselben Firma angewendet werden.

Eine Vorlage speichert:

- Ankauf oder Verkauf
- Menge pro Klick
- Preis
- Abteilung

> ⚠️ Das Item des Zielshops wird durch eine Shop-Vorlage nicht verändert.

---

# 🗂️ Abteilungen

Das Recht:

```text
departments
```

betrifft die Verwaltung der Unternehmensabteilungen.

Eine Abteilung kann beispielsweise mit:

```text
/company department create Getränke
```

erstellt werden.

Mit:

```text
/company department assign Getränke
```

kann anschließend ein Shop der entsprechenden Abteilung zugeordnet werden.

---

# 📊 Firmenstatistiken

Das Recht:

```text
statistics
```

erlaubt den Zugriff auf die dafür vorgesehenen Firmenstatistiken.

Dadurch können beispielsweise Mitarbeiter mit entsprechenden Aufgaben Zugriff auf wirtschaftliche Auswertungen erhalten.

---

# 📜 Aktivitätsprotokoll

Das Recht:

```text
activity
```

erlaubt den Zugriff auf das Aktivitätsprotokoll des Unternehmens.

Das Protokoll kann mit:

```text
/company activity
```

aufgerufen werden.

Es ist außerdem im Business OS unter **„Verwaltung“** verfügbar.

Dort können unter anderem folgende Aktionen nachvollzogen werden:

- Shop erstellt
- Shop gelöscht
- internen Shop-Namen geändert
- Abteilung zugewiesen
- Vorlage gespeichert
- Vorlage angewendet
- Mitarbeiterrolle geändert
- Mitarbeiterrecht geändert

Das Aktivitätsprotokoll enthält Informationen über **Ersteller, Zeitpunkt und Aktion**.

---

# 🆔 Feste Shop-IDs

Firmenshops erhalten seit CityShops 2.3.0 automatisch eine eindeutige Shop-ID.

Beispiele:

```text
SHOP-0001
SHOP-0002
SHOP-0003
```

Die Shop-ID wird automatisch vergeben und benötigt kein eigenes Mitarbeiterrecht zur Vergabe.

Sie bleibt erhalten, wenn beispielsweise der Name, Preis, die Abteilung oder Filiale eines Shops geändert wird.

---

# 🏷️ Interne Shop-Namen

Firmenshops können zusätzlich einen internen Shop-Namen erhalten.

Dafür wird verwendet:

```text
/company shop internalname Getränke-01
```

Anschließend wird der gewünschte Shop angeklickt.

Der interne Name dient der besseren Verwaltung innerhalb des Unternehmens und kann beispielsweise im Business OS verwendet werden.

---

# 💰 Firmenkonto

Unternehmen verwenden ein eigenes Firmenkonto über **MineBank**.

Dadurch werden:

- privates Spielergeld
- Firmenvermögen

voneinander getrennt.

MineBank ist eine **externe Abhängigkeit** von CityShops und kein Bestandteil der CityMods.

---

# 💵 Geld einzahlen

Geld kann mit:

```text
/company deposit <Betrag>
```

auf das Firmenkonto eingezahlt werden.

### Beispiel

```text
/company deposit 5000
```

Dadurch werden 5.000 vom persönlichen Konto auf das Firmenkonto übertragen.

---

# 💸 Geld auszahlen

Für Auszahlungen wird:

```text
/company withdraw <Betrag>
```

verwendet.

### Beispiel

```text
/company withdraw 2500
```

Die Auszahlung vom Firmenkonto ist dem **Firmenbesitzer** vorbehalten.

Dadurch können normale Mitarbeiter nicht einfach Firmenvermögen vom Konto auszahlen.

---

# 📊 Rollenübersicht

| Funktion | Spieler | Mitarbeiter | Firmenbesitzer | Admin / OP |
| --- | :---: | :---: | :---: | :---: |
| Eigene Shops erstellen | ✅ | ✅ | ✅ | ✅ |
| Eigene Shops verwalten | ✅ | ✅ | ✅ | ✅ |
| Bei Shops kaufen | ✅ | ✅ | ✅ | ✅ |
| Bei Shops verkaufen | ✅ | ✅ | ✅ | ✅ |
| Shops bewerten | ✅ | ✅ | ✅ | ✅ |
| Eigene Statistiken ansehen | ✅ | ✅ | ✅ | ✅ |
| Unternehmensfunktionen verwenden | ❌ | abhängig von Rechten | ✅ | ✅ |
| Unternehmensshops verwalten | ❌ | abhängig von `shops` | ✅ | ✅ |
| Shoppreise bearbeiten | ❌ | abhängig von `prices` | ✅ | ✅ |
| Warenbestand verwalten | ❌ | abhängig von `stock` | ✅ | ✅ |
| Shop-Vorlagen verwenden | ❌ | abhängig von `templates` | ✅ | ✅ |
| Abteilungen verwalten | ❌ | abhängig von `departments` | ✅ | ✅ |
| Firmenstatistiken ansehen | ❌ | abhängig von `statistics` | ✅ | ✅ |
| Aktivitätsprotokoll ansehen | ❌ | abhängig von `activity` | ✅ | ✅ |
| Unternehmen umbenennen | ❌ | ❌ | ✅ | ✅ |
| Mitarbeiter hinzufügen | ❌ | ❌ | ✅ | ✅ |
| Mitarbeiter entfernen | ❌ | ❌ | ✅ | ✅ |
| Firmenkonto verwalten | ❌ | eingeschränkt | ✅ | ✅ |
| Geld vom Firmenkonto auszahlen | ❌ | ❌ | ✅ | ✅ |
| Admin-Shops registrieren | ❌ | ❌ | ❌ | ✅ |
| Shop-History administrativ prüfen | ❌ | ❌ | ❌ | ✅ |

> Die konkreten Unternehmensrechte eines Mitarbeiters werden durch seine Rolle und seine einzelnen Berechtigungen bestimmt. Der Firmenbesitzer besitzt automatisch sämtliche Unternehmensrechte.

---

# 🛡️ Admin / OP

Einige Funktionen von CityShops sind bewusst ausschließlich für Administratoren beziehungsweise Spieler mit OP-Rechten vorgesehen.

Dazu gehören insbesondere administrative Shops und bestimmte Kontrollfunktionen.

---

# 🏪 Admin-Shops

Admin-Shops unterscheiden sich von normalen Spielershops.

Sie können ausschließlich von Spielern mit den erforderlichen administrativen Rechten registriert werden.

Für einen Admin-Verkauf wird beispielsweise verwendet:

```text
[AdminVerkauf]
```

Alternativ:

```text
[AdminShop]
```

Für einen Admin-Ankauf:

```text
[AdminAnkauf]
```

---

# ♾️ Unbegrenzter Warenbestand

Ein Admin-Verkauf benötigt keinen normalen Spieler-Warenbestand.

Die Waren können unbegrenzt angeboten werden.

Dadurch eignen sich Admin-Shops beispielsweise für serverseitige Grundversorgung oder eine kontrollierte Serverwirtschaft.

---

# 🏦 Staatskasse

Admin-Shops arbeiten mit der serverseitigen Wirtschaft beziehungsweise der vorgesehenen Staatskasse.

Damit wird das Geld nicht wie bei einem normalen Spielershop einem privaten Shopbesitzer zugeordnet.

Weitere Informationen findest du im Bereich:

**🏪 Admin-Shops**

---

# 📜 Shop-History für OP

Mit:

```text
/chestshop history
```

können OP-Spieler den gespeicherten Handelsverlauf eines Shops überprüfen.

Nach dem Ausführen des Befehls wird der gewünschte Shop ausgewählt.

CityShops speichert für einen Shop die letzten:

```text
50 Handelsvorgänge
```

Diese Funktion kann bei der Administration und Kontrolle der Serverwirtschaft hilfreich sein.

---

# ❤️ Admin-Spendenschilder

Neben normalen Spendenschildern unterstützt CityShops:

```text
[AdminSpende]
```

Diese Variante ist für Spenden an die vorgesehene Staatskasse gedacht.

Normale Spieler beziehungsweise Unternehmen verwenden dagegen:

```text
[Spende]
```

---

# ⭐ Bewertungen und Rechte

Auch das Bewertungssystem besitzt Schutzmechanismen.

Ein Shop kann nicht einfach beliebig bewertet werden.

Eine Bewertung setzt einen tatsächlichen Handel voraus.

Für eine Bewertung über den Befehl wird verwendet:

```text
/chestshop rate <1-5>
```

### Beispiel

```text
/chestshop rate 5
```

Eigene Shops beziehungsweise das eigene Unternehmen können nicht einfach selbst bewertet werden.

---

# 🔗 Bewertungsschilder

Für persönliche Shops können Bewertungsschilder mit:

```text
/chestshop link
```

verbunden werden.

Das Schild verwendet:

```text
[Bewertung]
```

Dadurch wird das Bewertungssystem eindeutig dem entsprechenden Shop zugeordnet.

---

# 🔐 Warum gibt es unterschiedliche Rechte?

Die Rollenaufteilung schützt die Wirtschaft des Servers.

Mit CityShops 2.3.0 können Unternehmen zusätzlich genauer bestimmen, welche Mitarbeiter bestimmte Unternehmensbereiche verwenden dürfen.

Dadurch kann beispielsweise verhindert werden, dass ein Mitarbeiter ohne entsprechende Rechte:

- Unternehmensshops verwaltet
- Shoppreise verändert
- Warenbestände verwaltet
- Shop-Vorlagen verwendet
- Abteilungen verändert
- Firmenstatistiken einsehen kann
- das Aktivitätsprotokoll einsehen kann
- Mitarbeiter entfernt
- die Firma umbenennt
- Firmenvermögen auszahlt
- administrative Shops erstellt
- administrative Kontrollfunktionen verwendet

Dadurch können mehrere Spieler gemeinsam in einem Unternehmen arbeiten, ohne dass jeder automatisch vollständige Kontrolle über das gesamte Unternehmen erhält.

---

# 🏢 Beispiel

Ein Unternehmen besitzt mehrere Shops und verschiedene Mitarbeiter.

### Filialleiter

Der Firmenbesitzer kann beispielsweise einem Mitarbeiter die Rolle:

```text
/company role set Spielername filialleiter
```

geben.

### Zusätzliches Recht

Soll der Mitarbeiter zusätzlich Shop-Vorlagen verwenden dürfen, kann das entsprechende Recht vergeben werden:

```text
/company permission set Spielername templates true
```

Soll dieses Recht später wieder entfernt werden:

```text
/company permission set Spielername templates false
```

### Firmenbesitzer

Der Firmenbesitzer besitzt automatisch sämtliche Unternehmensrechte und kann weiterhin beispielsweise:

```text
/company add Spielername
```

```text
/company remove Spielername
```

```text
/company rename NeuerName
```

und:

```text
/company withdraw 10000
```

verwenden.

---

# ⚠️ Keine Berechtigung?

Wenn eine CityShops-Funktion nicht verwendet werden kann, überprüfe zuerst:

- Gehört der Shop dir?
- Gehört der Shop zu deinem Unternehmen?
- Bist du Mitglied des Unternehmens?
- Bist du Firmenbesitzer?
- Welche Mitarbeiterrolle besitzt du?
- Besitzt du das benötigte einzelne Mitarbeiterrecht?
- Benötigt die Funktion OP-Rechte?
- Ist der richtige Shop ausgewählt?
- Ist MineBank korrekt installiert?
- Verwendet der Server die passende CityShops-Version?

Bei administrativen Funktionen sollte zusätzlich überprüft werden, ob der Spieler tatsächlich die notwendigen Minecraft-OP-Rechte besitzt.

---

# 💡 Wichtig

**OP-Rechte sollten nur vertrauenswürdigen Serveradministratoren gegeben werden.**

CityShops nutzt administrative Rechte unter anderem für Funktionen, die direkten Einfluss auf Shops und die Serverwirtschaft haben können.

Für normale Unternehmensmitarbeiter sind OP-Rechte nicht notwendig.

Die Mitarbeiterverwaltung sollte stattdessen über die vorgesehenen **Rollen und einzelnen Berechtigungen** von CityShops erfolgen.

---

# 📚 Passende Wiki-Seiten

Weitere Informationen zu den einzelnen Bereichen findest du hier:

- 🛒 **Shop erstellen**
- 🏪 **Admin-Shops**
- 🏢 **Unternehmen & Filialen**
- 💰 **Kaufen & Verkaufen**
- 📊 **Statistiken & Bewertungen**
- ❤️ **Spendenschilder**
- 💻 **Business OS**
- ⌨️ **Befehle**
- 📋 **Versionen & Changelog**

---

# ➡️ Als Nächstes

Im nächsten Bereich findest du Antworten auf häufig auftretende Fragen und Probleme rund um CityShops.

**❓ Häufige Fragen**

---

[← Befehle](cityshops-befehle.md) | [Weiter: Häufige Fragen →](cityshops-haeufige-fragen.md)
