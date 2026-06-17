# mydealz Manager

Ein Userscript zur Verwaltung und Filterung von Deals auf mydealz.de und preisjaeger.at.

> **🌍 International Users:** This script can easily be adapted for *hotukdeals, Dealabs, Pepper.pl, Chollometro*, etc. [Scroll down to the English section](#-international-users--support-for-other-countries) to request support for your country!
---

## Hinweis zur Projektentwicklung

Dieses Projekt wird überwiegend von mir allein entwickelt und gepflegt. 
Ich bin kein professioneller Softwareentwickler, sondern habe den mydealz Manager aus persönlichem Interesse und mithilfe von KI-Unterstützung erstellt.

Der Code entspricht möglicherweise nicht in allen Bereichen etablierten Best Practices oder typischen Architekturmustern. 
Feedback, Verbesserungsvorschläge oder konstruktive Hinweise sind jederzeit willkommen.

## Installation

Installiere das Script über [Greasyfork](https://greasyfork.org/de/scripts/522038-der-mydealz-manager-deine-pers%C3%B6nliche-deal-zentrale).

Voraussetzung: [Tampermonkey](https://www.tampermonkey.net/) oder eine ähnliche Userscript-Erweiterung.

## Funktionen

### Filter
- **Wortfilter**: Blende Deals basierend auf Schlüsselwörtern aus. Unterstützt Wildcards (`*`) für flexible Teilabgleiche
- **Händlerfilter**: Blockiere Deals von bestimmten Händlern
- **Benutzerfilter**: Blende Deals von bestimmten Benutzern aus
- **Preisfilter**: Setze eine Obergrenze für Deal-Preise
- **Temperaturfilter**: Blende Deals unter 0° automatisch aus

<div align="center">

![ezgif-52bf62337b566571](https://github.com/user-attachments/assets/c2c70ae5-e184-4874-b7e6-a66252cfa217)

</div>

### Verwaltung
- **Schnelles Ausblenden**: Klick auf das [X]-Symbol bei einem Deal zum sofortigen Ausblenden
- **Zentrale Einstellungen**: Verwaltung aller Filter über das Zahnrad-Icon
- **Backup & Restore**: Exportiere und importiere deine Filterlisten als JSON-Datei
- **Sortierungsspeicher**: Speichere deine bevorzugten Sortierungseinstellungen
  
<div align="center">

![ezgif-14e9a511016c1fec](https://github.com/user-attachments/assets/d7e1ac51-0f15-4b69-8638-bf990f50a907)

</div>

## Verwendung

1. Öffne mydealz.de oder preisjaeger.at
2. Klicke auf das Zahnrad-Icon bei einem beliebigen Deal, um das Einstellungsmenü zu öffnen
3. Konfiguriere deine Filter nach Bedarf
4. Verwende das [X]-Symbol, um einzelne Deals schnell auszublenden

## Kompatibilität

- mydealz.de
- preisjaeger.at
- Desktop und Mobile

## Lizenz

MIT

## Diskussion

[Diskussionsthread auf mydealz](https://www.mydealz.de/diskussion/tampermonkey-script-fur-mydealz-2299700)

---

## 🌍 International Users / Support for Other Countries

**English:**
This Tampermonkey / Violentmonkey script is built specifically for the platform structure of the **Atolls / Pepper.com** network. Because these deal platforms share a highly similar technical infrastructure, this script can easily be adapted for other international versions of the network.

If you want to use this script to manage, filter, or hide deals on your local platform, **please [open a GitHub Issue](https://github.com/9jS2PL5T/mydealz-Manager/issues) or comment on existing ones!** Once there is interest from your country, adding support for your local platform is a quick and easy task.

### Potential Platforms for Adaptation (Atolls / Pepper Network):
* **United Kingdom:** hotukdeals.com
* **France:** Dealabs.com
* **Poland:** Pepper.pl
* **Spain:** Chollometro.com
* **Mexico:** Promodescuentos.com
* **Sweden:** Pepperdeals.se
* **USA:** Pepperdeals.com
* ... and other regional platforms of the Atolls Germany GmbH & Pepper network.

---

## Hinweis / Disclaimer

Dieses Projekt ist ein inoffizielles Userscript und steht in keiner Verbindung zu mydealz.de, Preisjäger.at, der Atolls Germany GmbH, Pepper.com oder deren Partnern.

* **Reine Client-Seite:** Das Skript arbeitet ausschließlich lokal in deinem Browser und passt lediglich die Darstellung der Webseite an.
* **Keine Umgehung:** Es werden keine technischen Schutzmaßnahmen der Plattformen umgangen.
* **Keine Affiliate-Manipulation:** Es werden keine Affiliate-Links verändert, manipuliert oder durch eigene Erlöscodes ersetzt.
* **Datenschutz:** Es findet keinerlei Datenübertragung an den Entwickler oder Dritte statt. Alle Filterlisten und Einstellungen werden lokal in deinem Browser gespeichert.
* **Markenrechte:** Alle Marken- und Produktnamen sind Eigentum der jeweiligen Rechteinhaber und werden hier ausschließlich zur Beschreibung der Kompatibilität verwendet.

Die Nutzung dieses Skripts erfolgt auf eigene Verantwortung. Der Entwickler übernimmt keine Haftung für verpasste Deals, Darstellungsfehler oder eventuelle Verstöße gegen die Nutzungsbedingungen der jeweiligen Plattformen.
