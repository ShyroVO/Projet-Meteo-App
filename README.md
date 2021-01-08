# Projet-Meteo-App

Projet : Application météo

Consignes :

- Vous allez réaliser une application météo à l'aide de l'API gratuite d'openweathermap
- Rendez vous sur https://openweathermap.org/price et souscrivez à l'option gratuite
- Vous trouverez ici la documentation de l'api : https://openweathermap.org/current#one
- Vous utiliserez ce JSON renvoyé avec Javascript/ajax pour afficher à l'utilisateur les informations météo
- L'appli doit être responsive
- Utilisez la maquette fournie pour réaliser l'interface de l'appli

N’hésitez pas à vous aider les uns les autres ! L’utilisation d’une API et d’une documentation n’est pas forcément quelque chose de facile lorsque c’est la première fois !


Théorie.

JSON veux dire JavaScript Object Notation, le texte renvoyé l'est sous forme d'objet, exemple :

let text = '{"propriete1" : valeur1, "propriete2" : valeur2}';

En javascript, on utilisera la méthode JSON.parse() pour convertir ce texte en un objet exploitable :

let text2 = JSON.parse(text);

On pourra par la suite acceder aux propriétés de l'objet de cette façon :

 text2.propriete1
