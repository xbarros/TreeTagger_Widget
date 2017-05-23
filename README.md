.. meta::
   :description: Orange Textable Prototypes documentation, TreeTagger 
                 widget
   :keywords: Orange, Textable, Prototypes, documentation, TreeTagger,
              widget

.. _TreeTagger:

TreeTagger_Widget
=================

img...

Annote les textes entrant en type et lemma grâce à `Treetagger 
<http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/>`_ .

Permet la lemmatisation et l'étiquetage morphosyntaxique d'un texte.

Auteur
------

Xavier Barros

Signals
-------

Inputs: 

   Corpus texte (ex: Text Fiels, Text Files, tec...)

Outputs:

* ``Text data``

  Segmentation contenant le texte rentré annoté (type et lemma)

Déscription
-----------

Ce widget est conçu pour annoté un ou plusieurs textes dans Orange Canvas. 
Le widget fait appel à Treetagger afin d'annoté le contenu entrant.
Il renvoie une seguementation sous format texte ou xml contenant un segment par entrée.
Chaque segment a 3 annotations: un *id*, le *lemma* et le *type*.

L'interface de Treetagger Widget est disponible en deux versions.
La première apparait si le lien vers TreeTagger n'est pas rentré et bloque les fonctionnalité du widget.
La deuxième apparait lorsque le lien est rentré et permet une utilisation normale.

Lien vers Treetagger inconnu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Il faut aller chercher le lien vers le dossier Treetagger qui doit contenir un certain nombres de fichiers:

* ``cmd/tokenize.pl``

* ``cmd/utf8-tokenize.perl``
* ``bin/tree-tagger``


Lien vers Treetagger rentré
~~~~~~~~~~~~~~~~~~~~~~~~~~~


