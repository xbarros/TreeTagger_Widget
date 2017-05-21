.. meta::
   :description: Orange Textable Prototypes documentation, TreeTagger 
                 widget
   :keywords: Orange, Textable, Prototypes, documentation, TreeTagger,
              widget

.. _TreeTagger:

TreeTagger_Widget
=================

Author
------

Xavier Barros

Signals
-------

Inputs: None

Outputs:

* ``Text data``

  Segmentation contenant le texte rentré annoté (type et lemma)

Description
-----------

Ce widget est conçu pour annoté un ou plusieurs textes dans Orange Canvas. 
Le widget fait appel à Treetagger afin d'annoté le contenu entrant.
Il renvoie une seguementation sous format texte ou xml contenant un segment par entrée.
Chaque segment a 3 annotations: un id, le lemma et le type.

L'interface de Treetagger Widget est disponible en deux versions.
La première apparait si le lien vers Treetagger n'est pas rentré et bloque les fonctionnalité du widget.
La deuxième apparait lorsque le lien est rentré et permet une utilisation normale.




