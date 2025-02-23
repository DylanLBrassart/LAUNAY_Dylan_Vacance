# LAUNAY_Dylan_Vacance
Bonjour Monsieur, voilà mon devoir, je suis un peu déçu car je n'ai pas pu faire tout ce que je voulais à l'origine, je me suis retrouvé limité par le temps. J'ai voulu faire un combat de boss et un truc de victoire mais je dois partir prendre mon train et je n'aurai pas mon ordinateur donc je vous le rends ce dimanche 23 car impossible plus tard...

/////////////////

sur ce, dans le projet j'ai fait tout ce que vous avez demandé, soit en ajoutant des trucs, soit à ma manière :

smart bomb : fonctionne en appuyant sur B, lance une grenade qui fait 100 dégâts aux ennemis avec un effet de particules et un son, j'ai rajouté une limite de bombe à 10 qui demande de retrouver d'autres bombes pour se recharger en passant dessus

Pour le flash d'un acteur, je fais flasher le joueur lors de la fin de l'invisibilité. Je n'ai pas fait passer de manière répétitive du matériau d'origine à un matériau blanc, mais j'ai plutôt créé un matériau qui clignote de base

Pour le rayCast, j'ai fait que suite à la récupération d'un item, un petit familier s'ajoute à notre personnage et que c'est lui qui tire les lasers infligeant des dégâts (pas maintenir mais appuyer pour chaque tir ^^)

Il y a 3 cutscenes en tout dans le projet, une qui se lance au début du jeu et deux autres qui se déclenchent uniquement en traversant une zone (trigger box)

Collectible d'invisibilité qui se recuperer avec e qui transforme le joueur pour donner un visuel de l'invincibilité, le joueur ne peut plus perdre de pv mais peut en gagner (si il recupere un objet de soin par exemple) barre qui apparait et donne un compteur j'usqua la fin, lors de la derniere seconde le joueur commence a clignoter avant de redevenir normal et reprends la posibilite de prendre des dégats, si il recupere un deuxieme bonus d'invincibilité le compteur est remis au max et fait donc durée le bonus plus longtemps

Hp flottants sur les ennemis qui tournent en fonction de la position du joueur et est visible que si le joueur peut les voir ( pas de système de distances car je n'ai pas trouvé une méthode qui me plaise. Je vais étudier ça, mais pour l'instant la barre garde la même taille par rapport à l'ennemi donc de loin ne se voit que si on voit l'ennemi mais sera toute petite)

Plateforme à la crashe bandicoot, j'ai deux styles de plateforme, elle se démarre uniquement quand le joueur marche dessus, mais aucune arrête les déplacements du joueur. J'ai essayé mais pas trouvé de méthode qui me permette de les réactiver (bah plutôt je n'arrivais pas à les réactiver). J'ai donc décidé de les laisser ainsi, mais sur une des plateformes qui demande forcément la récupération de l'objet des raycast, une cut scène se lance et coupe les contrôles, ça compte ^^? (avec plus de temps, j'aurais sûrement trouvé, mais manque de temps)

Pour les dégâts de chute, j'ai utilisé la vélocité bien que moins optimisée. Cela fonctionne et plus on tombe de haut, plus on prend de dégâts de chute. De plus, on a un Stun à l'atterrissage :)

/////////////////

Problème rencontré que je n'ai pas réussi à résoudre :
J'ai rencontré beaucoup de problèmes, que ce soit mineurs ou majeurs. J'ai corrigé certaines parties, mais voilà certaines non résolues :'(

Compteur d'invincibilité : si on prend qu'un bonus, le compteur disparaît à la fin de l'invincibilité, mais si on en prend plusieurs, le compteur ne disparaît pas (prendre plusieurs en même temps)

Parler au NPC, j'ai essayé de désactiver les mouvements, mais je n'ai pas trouvé comment. Étant donné que j'ai besoin des inputs, je ne peux pas disable les inputs lors du dialogue

comme dit plus tôt, réactiver les inputs après la plateforme

Gravité de la bombe, la bombe actuellement se pose directement au sol mais je voulais qu'elle apparaisse au centre et devant de notre personnage mais si je mettais de la gravité elle se mettrait à rouler ce que je ne souhaitais pas. Donc je l'ai rendue solide de sorte à ce qu'elle ne bouge plus mais ce n'était pas l'effet recherché (de plus elle gêne le joueur s'il essaye d'avancer et de poser des bombes) en même temps

 J'ai aussi une de mes plateformes qui tremble légèrement, en soi c'est léger et ne pose pas trop de soucis mais je n'ai pas réussi à retirer cet effet de tremblement. De plus, c'est que l'une de mes deux plateformes reste stable alors que pourtant c'est une duplication de celle qui tremble, donc je ne comprends pas la cause

/////////////////

Voilà Tout les problèmes auraient pu être résolus avec plus de temps et j'aurais pu finaliser, mais obligé de m'arrêter là

PS : niveau level design, c'est vraiment pas incroyable. Désolé, je voulais que vous puissiez tester tout de manière assez rapide de sorte à ce que vous ne preniez pas trop de temps pour tout tester afin de gagner du temps pour corriger tous les devoirs :)


Developed with Unreal Engine 5
