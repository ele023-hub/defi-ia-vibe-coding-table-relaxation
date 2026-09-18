# Défi vibe coding : la table de relaxation

Application web ludique et hypnotique : une "table musicale" réagit au clic (ou au tap) par un effet visuel et un son généré en temps réel, dont les caractéristiques se règlent depuis un panneau de commande.

## Contexte

Exercice réalisé dans le cadre d'un cours sur l'usage de l'IA en développement. Consigne : reproduire le plus fidèlement possible une mini-application montrée en vidéo, en dialoguant uniquement avec un agent IA — aucune ligne de code modifiée manuellement, toute correction devant passer par le prompt. Le résultat final ainsi que la formulation des prompts ont ensuite été évalués, notamment sous l'angle de leur sobriété (score de dépendance à l'IA).

## Fonctionnement

- Une "table musicale" occupe l'essentiel de l'écran, avec un fond en dégradé animé par des bandes diagonales translucides qui se déplacent en boucle
- Chaque clic ou tap déclenche un son et fait apparaître un cercle qui s'agrandit et s'estompe à l'endroit précis de l'interaction
- Un panneau de commande permet de choisir le type de son, la tonique et la gamme : chaque changement s'applique immédiatement aux sons suivants
- Les notes jouées restent aléatoires (graves ou aiguës) mais cohérentes avec les paramètres choisis

## Stack

- HTML / CSS / JavaScript (aucune librairie)
- Web Audio API pour la génération sonore en temps réel

## Remarque

Le code de ce projet n'a pas été écrit à la main : il est le résultat d'un pilotage entièrement par prompt, affiné sur plusieurs itérations (ajustement des courbes d'animation, de l'opacité des couches visuelles, de la réactivité du son aux paramètres), dans le cadre d'un exercice pédagogique visant à évaluer la précision des consignes données à un agent IA plutôt qu'une compétence de développement.
