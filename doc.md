<!-- A FAIRE :
    Une documentation contenant
    o Une explication détaillée du schéma électrique
    o Au travers d’un texte, la description de votre stratégie utilisée pour réaliser le projet. Soyez le plus exhaustif possible
    o Le diagramme de flux du code
    o Une conclusion concernant les objectifs atteints et non atteint et les améiorations
possibles -->

# Documentation

## Explication du schéma électrique

| Composant         | Pin   | Utilité                                                                                       |
| ----------------- | ----- | --------------------------------------------------------------------------------------------- |
| boutons poussoirs | A2-A5 | déclancher des événements programmé sur la carte comme activer les leds ou démmarer la partie |
| LEDs              | 2-5   | afficher la couleurs dans la séquence                                                         |
| Résistances       | GND   | réduire la tension des LEDs pour les préserver                                                |
| Buzzer            | 7     | Produire un bruit en même temps qu'une LEDs s'allume                                          |

![schema éléctronique](./schema%20electronique.png)


## 