Bienvenue dans DestiNation !


Pour le bon déroulement du jeu, veuillez suivre les instructions suivantes :


 - Associer la base de données et le code.

	∙ Tout d'abord, changer le point d'accès PhpMyAdmin dans la première partie du fichier '..\DestiNation\php\bdd_destination.php'.
	∙ Puis, créer la base de données 'bdd_destination' dans l'espace PhpMyAdmin.
	∙ Enfin, importer le fichier '..\DestiNation\bdd_destination.sql' dans l'espace PhpMyAdmin.


 - Changer le chemin du 'localhost' dans MAMP.

	∙ Choisir comme chemin d'accès : '..\DestiNation\html\'.
	∙ Le navigateur devrait automatiquement se lier au fichier 'index.html' présent dans le dossier.
	∙ Si ce n'est pas le cas, alors choisir le chemin de ce fichier comme étant le chemin d'accès du 'localhost'.


 - Jouer

	∙ Une fois arrivé∙e sur la page d'accueil, vous serez guidé∙e par les indications.
	∙ Il y a des DestiNations assez vastes comme des îles, des lacs. Pour trouver l'objet vous permettant d'avancer dans le jeu, il faut zoomer sur le nom de l'endroit en question.
	∙ Il se peut que certaines DestiNations soient mal placées. La base de données a pris environ 10 heures à être confectionée et il y a eu à coup sûr des fautes de frappe. Veuillez nous en excuser.
   

Calcul du score :


 - Variables : nb_dest -> nombre de DestiNations, dif -> difficulté d'une DestiNation, delta_t -> temps d'une étape, t_code -> temps de déverrouillage du coffre

 - Formule : score = (SOMME(1,nb_dest)(1000000 * dif / sqrt(delta_t)) + (1000000 / (3000 + sqrt(t_code)))) * (1 + 2 * nb_dest / 96)

 - Chaque temps est en millisecondes.



Pour ce qui est de l'implémentation des meilleurs scores, nous n'avons pas su comment faire. L'interface permet de les ajouter mais elle est vide.


Nous espérons que vous allez apprécier notre jeu, Destination !


Clément et Lauris. 
