## [Mydealz Feedback Ecke <img src="https://www.mydealz.de/assets/img/emojis/thumb_7d48b.svg" width="50">](https://www.mydealz.de/feedback)  


#### [Einzelne User blockieren](https://www.mydealz.de/feedback/einzelne-user-blockieren-2500450)  

## Geizfaktor  
Wer hat nicht die Faxen dicke von "-6% " und somit eine ersparnis von 0,80€ ?  Aber hey das Problem ist ja noch etwas anders, wenn der Artikel 1.699€ kostet statt 1.799€  
dann wird das ganze ja wieder interessant desshalb sollte eine mischung aus Artikel ausblenden wenn unter ## % ersparnis und weniger als ## € ersparniss. wobei die werte selber festgelegt werden könnten.  
#### Neuer Preis  
``` html  
<span class="vAlign--all-tt"><span class="threadItemCard-price text--b thread-price">1.699€</span></span>
```
#### Alter Preis  
``` html 
<div class="flex boxAlign-ai--all-c"><span class="text--lineThrough space--ml-1 color--text-TranslucentSecondary
size--all-xl size--fromW3-xxl"> 1.799€ </span><button type="button" class="color--text-NeutralSecondary
flex space--ml-1 button--square"><!----><span class="flex--inline boxAlign-ai--all-c">  
<svg width="14" height="14" class="icon icon--info"><use xlink:href="/assets/img/ico_03e08.svg#info">
</use></svg><span class="popover-origin"><!----></span></span></button></div>
```  
#### Ersparnis in %
``` html
<div class="textBadge bRad--a-m flex--inline text--b boxAlign-ai--all-c size--all-s
size--fromW3-m space--h-1 space--ml-1 space--mr-0 textBadge--green"> -6% </div>
```  


## General Editing mode  
da stelle ich mir sowas vor, dass man auf einen Button mit "Multi Edit" oder "Selection Mode" klickt und dann die elemente, die wir schon mit dem zahnradmenü auswählen kann auch hervorgehoben werden, diese sollten dann im selection mode als button zur verfügung stehen, und wenn diese als buttons gedrückt werden die hervorhebung bzw. farbe ändern, so dass es aussieht wie wenn der button aktiviert/ gedrückt wird und dann vielleicht noch leicht rötlich hinterlegt, das ganze soll so ähnlich funktionieren wie der element picker bei ublock origin.
  


#### Der Fettgedruckte text im Deal Titel
hier sollte es im "Sniping" Modus möglich sein die einzelnen wörter in der überschrift beim hovern als button darzustellen um dann das jeweilige wort auszuwählen, wenn ein string markiert ist, sollen alle wörter einzeln markiert werden die in dem string vorkommen um sie nachher an den wortfilter zu übergeben...
``` html
<a class="cept-tt thread-link linkPlain thread-title--list js-thread-title" title="Flexispot Brand Sale | z.B.
Schreibtischgestell E5 = 179,99€ | Stühle und elektr. höhenverstellbare Schreibtische | + 8,5% Shoop Cashback"
href="https://www.mydealz.de/deals/der-grosse-flexispot-brand-month-sammeldeal-zb-elektrisch-hohenverstellbare-
gestelle-e5-17999eur-e7-plus-39999eur-uvm-85-shoop-2566055" data-t="threadLink" data-t-click="">Flexispot Brand Sale
| z.B. Schreibtischgestell E5 = 179,99€ | Stühle und elektr. höhenverstellbare Schreibtische | + 8,5% Shoop Cashback</a>
```  
  
#### Der Händler soll etwas hervorgehoben werden, so, dass er als editierbares element ins auge sticht.
``` html
<span class="color--text-TranslucentSecondary size--all-xs size--fromW3-s overflow--wrap-off overflow--ellipsis">
Verfügbar bei <a href="/search/deals?merchant-id=12021" class="text--b color--text-AccentBrand overflow--wrap-off
link  color--text-NeutralPrimary" data-t-click="" data-t="merchantLink"> FlexiSpot </a></span>
``` 
#### Der einzelne Benutzer soll etwas hervorgehoben werden, so, dass er als editierbares element ins auge sticht.
``` html
<span class="color--text-TranslucentSecondary overflow--wrap-off gap--h-1 flex boxAlign-ai--all-c">
<img src="https://static.mydealz.de/users/raw/default/2648675_15/fi/60x60/qt/45/2648675_15.jpg"  
srcset="https://static.mydealz.de/users/raw/default/2648675_15/fi/96x96/qt/45/2648675_15.jpg 2x" alt="Acuario's Profilbild"
class="size--all-s size--fromW3-m avatar--type-xs img img--type-entity img--square-s"><span class="overflow--ellipsis
size--all-xs size--fromW3-s"> Veröffentlicht von Acuario </span><svg width="14" height="14" class="size--all-xs
color--graphic-TranslucentTertiary icon icon--verified"><use xlink:href="/assets/img/ico_03e08.svg#verified">
</use></svg></span>
```

## Weitere Elemente als Variable speichern  
### Einfach nur eine Kurze Liste mit den "Interessantesten" HTML Containern für Copy Paste in´s LLM  
#### Alter Preis (durchgestrichen)  
``` html
<span class="color--text-NeutralSecondary text--lineThrough space--ml-1 size--all-m"> 353,82€ </span>
```

#### Neuer Preis 
``` html
<span class="text--b size--all-xl size--fromW3-xxl thread-price"> 317,99€ </span>
```

#### Ersparnis in %  
``` html
<div class="textBadge bRad--a-m flex--inline text--b boxAlign-ai--all-c
size--all-s size--fromW3-m space--h-1 space--ml-1 space--mr-0 textBadge--green"> -10% </div>
```

#### Händler  
``` html
<a href="/search/deals?merchant-id=723" class="text--b color--text-AccentBrand
overflow--wrap-off link  color--text-NeutralPrimary" data-t-click="" data-t="merchantLink"> Epson </a>
```

#### Benutzer
``` html
<span class="overflow--ellipsis size--all-xs size--fromW3-s"> Veröffentlicht von lluni </span>
```
#### Dealtemperatur
``` html
<button title="Derzeit bewertet mit 656°. Dein Vote verändert die Temperatur!"  
class="cept-vote-temp vote-temp size--all-m space--l-half-1 vote-temp--burn space--mh-1"  
style="position: relative;"><span class="overflow--wrap-off">656° </span><!---->  
<div style="position: absolute; left: 0px; top: 0px; width: 100%; height: 100%;  
display: none; z-index: 10001; pointer-events: none;"></div></button>
```
#### Anzahl der kommentare
``` html  
<a href="/deals/xiaomi-tv-ff-pro-2026-xiaomi-earlybird-aktion-bis-zu-12-zusatzlich-  
sofortrabatt-durch-mi-points-2569496#comments" class="flex--shrink-0 button button  
--type-text button--mode-secondary  2569496" title="Kommentare" data-t-click=""  
data-t="commentsLink"><svg width="22" height="22" class="icon icon--comments  
space--mr-1"><use xlink:href="/assets/img/ico_03e08.svg#  
comments"></use></svg> 5 </a>
```

#### Versandkosten
``` html  
<span class="flex--inline boxAlign-ai--all-c color--text-TranslucentSecondary
size--all-s size--fromW3-m"><span class="size--all-xs size--fromW3-s"> inkl.
</span><svg width="18px" height="14px" class="color--graphic-TranslucentSecondary
icon icon--truck space--mr-2p"><use xlink:href="/assets/img/ico_03e08.svg#truck">
</use></svg><span class="overflow--wrap-off"> 5,95€ </span></span>
```


## Händler durch icon ersetzen? 
``` html  
<a href="/search/deals?merchant-id=449" class="text--b color--text-AccentBrand overflow--wrap-off link  color--text-NeutralPrimary" data-t-click="" data-t="merchantLink"> dm </a>  
```
