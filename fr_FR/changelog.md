# **Change Log**

# 1.0.L Version du 08/11/2020

- Refactorisatiuon du code,
- Ajout d'une commande **Off** qui permet d'éteindre la Smart Tv depuis un scénario.
- Correction bug sur gestion du WOL ( wake on lan).

# 1.0.L Version du 27/04/2020

- Refactorisation du code 
- Ajout d'une commande 'Off' afin d'éteindre la télévision depuis un scénario,
- Correction bug sur le traitement du Wake on lan (WOL), 
- Pour le paramètre WOL, fonctionnement soit en mode direct sur l'IP de la télévision soit en mode broadcast , dans ce cas renseigner le masque de sous-réseau.
  

# 1.0.K Version du 27/04/2020

- Amélioration de l'affichage de la télécommande suivant le média utilisé: PC, tablette ou téléphone mobile.

# 1.0.J Version du 13/03/2020

- Correction de l'affichage du widget : dashboard et design.

- Permettre de redimensionner et de placer le widget sur un design.


# 1.0.I Version Beta

- Ajout d'un paramètre de latence pour envoi séquence de touche depuis un scénario.

# 1.0.H Version Beta 

- Correction typo pour fichiers I18n

# 1.0.G Version Beta 31/12/2019

- Mise à niveau widget en conformité avec jeedom V4
- Correction bug lié suppression de l'entité objet replacée par jeeObject

# 1.0.D Version Beta 04/04/2019

- Prise en compte des Smart Tv Samsung modèles J
- Paramétrage du temps de pause nécessaire lors de l'envoi d'une séquence de touches.(Utilisé dans les scénarios, par exemple).

# 1.0.C Version 18/12/2018

- Prise en compte du firmware d'Octobre 2018 pour les modèles de Tv Tizen.
  Pour ces modèles il faut configurer le port 8002 et le mode SSL.

  > Si vous n'avez pas installé le dernier firmware sur votre Smart Tv Tizen , il faut rester sur le port 8001 SSL off.

- Ajout d'une commande wake on lan, pour les modèles Tizen.

# 1.0.B Version 01/12/2018

- Version intermédiaire, non diffusée.

# 

# 1.0.A Version 25/11/2018

* Modèles `Legacy` série ES modification du protocole de communication: ajout d'une séquence d'authentification. 


# 1.0.9 Version 30/05/2018

* Modèles de TV de type K, paramètrage délai d'attente avant déconnexion.
Pour cela un paramètre de configuration a été ajouté dans le module de description des équipements.

# 1.0.8 Version 22/04/2018

- Ajout protocole de communication spécifique aux modèles de TV de type K.

- Pour cela un paramètre de configuration a été ajouté dans le module de description des équipements.

# 1.0.7 Version 03/04/2018

* Correction bug de communication : ajout paramètre à al connexion webSocket.
* Fourniture template affichage widget.

# 1.0.6 Version 05/03/2018


   * Correction bug affichage de la télécommande : centrage, couleur, format d'affichage
   * ajout commande générique pour appel depuis scénario. Voir liste jointe des commandes sous /doc. Egalement en annexe.


# 1.0.5 Version 18/01/2018

   * Intégration des TV Samsung année 2014 et suivantes, plate-forme Samsung Tizen
        Le plugin est compatible pour les modèles antérieurs à 2014.

> **Tip**
>
> Attention, pour l'instant seuls les modèles > à 2014 nommés QLED, M et K semblent fonctionner. les modèles J et H ne fonctionnent pas.


# 1.0.4 Version 10/07/2017

   - Mise à niveau jeedom V3.


# 1.0.3 Version 12/03/2016

  * Réduction de la taille d'affichage de la télécommande
  * Possibilité de personnaliser le fond d'écran de la télécommande 
  * Possibilité de personnaliser la couleur des labels en conjonction du fond d'écran
  * Ajout de commandes pour pilotage au travers de scénarios.
  * Corrections mineures pour création fichiers I18n
  * Configuration : association automatique widget de lancement
  * Mise à niveau automatique de la configuration du plugin pour les configurations déjà existantes

# 1.0.1 Version 02/03/2016

  * Ajout des screen-shots de l'application

# 1.0 Version initiale - Fév 2016

   - Fourniture du plugin, du widget et de la documentation.

   - Tests réalisés sous jeedom 1.212 et mini+ 

   - Tests réalisés sous jeedom 1.212 et VirtualBox

   - Tests réalisés sous jeedom V2    et VirtualBox

     
