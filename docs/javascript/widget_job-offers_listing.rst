Widget listing des offres d'emplois
====================================


.. image:: /_images/widget_job_offers.png
   :alt:   Widget listing des offres d'emplois
   
Le widget des offres d'emplois permet à vos visiteurs de consulter les dernières annonces dans toute la france directement depuis votre site internet. 

Voici un exemple d'implémentation :

.. code-block:: html
    :linenos:
    
    <div class="seasonpros-widget" data-widget="offers" data-partner-id="mon-id-partenaire">
    </div>
    
    
Paramètres disponibles
-----------------------

+-----------------+-------------+------------------------------------------------+
| Paramètre       | Obligatoire | Description                                    |
+=================+=============+================================================+
| class           | Oui         | Doit être égal à 'seasonpros-widget'           |
+-----------------+-------------+------------------------------------------------+
| data-widget     | Oui         | Type du widget, ici doit être égal à 'offers'  |
+-----------------+-------------+------------------------------------------------+
| data-partner-id | Non         | Votre tag partenaire.                          |
+-----------------+-------------+------------------------------------------------+
| data-height     | Non         | Hauteur du widget                              |
+-----------------+-------------+------------------------------------------------+
| data-width      | Non         | Largeur du widget                              |
+-----------------+-------------+------------------------------------------------+

.. note::
    Vous pouvez demander votre clef partenaire à contact@seasonpros.com

