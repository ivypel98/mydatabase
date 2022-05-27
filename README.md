# My_Database-
Ceci est conçu pour gérer la location de films d'une cinéma :)

1- Pour ajouter les information d'un film (APOCALYPTO dans notre exemple), vous pourrez utiliser cette requête = " INSERT INTO film (name_film , realisateur , duree , date_sortie ) VALUES (Apocalypto , Mel gibson , 2h18 , 2006/12/08 ) "

2- Vous souhaitez modifier les infos d'un film, par exemple au niveau du realisateur = " UPDATE film SET realisateur = 'Mel Gibbel' WHERE id=1 ; "

3- Supprimer un film 
DELETE FROM film WHERE id=1 ;

4- Ajouter un client = " INSERT INTO client (idclient , name , firstname , email , contact , lieu_de_residence)"

5- Si vous souhaitez afficher les 3 derniers film ajoutés = " SELECT * FROM Gestiondefilm.film ORDER BY idfilm ASC LIMIT 3; "
