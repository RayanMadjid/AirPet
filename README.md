# AirPet

AirPet est un premier projet de recherche en intelligence artificielle : un petit compagnon volant qui réagit à ta présence, à ta voix et à son environnement, tout en respectant des règles de sécurité strictes.

## Vision

Créer une IA qui se comporte comme un « petit animal de compagnie volant » (dans l’esprit d’un microduck), avec des réactions simples, lisibles et sûres.

## Boucle de fonctionnement (prototype)

Caméra / micro  
↓  
Détection simple : personne, main, voix, mouvement  
↓  
État émotionnel simulé : **curieux · calme · joueur · fatigué**  
↓  
Choix d’un comportement sûr  
↓  
Pilote humain ou commandes très limitées au drone

## Comportements à développer (ordre recommandé)

1. Réagir à ta présence : orientation, petit son, LED/couleur.  
2. Se poser près d’un point sûr quand tu l’appelles.  
3. Suivre lentement une balise ou une personne, avec distance minimum.  
4. Explorer une petite zone autorisée et revenir à sa base.  
5. Créer une personnalité : curiosité, hésitation, enthousiasme, repos après plusieurs vols.

## Sécurité et stratégie de prototype

Pour un premier prototype, éviter le vol autonome extérieur : l’Air75 est très léger, sensible au vent et possède environ 6 minutes d’autonomie.

Approche recommandée :

- D’abord des réactions au sol, hélices désarmées.
- Ensuite des vols très courts en zone protégée.
- Télécommande toujours active.
- Bouton d’arrêt d’urgence.
- Limite stricte de vitesse.
- Zone virtuelle stricte (géorepérage).
