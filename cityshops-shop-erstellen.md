<link rel="stylesheet" href="style.css">

# 🛒 CityShops – Shops & Funktionen

Mit **[CityShops](https://www.curseforge.com/minecraft/mc-mods/cityshops)** kannst du direkt in deiner Minecraft-Welt eigene Verkaufs- und Ankaufsshops erstellen.

Neben klassischen Spieler-Shops bietet CityShops auch **Adminshops, Firmen, Mitarbeiter, Bewertungen, Spendenschilder, Lottery, einen Shop-PC mit Business OS, Statistiken, Automatisierung und weitere Funktionen**.

Die Bezahlung und Kontoverwaltung erfolgt über **[MineBank](https://www.curseforge.com/minecraft/mc-mods/minebank)**.

---

## 🧭 Übersicht

CityShops bietet unter anderem:

- 🛒 Spieler-Verkaufsshops
- 📥 Spieler-Ankaufsshops
- 👑 Admin-Verkaufsshops
- 👑 Admin-Ankaufsshops
- 📦 Einzel- und Doppelkisten
- 🏢 Firmen und Firmenshops
- 👥 Mitarbeiter und Firmenrollen
- ⭐ Bewertungen und Bewertungsschilder
- 🏷️ eigene Shopnamen
- ❤️ Spendenschilder
- 🎟️ Lottery
- 💻 Shop-PC & Business OS
- 🏬 Filialen
- 📜 Firmenlizenzen
- 📊 Statistiken und Handelsverlauf
- 📈 Marktberichte und Produktionsanalyse
- ⚙️ Hopper-Automatisierung
- ⏰ automatische Verwaltung inaktiver Shops

---

# 📦 Einen Shop erstellen

Die grundlegende Erstellung ist bei Spieler-Verkaufs- und Ankaufsshops ähnlich.

## 1️⃣ Kiste aufstellen

Stelle zuerst eine normale **Kiste oder Doppelkiste** an der gewünschten Stelle auf.

Eine Doppelkiste wird von CityShops automatisch als **ein gemeinsamer Shop mit gemeinsamem Warenbestand** behandelt.

---

## 2️⃣ Schild anbringen

Sneake und befestige ein **Schild direkt an der Kiste**.

Dieses Schild wird anschließend als Shop-Schild verwendet.

---

## 3️⃣ Shop-Item festlegen

Öffne die Kiste und lege das gewünschte Item in den **obersten linken Slot**.

CityShops erkennt dieses Item automatisch als Handelsware des Shops.

Dabei verwendet CityShops automatisch den übersetzten Namen des Gegenstands.

Du musst also keine technische Item-ID wie:

```text
minecraft:stone
```

auf das Schild schreiben.

---

## 4️⃣ Shop-Schild beschriften

Über die Beschriftung des Schildes legst du fest, welchen Shoptyp du erstellen möchtest.

Die zweite Zeile bestimmt die **Menge pro Handel**.

Steht dort beispielsweise:

```text
16
```

werden bei jedem erfolgreichen Handel **16 Items** gekauft oder verkauft.

> ⚠️ **Wichtig:** Die Menge ist kein Gesamtlimit des Shops. Sie bestimmt ausschließlich die Menge pro Handel.

---

## 5️⃣ Shop registrieren

Wenn Kiste, Item und Schild vorbereitet sind, klickst du das **Shop-Schild mit der rechten Maustaste an**.

Dadurch wird der Shop bei CityShops registriert.

---

# 💰 Spieler-Verkaufsshop

Mit einem Verkaufsshop können andere Spieler Waren aus deiner Shopkiste kaufen.

## 🪧 Schild beschriften

Beispiel:

```text
[Verkauf]
16

5,00
```

Alternativ kannst du auch:

```text
[Shop]
16

5,00
```

verwenden.

### Was bedeutet das?

Der Shop verkauft:

**16 Items für insgesamt 5,00**

Bei jedem erfolgreichen Handel erhält der Kunde 16 Items und bezahlt dafür insgesamt 5,00.

---

## 📦 Warenbestand

Ein normaler Verkaufsshop benötigt ausreichend Ware in seiner Shopkiste.

Wenn dein Shop beispielsweise 16 Items pro Handel verkauft, müssen mindestens 16 passende Items vorhanden sein.

Sind nicht genügend Items vorhanden, kann der Handel nicht durchgeführt werden.

---

## 💳 Wohin geht das Geld?

Bei einem persönlichen Shop werden die Einnahmen dem **MineBank-Konto des Shopbesitzers** gutgeschrieben.

Gehört der Shop zu einer Firma, werden die Einnahmen dem entsprechenden **MineBank-Firmenkonto** gutgeschrieben.

---

# 📥 Spieler-Ankaufsshop

Mit einem Ankaufsshop können andere Spieler ihre Items an deinen Shop verkaufen.

## 🪧 Schild beschriften

Beispiel:

```text
[Ankauf]
16

3,00
```

Der Shop kauft damit:

**16 Items für insgesamt 3,00**

Der handelnde Spieler gibt die Items ab und erhält dafür den eingetragenen Betrag.

---

## 📦 Wohin gehen die angekauften Items?

Die angekauften Items werden in der Shopkiste gelagert.

Deshalb muss in der Kiste ausreichend freier Platz vorhanden sein.

---

## 💳 Woher kommt das Geld?

Bei einem persönlichen Ankaufsshop wird das Geld vom **MineBank-Konto des Shopbesitzers** bezahlt.

Gehört der Shop zu einer Firma, wird das Geld vom **Firmenkonto** bezahlt.

Ein Handel kann nicht durchgeführt werden, wenn:

- der Spieler nicht genügend Items besitzt,
- der Shopbesitzer beziehungsweise die Firma nicht genügend Geld besitzt,
- oder in der Shopkiste nicht genügend Platz vorhanden ist.

---

# 👑 Admin-Verkaufsshop

Adminshops sind spezielle Shops für Serverbetreiber.

> ⚠️ **Nur OP-Spieler können Adminshops registrieren.**

Ein Admin-Verkaufsshop besitzt **unbegrenzten Warenbestand** und muss deshalb nicht wie ein normaler Spielershop aufgefüllt werden.

## 🪧 Schild beschriften

Beispiel:

```text
[AdminVerkauf]
16

5,00
```

Alternativ kann auch:

```text
[AdminShop]
16

5,00
```

verwendet werden.

Der Spieler erhält in diesem Beispiel:

**16 Items für insgesamt 5,00**

---

## ♾️ Unbegrenzter Bestand

Ein Admin-Verkaufsshop benötigt keinen normalen Warenbestand.

Die angebotenen Items können unabhängig vom Inhalt der Kiste verkauft werden.

---

## 🏦 Staatskasse

Das Geld eines erfolgreichen Kaufs geht nicht an den Ersteller des Adminshops.

Die Zahlung wird über **MineBank direkt in die Staatskasse** eingezahlt.

> 💡 Auch der Ersteller des Adminshops kann ganz normal an seinem Adminshop einkaufen.

---

# 👑 Admin-Ankaufsshop

Mit einem Admin-Ankaufsshop können Spieler Items an einen administrativen Shop verkaufen.

## 🪧 Schild beschriften

Beispiel:

```text
[AdminAnkauf]
16

3,00
```

Damit verkauft der Spieler:

**16 Items für insgesamt 3,00**

an den Adminshop.

---

## 🏦 Auszahlung aus der Staatskasse

Die Auszahlung erfolgt direkt aus der **MineBank-Staatskasse**.

Deshalb muss ausreichend Guthaben in der Staatskasse vorhanden sein.

Die angenommenen Items müssen bei einem Admin-Ankaufsshop **nicht dauerhaft in der Kiste gelagert werden**.

---

# 📋 Shoptypen im Überblick

| Shoptyp | Schild | Funktion |
| --- | --- | --- |
| 🟢 Spieler-Verkauf | `[Verkauf]` oder `[Shop]` | Verkauft Waren aus der Kiste |
| 🔵 Spieler-Ankauf | `[Ankauf]` | Kauft Waren von Spielern |
| 🟠 Admin-Verkauf | `[AdminVerkauf]` oder `[AdminShop]` | Verkauft mit unbegrenztem Bestand |
| 🟣 Admin-Ankauf | `[AdminAnkauf]` | Kauft über die Staatskasse an |

Bei den gezeigten Schildbeispielen bleibt die **dritte Zeile leer**.

---

# 🖱️ Mit einem Shop handeln

Spieler handeln über einen **Rechtsklick auf das Shop-Schild**.

Bei jedem erfolgreichen Handel wird genau die Menge verwendet, die in der zweiten Zeile des Schildes eingetragen wurde.

Beispiel:

```text
[Verkauf]
16

5,00
```

Ein erfolgreicher Rechtsklick bedeutet:

**16 Items kaufen → 5,00 bezahlen**

Ein weiterer erfolgreicher Rechtsklick führt denselben Handel erneut durch.

---

# 🧪 Eigenen Shop testen

Du benötigst keinen zweiten Spieler, um deinen eigenen Shop zu testen.

Als Besitzer:

**Sneaken + Rechtsklick auf den eigenen Shop**

CityShops führt anschließend einen Testhandel durch.

> 💡 **Beim Testhandel wird kein Geld übertragen.**

So kannst du überprüfen, ob dein Shop korrekt eingerichtet wurde.

---

# 📦 Einzelkisten & Doppelkisten

CityShops unterstützt normale Kisten und Doppelkisten.

Bei einer Doppelkiste gilt:

- beide Hälften teilen sich denselben Warenbestand,
- beide Hälften gehören zur selben Shopregistrierung,
- die komplette Doppelkiste zählt als **ein Shop**.

Du kannst deshalb nicht eine Hälfte als Verkaufsshop und die andere Hälfte als Ankaufsshop verwenden.

---

# 🔒 Schutz der Shopkisten

Registrierte Shopkisten sind vor unberechtigtem Zugriff geschützt.

Andere Spieler können dadurch nicht einfach auf den Warenbestand eines fremden Shops zugreifen.

Auch verbundene **Bewertungsschilder** werden geschützt.

OP-Spieler behalten ihren administrativen Zugriff und können trotzdem weiterhin normal an Shops handeln.

---

# ⭐ Bewertungen & Bewertungsschilder

CityShops besitzt ein eigenes Bewertungssystem für Shops und Unternehmen.

Nach einem **echten Handel** kann ein Kunde einen Shop beziehungsweise eine Firma mit **1 bis 5 Sternen** bewerten.

Eigene Shops beziehungsweise die eigene Firma können nicht selbst bewertet werden.

---

## 🪧 Bewertungsschild für einen persönlichen Shop

Stelle an der gewünschten Stelle ein Schild auf.

Schreibe in die erste Zeile:

```text
[Bewertung]
```

Anschließend verwendest du:

```text
/chestshop link
```

Danach:

1. klickst du deinen Shop an,
2. anschließend klickst du das Bewertungsschild an.

Das Bewertungsschild ist jetzt mit deinem Shop verbunden.

---

## 🏢 Bewertungsschild für eine Firma

Bei einer Firma kann ein Bewertungsschild ebenfalls mit:

```text
[Bewertung]
```

erstellt werden.

Der Firmenbesitzer registriert beziehungsweise verbindet das Schild anschließend mit der Firma.

---

## ⭐ Eine Bewertung abgeben

Ein Rechtsklick auf das Bewertungsschild öffnet die Auswahl für eine Bewertung von:

**⭐ 1 bis ⭐⭐⭐⭐⭐ 5 Sternen**

Die Auswahl ist aus Sicherheitsgründen nur für kurze Zeit gültig und funktioniert nur, wenn sich der Spieler in der Nähe des Bewertungsschildes befindet.

Alternativ kann die Bewertung über:

```text
/chestshop rate <1-5>
```

gestartet werden.

Danach wird der gewünschte Shop angeklickt.

---

# 🏷️ Eigene Shopnamen

Besitzer können ihren Shops eigene Namen geben.

Dafür kann folgender Befehl verwendet werden:

```text
/chestshop name <Name>
```

Anschließend klickst du deinen eigenen Shop an.

Der gewünschte Name wird dadurch dem Shop zugeordnet.

---

# ❤️ Spendenschilder

CityShops unterstützt Spendenschilder.

Für ein Spendenschild wird **keine Shopkiste benötigt**.

Das Schild kann an einer beliebigen Stelle aufgestellt und anschließend registriert werden.

---

## 👤 Spieler- oder Firmenspende

Beispiel:

```text
[Spende]


10,00
```

Bei jedem erfolgreichen Rechtsklick werden:

**10,00**

gespendet.

Gehört der Ersteller des Spendenschildes zu einer Firma, wird das Geld auf das entsprechende **MineBank-Firmenkonto** übertragen.

Besitzt der Ersteller keine Firma, geht die Spende auf sein persönliches **MineBank-Konto**.

Das Spendenschild zeigt außerdem den **insgesamt gesammelten Betrag** an.

---

## 🏦 Spende an die Staatskasse

Für die Staatskasse gibt es ein eigenes Admin-Spendenschild.

Beispiel:

```text
[AdminSpende]


10,00
```

Dieses Schild kann nur von **OP-Spielern** erstellt werden.

Die Spende wird direkt in die **MineBank-Staatskasse** eingezahlt.

Auch dafür wird keine Kiste benötigt.

---

# 🎟️ Lottery

CityShops besitzt zusätzlich ein **spielerbetriebenes Lottery-System**.

Die Lottery ist in das CityShops-Firmensystem und das Business OS integriert und verwendet das **MineBank-Firmenkonto**.

> ℹ️ Die Lottery ist ein zusätzliches CityShops-Feature und benötigt keine normale Shopkiste.

---

# 🏢 Firmen & Firmenshops

CityShops besitzt ein vollständiges Firmensystem.

Eine Firma kann beliebig viele Shopkisten besitzen.

Wird eine Firma gegründet, übernimmt CityShops vorhandene persönliche Shops automatisch.

Neue Shops von Firmenmitgliedern können anschließend ebenfalls der Firma zugeordnet werden.

Firmenshops verwenden gemeinsam:

- den Firmennamen,
- das MineBank-Firmenkonto,
- und die gemeinsame Firmenverwaltung.

---

# ⌨️ Firmenbefehle

## Firma erstellen

```text
/company create <Name>
```

Erstellt eine Firma und das dazugehörige MineBank-Firmenkonto.

---

## Firma umbenennen

```text
/company rename <Neuer Name>
```

Ändert den Firmennamen.

---

## Firmeninformationen anzeigen

```text
/company info
```

Zeigt Informationen zur eigenen Firma.

---

## Mitarbeiter hinzufügen

```text
/company add <Spieler>
```

Fügt einen Spieler als Mitarbeiter hinzu.

---

## Mitarbeiter entfernen

```text
/company remove <Spieler>
```

Entfernt einen Mitarbeiter aus der Firma.

---

## Firma verlassen

```text
/company leave
```

Ermöglicht einem Mitarbeiter, die Firma zu verlassen.

---

## Shop für die Firma übernehmen

```text
/company claim
```

Anschließend kann ein vorhandener persönlicher Shop angeklickt und der Firma zugeordnet werden.

---

## Geld einzahlen

```text
/company deposit <Betrag>
```

Überweist Geld vom persönlichen Konto auf das Firmenkonto.

---

## Geld auszahlen

```text
/company withdraw <Betrag>
```

Ermöglicht eine Auszahlung vom Firmenkonto.

---

# 👥 Mitarbeiter & Firmenrollen

Mitarbeiter können abhängig von ihrer Rolle Firmenfunktionen verwenden und gemeinsame Shops verwalten.

Bestimmte Verwaltungsfunktionen bleiben dem Firmenbesitzer beziehungsweise entsprechend berechtigten Rollen vorbehalten.

Dazu gehören unter anderem:

- Mitarbeiter verwalten
- Firmenverwaltung
- Firmenshops verwalten
- Firmenkonto verwalten
- Rollen und Berechtigungen verwalten

---

# 💻 Shop-PC & Business OS

CityShops besitzt einen eigenen platzierbaren **Shop-PC**.

Ein Rechtsklick auf den Computer öffnet das speziell entwickelte **CityShops Business OS**.

Das Business OS dient als zentrale Verwaltung für Shops und Unternehmen.

---

## 🖥️ Funktionen des Business OS

Das Business OS bietet unter anderem:

- Firmenname
- Firmenkontostand
- eigene Firmenrolle
- persönliche Shops
- Firmenshops
- Shopstatistiken
- Firmenstatistiken
- Filialen
- Mitarbeiter
- Firmenrollen
- Firmenlizenzen
- Lizenzkäufe über das MineBank-Firmenkonto
- Marktberichte auf Grundlage echter CityShops-Preise
- Produktionsanalyse
- scrollbare Listen
- sichtbare Scrollleisten

Die Marktübersicht teleportiert Spieler bewusst **nicht direkt zu einem Shop**.

---

# 🏬 Filialen

Unternehmen können ihre Shops über **Filialen** organisieren.

Dadurch können mehrere Verkaufsstellen eines Unternehmens übersichtlicher im Business OS verwaltet werden.

Filialen sind Teil der zentralen Firmen- und Shopverwaltung von CityShops.

---

# 📜 Firmenlizenzen

CityShops unterstützt außerdem **Firmenlizenzen**.

Lizenzen können innerhalb des Business OS verwaltet und miteinander kombiniert werden.

Lizenzkäufe werden über das **MineBank-Firmenkonto** abgewickelt.

---

# 📈 Marktberichte & Produktionsanalyse

Das Business OS enthält Funktionen zur Analyse des CityShops-Marktes.

Dazu gehören unter anderem:

- Marktberichte
- Auswertungen realer CityShops-Preise
- Produktionsanalyse
- Shop- und Unternehmensdaten

Dadurch können Unternehmen ihre Verkaufsaktivitäten direkt über das Business OS auswerten.

---

# ⚙️ Trichter & Automatisierung

CityShops unterstützt Minecraft-Trichter.

Damit können Shops teilweise automatisiert werden.

## 🟢 Verkaufsshops automatisch auffüllen

Trichter können Verkaufskisten automatisch mit neuer Ware versorgen.

So können beispielsweise Lager oder Farmen direkt mit einem Shop verbunden werden.

---

## 🔵 Ankaufsshops automatisch leeren

Trichter können angekaufte Items automatisch aus Ankaufskisten entfernen.

Dadurch entsteht wieder freier Platz für weitere Ankäufe.

> 💡 Für den Handel zählt ausschließlich das für den Shop registrierte Item.

Andere Items, die versehentlich in die Kiste gelangen, werden vom Shopsystem nicht als Shopware gehandelt.

---

# 📊 Statistiken & Handelsverlauf

CityShops zeichnet echte Handelsvorgänge automatisch auf.

Gespeichert werden unter anderem:

- Anzahl der Transaktionen
- gehandelte Itemmengen
- Umsatz

Die Daten werden serverseitig gespeichert.

Pro Shop werden außerdem die **letzten 50 Handelsvorgänge** gespeichert.

---

## 📴 Offline-Zusammenfassung

War ein Shopbesitzer offline, während an seinen Shops gehandelt wurde, erhält er beim nächsten Login eine Zusammenfassung seiner Verkäufe und Ankäufe.

---

## 📊 Eigene Statistik anzeigen

Mit:

```text
/chestshop stats
```

kannst du deine persönliche Handelsstatistik anzeigen.

---

## 🔎 Shop-Verlauf für Administratoren

OP-Spieler können:

```text
/chestshop history
```

verwenden.

Anschließend wird das gewünschte Shop-Schild angeklickt.

Dadurch kann der Handelsverlauf des Shops überprüft werden.

---

# ⏰ Inaktive Shops

Spielershops können automatisch deaktiviert werden, wenn der Besitzer längere Zeit nicht aktiv war.

Standardmäßig beträgt diese Zeit:

**168 Stunden**

Die Shopkiste und die darin enthaltenen Items werden dabei **nicht gelöscht**.

Serverbetreiber können diese Zeit über:

```text
inactiveHours
```

in:

```text
serverconfig/chestshop-server.toml
```

anpassen.

> 👑 **Adminshops bleiben aktiv** und sind von dieser automatischen Deaktivierung ausgenommen.

Entfernte Shops werden automatisch aus den Statistiken und dem Shop-PC bereinigt.

---

# ⚠️ Wichtige Shopregeln

Für CityShops gelten einige wichtige Regeln:

- Pro Kiste beziehungsweise Doppelkiste ist genau **ein Shop** erlaubt.
- Ein Shop ist entweder **Ankauf oder Verkauf**.
- Eine Kiste kann nicht gleichzeitig ankaufen und verkaufen.
- Beide Seiten einer Doppelkiste teilen sich denselben Bestand.
- Eine Doppelkiste besitzt nur eine Shopregistrierung.
- Shopkisten sind vor unberechtigtem Zugriff geschützt.
- Verbundene Bewertungsschilder sind ebenfalls geschützt.
- OP-Spieler behalten administrativen Zugriff.
- OP-Spieler können trotzdem normal an Shops handeln.
- Besitzer können ihren eigenen Shop mit **Sneaken + Rechtsklick** testen.
- Beim Testhandel wird kein Geld übertragen.

---

# ❓ Shop funktioniert nicht?

Falls sich dein Shop nicht registrieren lässt oder ein Handel nicht funktioniert, überprüfe zuerst:

- Ist **[CityShops](https://www.curseforge.com/minecraft/mc-mods/cityshops)** korrekt installiert?
- Ist **[MineBank](https://www.curseforge.com/minecraft/mc-mods/minebank)** installiert?
- Ist das Schild direkt an der Kiste angebracht?
- Wurde das Schild beim Sneaken platziert?
- Liegt das gewünschte Item oben links in der Kiste?
- Ist das Schild korrekt beschriftet?
- Wurde das Schild anschließend mit Rechtsklick registriert?
- Ist bei einem Verkauf genügend Ware vorhanden?
- Besitzt der Spieler bei einem Ankauf genügend Items?
- Besitzt der Shop beziehungsweise die Firma genügend Geld?
- Ist in einer Ankaufskiste genügend freier Platz vorhanden?
- Ist bei einem Admin-Ankauf ausreichend Geld in der Staatskasse?
- Besitzt du für das Registrieren eines Adminshops OP-Rechte?

---

# 🛡️ Hinweise für Serverbetreiber

Vor größeren CityShops-Updates empfiehlt sich ein Backup der Welt und der Serverdaten.

Achte außerdem darauf, dass:

- CityShops und MineBank in kompatiblen Versionen installiert sind,
- keine alten doppelten CityShops-JARs im `mods`-Ordner liegen,
- die MineBank-Staatskasse für Admin-Ankäufe ausreichend Guthaben besitzt.

Admin-Verkaufsshops zahlen Einnahmen in die Staatskasse ein.

Admin-Ankaufsshops bezahlen Spieler aus der Staatskasse.

CityShops speichert seine Shop-, Firmen-, Bewertungs- und Statistikdaten serverseitig.

---

# 🌆 CityShops auf einen Blick

CityShops ist weit mehr als ein klassischer Chest-Shop-Mod.

Das System verbindet Shops und Wirtschaft mit umfangreichen Verwaltungsfunktionen:

- 🛒 Spieler-Verkauf
- 📥 Spieler-Ankauf
- 👑 Admin-Verkauf
- 👑 Admin-Ankauf
- 📦 Einzel- und Doppelkisten
- 🏢 Unternehmen und Firmenshops
- 👥 Mitarbeiter und Rollen
- ⭐ Bewertungen
- 🏷️ Shopnamen
- ❤️ Spendenschilder
- 🎟️ Lottery
- 💻 Shop-PC & Business OS
- 🏬 Filialen
- 📜 Firmenlizenzen
- 📊 Shop- und Firmenstatistiken
- 📈 Marktberichte
- 🏭 Produktionsanalyse
- 📜 Handelsverläufe
- ⚙️ Hopper-Automatisierung
- ⏰ automatische Inaktivitätsverwaltung

---

## 🔗 Offizielle Seiten

- **[CityShops auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/cityshops)**
- **[MineBank auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/minebank)**

---

[← Zurück zu CityShops](cityshops.md)
