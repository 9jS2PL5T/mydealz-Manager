# myDealz Manager Übersicht 🚀

> Alles Wichtige an einem Ort: Ideen, Filter-Logik, Editing-Modus, Werkzeuge & Projekte!

---

## Inhaltsverzeichnis

1. [Ideenecke](#ideenecke)  
2. [Werkzeuge 🧰](#werkzeuge-🧰)  
3. [Andere Projekte & Skripte 🚀](#andere-projekte--skripte-🚀)  

---

## Ideenecke

### 1. Feedback-Ecke 👍  
[Mydealz Feedback Ecke <img src="https://www.mydealz.de/assets/img/emojis/thumb_7d48b.svg" width="50" alt="Daumen hoch">](https://www.mydealz.de/feedback)

### 2. Einzelne User blockieren  
[Einzelne User blockieren](https://www.mydealz.de/feedback/einzelne-user-blockieren-2500450)

### 3. Geizfaktor 💰  
**Problem:** Wer will schon nur „-6 % Ersparnis“ sehen, wenn der Listenpreis hoch ist?  
**Lösung:**  
- Artikel **ausblenden**, wenn  
  - Ersparnis < X % **oder**  
  - Ersparnis < Y €  
- X und Y sind konfigurierbar.

<details>
<summary>HTML-Snippets für Geizfaktor</summary>

```html
<!-- Neuer Preis -->
<span class="vAlign--all-tt">
  <span class="threadItemCard-price text--b thread-price">1.699€</span>
</span>

<!-- Alter Preis (durchgestrichen) -->
<div class="flex boxAlign-ai--all-c">
  <span class="text--lineThrough space--ml-1 color--text-TranslucentSecondary size--all-xl size--fromW3-xxl">
    1.799€
  </span>
  <button type="button" class="color--text-NeutralSecondary flex space--ml-1 button--square">
    <svg width="14" height="14" class="icon icon--info">
      <use xlink:href="/assets/img/ico_03e08.svg#info"></use>
    </svg>
  </button>
</div>

<!-- Ersparnis in % -->
<div class="textBadge bRad--a-m flex--inline text--b boxAlign-ai--all-c size--all-s size--fromW3-m space--h-1 space--ml-1 space--mr-0 textBadge--green">
  -6%
</div>
