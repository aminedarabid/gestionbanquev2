- Dans Mysql, cr�er une table "gestionbanque" et importer le fichier "gestionbanque.sql"

- Pour executer le JAR, execut� l'invite de commande et ce positionnant dans le repertoire du fichier jar, puis taper la commande:
java -cp gestionbanquev2-presentation-1.0.jar;gestionbanquev2-domaine-1.0.jar;gestionbanquev2-service-1.0.jar;gestionbanquev2-dao-1.0.jar;mysql-connector-java-5.0.5.jar fr.Aminecorp.presentation.GestionBanque

- Un nom vous sera demand� pour vous authentifier. Le nom est "DARABID" (en minuscule ou majuscule).
- une fois authentifi�, un menu apparaitra :
	- Choix numero "1" pour consulter votre demande.
	_ Choix numero "2" pour retirer de l'argent.
		- vous devrait indiquer un montant de retrait qui soit inf�rieur � votre solde