# Réponses de cadrage validées

## A. Gameplay

1. **Combien de questions par partie ?**  
   Jusqu'à élimination : toute mauvaise réponse élimine le joueur.
2. **Barème des points ?**  
   Même progression que "Qui veut gagner des millions" (adaptée en points).
3. **Paliers de sécurité ?**  
   Oui, les mêmes paliers que l'émission d'origine.
4. **Comportement des 3 jokers ?**  
   Voir proposition validable dans `docs/requirements.md` (1 gratuit/jour + 2 jokers payants).
5. **Joker gratuit : fréquence ?**  
   1 fois par jour.
6. **Jokers payants : achat ?**  
   À l'unité + packs.

## B. Économie et paiements

1. **Monnaies supportées ?**  
   XPF et USD.
2. **Fournisseurs de paiement ?**  
   Apple/Google in-app + paiement SMS surtaxé.
3. **Expiration des points ?**  
   Les points expirent à chaque changement de boutique (1 fois/mois).
4. **Conversion points → cadeaux ?**  
   Clarifié dans les exigences : chaque cadeau a un coût fixe en points, visible en boutique.

## C. Comptes et sécurité

1. **Inscription/connexion ?**  
   Email + téléphone avec double authentification.
2. **Vérification d'identité gros cadeaux ?**  
   Oui : pièce d'identité + selfie.
3. **Limitation multi-comptes ?**  
   Oui : 1 compte par personne.
4. **Cadre légal données personnelles ?**  
   Conformité loi française / RGPD.

## D. Anti-triche détaillé

1. **Perte réseau = défaite immédiate ?**  
   Non.
2. **Tolérance latence ?**  
   La plus courte possible.
3. **Timer contrôlé par serveur ?**  
   Oui (décision produit recommandée et retenue).
4. **Journalisation comportements suspects ?**  
   Oui : 1 avertissement puis bannissement à vie en cas de récidive.

## E. Produit & design

1. **Charte graphique ?**  
   Non, à créer.
2. **Langues au lancement ?**  
   Français + anglais.
3. **Ton produit ?**  
   Fun.
4. **Mode invité ?**  
   Oui, limité à 2 connexions ; pas d'accès boutique sans compte créé.

## F. Opérations

1. **Base de questions ?**  
   À construire, thèmes et niveaux variés ; un joueur ne doit pas revoir la même question dans la même année.
2. **Administration boutique/stocks ?**  
   Le client et ses collaborateurs.
3. **Back-office MVP ?**  
   Oui.
4. **Date cible ?**  
   Première version attendue immédiatement.
