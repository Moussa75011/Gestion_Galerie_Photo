# Pagination-Téléverssement-récurssif  
Création d'un systeme en PHP perméttant le téléverssement d'images, de parcours de dossier et sous dossier complétés d'un système de pagination pournaviguer d'une page a l'autre de la galerie photo.Un bouton scan permet egalement l'affichage du répértoire d'un dossier dont les noms, les chemins..., s'il s'agit d'images, sur une page web. De plus il est possible de supprimer les images lorseque nous sommes connécter en tant qu'admin.   

## IMAGES

![ recursive ]( https://github.com/Moussa75011/tp4_recudir_delect/blob/master/Screenshot%202022-04-08%20at%2023.36.01.png )
![ recursive ](https://github.com/Moussa75011/tp4_recudir_delect/blob/master/Screenshot%202022-04-09%20at%2000.46.26.png)


# Instalation

- 1 Installer Mamp  
- 2 placer le dossier phpupload dans Mamp /htdocs  
- 3 configurer votre base de donnée de sorte a ce que le programme puisse s'y connecter (Dans notre programme la base de donnée s'appelle "testexo2" et la table s'apelle "images) 
- 4 Configuer la table 'Users' pour configurer le mot de passe de l'admin 
- 5 lancer xampp Apache/mysql  
- 6 tapper sur votre navigateur http://localhost:8080/phpupload/  

# Utilisation
Vous pouvez séléctionner une image au travers du bouton "Choisir un fichier" ensuite vous cliquer sur envoyer  

Ensuite vous pouvez voyager au travers des pages a l'aide du systeme de pagination.  

De plus vous pouvez appuyer sur le bouton "Scann" pour scanner toutes les photos du fichiers docs et les ajouter a la collection et en meme tant afficher le répértoire.  

Il est possible de se connecter en tant qu'admin a l'aide du formulaire qui donnera ensuite le droit de débloquer la capacité de supprimer des photos  






