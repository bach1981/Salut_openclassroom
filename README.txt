Le projet: Cr�er une page internet!

Apr�s l'installation de git et sa configuration gr�ce � :

git config --global user.name "xxxxxxxxx"
git config --global user.email "xxxxxxxxx"

1-   Cr�er un dossier "Salut" gr�ce � la commande mkdir ==> mkdir Salut
2-   Pointer sur ce dossier avec la commande cd ==> cd Salut
3-   Dire � git de versionner et initialiser le projet avec la commande git init ==> git init
4-   Consulter ce qui se passe sur mon projet gr�ce � git status ==> git status 
     Il nous dit que nous avons rien dans le projet pour l'instant
5-   Cr�er un autre fichier httml dans le dossier Bonjour, on va le nommer hi.html
6-   Rajouter ce code ( j'ai utilis� Notepad++ pour la saisi du code)

<!Doctype html>

<html>
<head>
<Title></title>
<meta charset="utf-8">
</head>

<Body>
<h1> Salut</h1>

</Body>
</html>


7-   Rajouter du code css dans hi.html

<style type="text/css">
     h1 {
 position: absolute;
top: 40%;
width: 100%;
front-family: Helvetica;
front-size: 100
text-align: center;

}
</style>
8-   Tracker notre fichier index.html avec la commande git add ==> git add index.html
9-   V�rifier le statut avec git sttus  (le nom est vert)
10-  Cr�er un commit avec la commande git commit --message"D�placer texte"


