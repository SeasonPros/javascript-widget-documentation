Mise en place du tag
=====================

Afin de faire fonctionner les widgets SeasonPros, vous devez inclure dans votre page, une seule fois, le tag suivant

.. code-block:: html
    :linenos:
    
    <script type="text/javascript">
        (function() {
            var seasonpros = document.createElement('script'); seasonpros.type = 'text/javascript'; seasonpros.async = true;
            seasonpros.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + 'www.seasonpros.com/js/widget.min.js';
            var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(seasonpros, s);
        })();
    </script>

Vous pouvez alors implémenter un widget avec de l'HTML en suivant les consignes expliquées dans les prochains chapitres.
