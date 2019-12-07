Une application qui peremt a un utilisateur :

- de s'inscrire
- de connecter avec un compte existant
- de stocker les coordonnees d'une peronne
- en tant que utilisateur simple je doit voir que les contacts que j'ai cree
- en tant que super utilisatuer j'ai le droit de voir tous les contacts

Pour chaque contact nous devons enregistrer :

Conatct

- une id(type = cle primaire) - Int(auto)
- un nom (type = varchar, longeur = 150) - CharField(max)
- un prenom (type = varchar, longeur = 150) - CharField(max)
- un numero de telephone (type = varchar, longeur = 150) CharField(max)
- un email (type = varchar, longeur = 150) EmailField(max)
- une date d'enregistrement (type = Date TimeStamp) DateTime(auto)
- L'utilisateur qui l'a cree (type = Cle etrangere) ForegntKey()

CRUD
C- Create, creer
R- Read, lecture
U- Update, modifier
D- Delete, Supprimer
