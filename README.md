# Solid principles :

- 1 : Single responsability : </br> 
  une classe/ fonction doit avoir une seule raison. (envoit de mail dans une class Mail creation de fichier dans une classe)
- 2 : Open closed principle : </br> une classe est ouverte a l'extension est férmé a la modification. </br>
      Afficher le detail d'un user( Custmer, User, supplier) dans ce cas on crée un interface avec la fonction getName et la classe User et Customer doit implementer cet interface. et apres dans chaque classe on defini l'affichier du user. <br>.
      displayWelcomeMessage(NameableInterface $entity) </br>
- 3 : Liskov substitution principle : </br>
      L’idée du principe est que les enfants ne peuvent pas faire plus ou moins que leur parent. (Type de retour ,nombre des parametres , exeptions)
- 4 : Interface Segregation Principle : </br>
      Il faut pas forcé les classes d'implementer les methodes et fonctions. (Penser à l'umplementation multiple).
- 5 : Dependency inversion principle : </br>
      Passer un interface en parametre et non pas un object ( interface avec la methode pay() ...)
  
   
