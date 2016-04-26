Tag
=========

Afin de faire fonctionner les widgets SeasonPros, vous devez inclure dans votre page le tag suivant

```html
  <script type="text/javascript">
    (function() {
        var seasonpros = document.createElement('script'); seasonpros.type = 'text/javascript'; seasonpros.async = true;
        seasonpros.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + 'www.seasonpros.com/js/widget.min.js';
        var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(seasonpros, s);
    })();
  </script>
```

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
