# Module-320-EPSIC

Modifications (diagramme a)

Enlevé la classe Employee car elle ne sert a rien

Séparé la prop « Name » en deux : firstname et lastname 
Modifié le type de retour de la fonction registerCustomer de Customer à void car la fonction n'effectue aucune opération nécessitant un retour de valeur. Le seul besoin est de savoir que l'opération s'est bien déroulée.

Déplacé les méthodes credit et debit de BankAccount vers Bank, en ajoutant un paramètre BankAccount. Cela permet de centraliser la gestion des transactions au niveau de la banque, plutôt que de laisser chaque compte se gérer lui-même. Cette modification améliore la sécurité en empêchant un compte de se créditer des sommes importantes sans l'autorisation préalable de la banque.

Ajout de la propriété Owner à BankAccount pour qu’on puisse identifier à qui appartient un compte

Ajout de la propriété BanksAccounts à Bank pour que les comptes soient stockés quelque part

Ajout de la relation de Composition entre Bank et BankAccount

