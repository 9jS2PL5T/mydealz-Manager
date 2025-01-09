## Hier habe Ich alles mögliche Hochgeladen mit dem man später Chat GPT füttern kann, Sammlung ist aber noch im Aufbau  

``` js
(function() {
    let articles = document.querySelectorAll('article.thread');
    let result = '';
    for (let i = 0; i < Math.min(20, articles.length); i++) {
        result += articles[i].outerHTML + '\n\n\n';
    }
    console.log(result);
})();
```



