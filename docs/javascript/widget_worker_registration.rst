Widget enregistrement saisonnier
=================================

.. image:: /_images/image.png
   :alt:   Widget enregistrement saisonnier
   
Le widget saisonnier permet à vos visiteurs de commencer leur inscription directement depuis votre site internet. 
Ce widget ne propose, à ce jour, qu'une inscription saisonnier.

Voici un exemple d'implémentation :

.. code-block:: html
    :linenos:
    
    <div class="seasonpros-widget" data-widget="registration" data-partner-id="mon-id-partenaire">
    </div>
    
    
Paramètres disponibles
-----------------------

==========  ============   =========== 
Paramètre   Obligatoire    Description
----------  ------------   -----------
class       Oui   Doit être égal à 'seasonpros-widget'
data-widget Oui   Type du widget, ici doit être égal à 'registration' 
data-partner-id  Non   Votre tag partenaire. Sans celui-ci les inscriptions ne seront pas identifiées comme provenant de chez-vous  
data-height   Non  Hauteur du widget
data-width    Non   Largeur du widget
