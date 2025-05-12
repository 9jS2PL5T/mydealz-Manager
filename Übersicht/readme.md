# myDealz Manager

> Automatisierte Anpassungen und Editing-Tools für die myDealz-Plattform

---

## Inhaltsverzeichnis

1. [Ideenecke](#ideenecke)  
2. [Geizfaktor](#geizfaktor)  
3. [General Editing Mode](#general-editing-mode)  
4. [Variable Elemente](#variable-elemente)  
5. [Werkzeuge & Ressourcen](#werkzeuge--ressourcen)  

---

## Ideenecke

- **Feedback Ecke**  
  [Mydealz Feedback Ecke <img src="https://www.mydealz.de/assets/img/emojis/thumb_7d48b.svg" width="24" alt="Daumen hoch">](https://www.mydealz.de/feedback)

- **Einzelne User blockieren**  
  [Einzelne User blockieren](https://www.mydealz.de/feedback/einzelne-user-blockieren-2500450)

---

## Geizfaktor

### Beschreibung  
Filtere Deals nach prozentualer oder absoluter Ersparnis.

### Filter-Logik  
- Ausblenden, wenn **% Ersparnis** < X  
- Ausblenden, wenn **€ Ersparnis** < Y  

> *X* und *Y* lassen sich konfigurierbar festlegen.

### HTML-Snippets

```html
<!-- Neuer Preis -->
<span class="thread-price">1.699€</span>

<!-- Alter Preis (durchgestrichen) -->
<span class="text--lineThrough">1.799€</span>

<!-- Ersparnis in % -->
<div class="textBadge--green">-6%</div>
