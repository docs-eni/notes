# Type de mémoire

## ROM (Read-only Memory)

La Rom contien des instruction en lecture seul pour le processeur.

La rom est non volatile

- **ROM** : Neu peut ête ni écrasé, ni effacé, est obsolète.
- **PROM** : Vendue Vierge, peut être programmé une seule fois, puis à la même comportement qu'une ROM.
- **EEPROM** : Peut être effacé avec de l'ultraviolet puissant. L'effacement et la reprogrammation constant peut altéré la mémoire.
- **EEPROM** : Également nommé "*ROM Flash*" car on peut supprimer leur contenu en la "*flashant*". Les EEPROME servent généralement à stocker le BIOS d'un système informatique.

## RAM (Random Access Memory)

la RAM sert à stocker temporairement des données.

Contrairement à la **ROM**, la **RAM** est une mémoire volatile.

L'ajout de RAM améliore les performance.

Ex: Plus il y a de RAM, plus le système peut traiter les donnée, moins il y en a, plus le système doit accéder au disque et la tache est plus longue.

La quantité de RAM installable dépend de la carte mère.

### Type de mémoire RAM

- **Mémoire RAM dynamiqe (DRAM)** :
  - Technologie la plus ancienne, populaire jusqu'au milieu des année 1990.
  - utilisé par la mémoire principal.
  - se décharge progressivement et doit être réactualisé par des impulsions électrique afin de concerver les donnée stocké sur la puce.
- **Mémoire RAM statique (SRAM)** :
  - Nécessite une alimentation constante pour fonctionner.
  - Souvent utilisé pour la mémoire cache.
  - Présente une consomation électrique plus faible.
  - Beaucoup plus rapide que la DRAM.
  - Plus chère que la DRAM.
- **SDRAM** :
  - DRAM qui fonctione en synchronisation avec le BUS de mémoire.
  - Peut traiter les instruction de chevauchement en parallèle; exemple : pour traiter un processus de lecture avant la fin du processus d'écriture.

- **DDR SDRAM (184 broches)** :
  - La **SDRAM DDR** tranfère 2 foix plus vite que la **SDRAM**.
  - Peut prendre en charge deux écriture et deu lecture par cycle d'horloge du processeur.
  - Utilise en tension standard (inferieur à 2,5V).
  - Famille DDR2, DDR3, DDR4
- **DDR2 SDRAM (240 broches)** :
  - La **SDRAM DDR2** tranfère aussi 2 foix plus vite que la **SDRAM**.
  - S'exécute à des débit d'horloge plus élevé que la DDR (533 MHz contre 200MHz)
  - Améliore les performances en réduisant les intérférences et la diaphonie entre les fils de transmission.
  - Utilise en tension standard (inferieur à 1,8V).
- **SDRAM DDR3 (240 broches)** :
  - La **SDRAM DDR3** augment la bande passant de la mémoire en doublant la fréquence horloge de la DDR2
  - Utilise en tension standard (inferieur à 1,5V).
  - Génère moin de chaleur
  - S'exécute à des débit d'horloge plus élevé que la DDR2 (800 MHz contre 533MHz)
- **SDRAM DDR4 (288 broches)** :
  - La **SDRAM DDR4** quadruple la capacité de stockage de la DDR3.
  - Utilise en tension standard (inferieur à 1,2V).
  - S'exécute à des débit d'horloge plus élevé que la DDR3 (1600 MHz contre 800MHz)
  - Disponible avec les fonctionalité avancé de correction d'erreur tel que la mémoire ECC pour détecter les erreur de bits multiple
- **SDRAM GDDR** :
  - **G** signifie **Graphic**
  - Mémoire RAM spécialement conçue pour les graphique vidéo.
  - Utilisé conjointement avec GPU dédié.
  - Famille : GDDR, GDDR2, GDDR3, GDDR4, GDDR5
  - Chaque membre de la famille améliore les performances.
  - Chaque membre de la famille réduit la consommation.
  - La **SDRAM GDDR** traite de grande quantitié mais n'offre pas nécessairement les débits les plus élevés

### Type de Module

- **DIP (Dual Inline Package)** :
  - Comporte 2 rangé de broches pour la fixé à la Carte mère.
- **SIMM (Single Inline Memory Module)** :
  - Petite carte contenant plusieur module mémoire.
  - Il existe 2 type de SIMM, une à **30 broches** ou **72 broches**
- **Mémoire DIMM (Dual Inline Memory Module)** :
  - Carte contenant des puces (**SDRAM**, **SDRAM DDR**, **SDRAM DDR2**, **SDRAM DDR3**, **SDRAM DDR4**)
  - Différentes taille de module existe :
    - **SDRAM DDR** :
    -
- **Mémoire SODIMM** :

```php
php -v
```