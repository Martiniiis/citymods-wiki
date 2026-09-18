<link rel="stylesheet" href="style.css">

<img src="admin shops.png" alt="CityShops – Admin-Shops" class="wiki-banner">

# 👑 CityShops – Admin-Shops

Mit **CityShops** können Serverbetreiber spezielle **Admin-Shops** erstellen.

Im Gegensatz zu normalen Spielershops gehören diese Shops keinem normalen Spieler oder Unternehmen. Sie arbeiten direkt mit der **MineBank-Staatskasse** und ermöglichen dem Server, Waren mit unbegrenztem Bestand zu verkaufen oder Items von Spielern anzukaufen.

> ⚠️ **Wichtig:** Admin-Shops können nur von Spielern mit **OP-Rechten** registriert werden.

---

## 🧭 Welche Admin-Shops gibt es?

CityShops unterstützt zwei Arten von Admin-Shops:

| Shoptyp | Funktion |
| --- | --- |
| 👑 **Admin-Verkauf** | Verkauft Items mit unbegrenztem Warenbestand an Spieler |
| 📥 **Admin-Ankauf** | Kauft Items von Spielern und bezahlt aus der Staatskasse |

Admin-Shops eignen sich beispielsweise dafür, wichtige Waren dauerhaft auf einem Server anzubieten oder bestimmte Items aus der Spielwelt anzukaufen.

---

# 👑 Admin-Verkaufsshop erstellen

Ein Admin-Verkaufsshop verkauft Items an Spieler.

Der große Unterschied zu einem normalen Verkaufsshop:

**Der Warenbestand ist unbegrenzt.**

Der Shop muss deshalb nicht ständig mit neuen Items aufgefüllt werden.

---

## 1️⃣ Kiste aufstellen

Stelle zuerst eine normale **Kiste oder Doppelkiste** an der gewünschten Stelle auf.

Auch bei Admin-Shops behandelt CityShops eine Doppelkiste als **einen gemeinsamen Shop**.

---

## 2️⃣ Verkaufsitem festlegen

Lege das Item, das der Admin-Shop verkaufen soll, in den **obersten linken Slot der Kiste**.

CityShops verwendet dieses Item zur Registrierung des Shops.

Der Itemname wird automatisch erkannt.

Du musst keine technische Item-ID wie:

```text
minecraft:diamond
```

auf das Schild schreiben.

---

## 3️⃣ Admin-Schild anbringen

Sneake und befestige ein **Schild direkt an der Kiste**.

Für einen Admin-Verkauf beschriftest du das Schild beispielsweise so:

```text
[AdminVerkauf]
16

5,00
```

Alternativ kannst du auch:

```text
[AdminShop]
16

5,00
```

verwenden.

---

## 4️⃣ Was bedeutet das Schild?

Bei diesem Beispiel:

```text
[AdminVerkauf]
16

5,00
```

gilt:

| Schildzeile | Bedeutung |
| --- | --- |
| `[AdminVerkauf]` | Erstellt einen Admin-Verkaufsshop |
| `16` | Menge pro Handel |
| leer | Diese Zeile bleibt leer |
| `5,00` | Gesamtpreis für diese Menge |

Ein Spieler erhält damit bei einem erfolgreichen Handel:

**16 Items für insgesamt 5,00**

> 💡 Die eingetragene Menge ist **kein Gesamtlimit**. Bei jedem erfolgreichen Handel werden erneut 16 Items verkauft.

---

## 5️⃣ Admin-Shop registrieren

Wenn Kiste, Item und Schild vorbereitet sind, klickst du das **Shop-Schild mit der rechten Maustaste an**.

CityShops registriert anschließend den Admin-Verkaufsshop.

> ⚠️ Für die Registrierung eines Admin-Shops benötigst du **OP-Rechte**.

🎉 **Der Admin-Verkaufsshop ist jetzt einsatzbereit.**

---

# ♾️ Unbegrenzter Warenbestand

Admin-Verkaufsshops besitzen einen **unbegrenzten Warenbestand**.

Nach der Registrierung muss der Shop deshalb nicht wie ein normaler Spieler-Verkaufsshop mit Waren aufgefüllt werden.

Spieler können weiterhin die auf dem Schild eingestellte Menge kaufen, auch wenn kein normaler Warenbestand in der Kiste vorhanden ist.

Das macht Admin-Verkaufsshops besonders praktisch für serverseitig bereitgestellte Waren.

---

# 🏦 Wohin geht das Geld?

Bei einem normalen Spielershop erhält der Besitzer beziehungsweise die Firma die Einnahmen.

Bei einem **Admin-Verkaufsshop** funktioniert das anders:

**Die Einnahmen werden direkt in die MineBank-Staatskasse eingezahlt.**

Beispiel:

```text
[AdminVerkauf]
16

5,00
```

Der Spieler:

**erhält 16 Items**

und:

**bezahlt insgesamt 5,00**

Die 5,00 werden der **MineBank-Staatskasse** gutgeschrieben.

---

# 📥 Admin-Ankaufsshop erstellen

Ein Admin-Ankaufsshop funktioniert in die andere Richtung.

Hier verkauft ein Spieler seine Items an den Server.

Die Bezahlung erfolgt aus der **MineBank-Staatskasse**.

---

## 1️⃣ Kiste aufstellen

Stelle eine normale **Kiste oder Doppelkiste** auf.

---

## 2️⃣ Ankaufitem festlegen

Lege das Item, das der Admin-Shop ankaufen soll, in den **obersten linken Slot** der Kiste.

CityShops erkennt dadurch automatisch, welches Item gehandelt werden soll.

---

## 3️⃣ Schild anbringen

Sneake und befestige ein Schild direkt an der Kiste.

Beschrifte es beispielsweise so:

```text
[AdminAnkauf]
16

3,00
```

---

## 4️⃣ Was bedeutet das Schild?

Bei:

```text
[AdminAnkauf]
16

3,00
```

gilt:

| Schildzeile | Bedeutung |
| --- | --- |
| `[AdminAnkauf]` | Erstellt einen Admin-Ankaufsshop |
| `16` | Menge pro Handel |
| leer | Diese Zeile bleibt leer |
| `3,00` | Auszahlung für diese Menge |

Der Spieler verkauft also:

**16 Items für insgesamt 3,00**

an den Admin-Shop.

---

## 5️⃣ Admin-Ankauf registrieren

Klicke nach der Einrichtung mit der **rechten Maustaste auf das Shop-Schild**.

CityShops registriert anschließend den Admin-Ankaufsshop.

Auch hierfür werden **OP-Rechte** benötigt.

🎉 **Der Admin-Ankaufsshop ist jetzt eingerichtet.**

---

# 🏦 Auszahlung aus der Staatskasse

Bei einem Admin-Ankauf wird das Geld nicht von einem Spieler oder einer Firma bezahlt.

Die Auszahlung erfolgt direkt aus der:

**🏦 MineBank-Staatskasse**

Das bedeutet:

```text
[AdminAnkauf]
16

3,00
```

Der Spieler gibt:

**16 Items**

ab und erhält:

**3,00 aus der Staatskasse**

> ⚠️ **Wichtig:** Die Staatskasse benötigt ausreichend Guthaben, damit ein Admin-Ankauf durchgeführt werden kann.

---

# 📦 Was passiert mit angekauften Items?

Ein Admin-Ankauf unterscheidet sich auch beim Warenbestand von einem normalen Spieler-Ankauf.

Bei einem normalen Ankaufsshop werden die angekauften Items in der Shopkiste gelagert.

Bei einem **Admin-Ankaufsshop müssen die angenommenen Items nicht dauerhaft in der Kiste gelagert werden**.

Dadurch kann der Server dauerhaft Items von Spielern ankaufen, ohne dass die Shopkiste regelmäßig geleert werden muss.

---

# 📋 Admin-Verkauf & Admin-Ankauf im Vergleich

| | 👑 Admin-Verkauf | 📥 Admin-Ankauf |
| --- | --- | --- |
| Schild | `[AdminVerkauf]` / `[AdminShop]` | `[AdminAnkauf]` |
| Spieler | kauft Items | verkauft Items |
| Warenbestand | unbegrenzt | keine dauerhafte Lagerung nötig |
| Geld | geht in die Staatskasse | kommt aus der Staatskasse |
| Shopbesitzer | Server/Admin | Server/Admin |
| Registrierung | OP erforderlich | OP erforderlich |

---

# 🖱️ An einem Admin-Shop handeln

Spieler benutzen Admin-Shops genauso bequem wie normale CityShops.

Der Handel erfolgt über einen **Rechtsklick auf das Shop-Schild**.

Die zweite Schildzeile bestimmt die Menge pro Handel.

Die vierte Schildzeile bestimmt den Gesamtpreis beziehungsweise die Auszahlung für diese Menge.

### Beispiel Verkauf

```text
[AdminVerkauf]
16

5,00
```

bedeutet:

**16 Items erhalten → 5,00 bezahlen**

### Beispiel Ankauf

```text
[AdminAnkauf]
16

3,00
```

bedeutet:

**16 Items abgeben → 3,00 erhalten**

---

# 👑 Können Admins selbst am Shop handeln?

Ja.

Auch der Ersteller beziehungsweise ein OP-Spieler kann ganz normal an einem Admin-Shop handeln.

Adminrechte verhindern also nicht die normale Verwendung des Shops.

---

# 📦 Einzelkisten & Doppelkisten

Auch Admin-Shops unterstützen **Einzelkisten und Doppelkisten**.

Bei einer Doppelkiste gilt:

- beide Seiten gehören zum selben Shop,
- die Doppelkiste besitzt nur eine gemeinsame Shopregistrierung,
- pro Doppelkiste kann nur ein Shop eingerichtet werden.

Eine Hälfte kann deshalb nicht als Admin-Verkauf und die andere Hälfte als Admin-Ankauf verwendet werden.

---

# 🔒 Schutz & administrativer Zugriff

Registrierte Shopkisten sind durch CityShops vor unberechtigtem Zugriff geschützt.

OP-Spieler behalten jedoch ihren administrativen Zugriff.

Dadurch können Serveradministratoren bei Problemen weiterhin auf die entsprechenden Shopkisten zugreifen.

---

# ⏰ Admin-Shops & Inaktivität

Normale Spielershops können nach längerer Abwesenheit ihres Besitzers automatisch deaktiviert werden.

**Admin-Shops sind von dieser Inaktivitätsregel ausgenommen.**

Sie bleiben weiterhin aktiv und können dauerhaft als Server-Shops verwendet werden.

---

# 💡 Typische Einsatzmöglichkeiten

Admin-Shops können beispielsweise eingesetzt werden, um:

- wichtige Ressourcen dauerhaft anzubieten,
- bestimmte Items dauerhaft anzukaufen,
- eine serverweite Grundversorgung aufzubauen,
- Geld über Verkäufe in die Staatskasse einzunehmen,
- Geld über Ankäufe wieder in die Wirtschaft zu bringen,
- zentrale Server-Shops oder Marktplätze aufzubauen.

---

# ⚠️ Wichtige Hinweise

Bei Admin-Shops solltest du Folgendes beachten:

- Nur **OP-Spieler** können Admin-Shops registrieren.
- Admin-Verkauf besitzt **unbegrenzten Warenbestand**.
- Einnahmen aus Admin-Verkäufen gehen in die **MineBank-Staatskasse**.
- Admin-Ankäufe werden aus der **MineBank-Staatskasse** bezahlt.
- Für Admin-Ankäufe muss ausreichend Geld in der Staatskasse vorhanden sein.
- Admin-Ankauf benötigt keine dauerhafte Lagerung der angekauften Items.
- Eine Kiste beziehungsweise Doppelkiste kann nur einen Shop besitzen.
- Admin-Shops bleiben auch bei Spieler-Inaktivität aktiv.

---

# ❓ Admin-Shop funktioniert nicht?

Falls sich ein Admin-Shop nicht registrieren lässt oder ein Handel nicht funktioniert, überprüfe:

- Ist **CityShops** korrekt installiert?
- Ist **MineBank** korrekt installiert?
- Besitzt du **OP-Rechte**?
- Ist das Schild direkt an der Kiste angebracht?
- Wurde das Schild beim Sneaken platziert?
- Liegt das gewünschte Item im obersten linken Slot?
- Ist das Schild korrekt beschriftet?
- Wurde das Schild anschließend mit Rechtsklick registriert?
- Ist beim Admin-Ankauf ausreichend Geld in der Staatskasse vorhanden?
- Besitzt der Spieler beim Admin-Ankauf genügend Items?

---

# 📚 Weitere CityShops-Anleitungen

Weitere Funktionen findest du in den anderen Bereichen der CityShops-Wiki:

- 🛒 **Shop erstellen**
- 🏢 **Unternehmen & Filialen**
- 💰 **Kaufen & Verkaufen**
- 📊 **Statistiken & Bewertungen**
- ❤️ **Spendenschilder**
- 🎟️ **Lottery**
- 💻 **Business OS**
- ⌨️ **Befehle**
- 🔐 **Berechtigungen**
- ❓ **Häufige Fragen**

---

## 🔗 Offizielle Seiten

- **[CityShops auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/cityshops)**
- **[MineBank auf CurseForge](https://www.curseforge.com/minecraft/mc-mods/minebank)**

---

[← Shop erstellen](cityshops-shop-erstellen.md) | [Weiter: Unternehmen & Filialen →](cityshops-unternehmen-filialen.md)
