# PROMPT_CHARTE_TECHNIQUE  
🎮 Règles techniques que je garderais

Pour un objet indépendant — tombe, citrouille, lanterne, coffre, rocher, panneau, ennemi, etc. :

- PNG avec transparence réelle : aucun fond blanc, noir ou coloré.

- Pas d'ombre portée peinte au sol par défaut. On pourra gérer les ombres/lumières dans Unity. En revanche, l'objet peut conserver ses propres zones sombres peintes : creux dans une pierre, côté sombre d'une tombe, intérieur d'une citrouille, etc.

- Pas de halo lumineux externe peint par défaut. Par exemple, une lanterne peut avoir son verre jaune/orange, mais son grand halo sera plutôt créé avec une Light 2D.

- Objet entièrement visible, rien ne doit être coupé par les bords de l'image.

- Marge transparente autour de chaque objet pour éviter que deux sprites se touchent.

- Vue latérale compatible avec notre side-scroller.

- Même échelle visuelle entre les variantes autant que possible.

- Pas de texte, UI, décor ou objet parasite.

- Contours suffisamment propres et lisibles pour fonctionner une fois le sprite réduit dans le jeu.
