#Wordpress S.E.O Plugin
______________________
  
Ce plugin wordpress ajoutes les balises suivantes dans la partie head de la page web:  
- `<title></title>`
- `<meta property="og:title" content="..." />`
- `<meta name="description" content="..." />`
- `<meta property="og:description" content="..." />`
- `<meta property="og:image" content="..." />`
- `<meta property="og:url" content="..." />`
- `<meta property="og:name" content="..." />`
  
Le but est d'utiliser au maximum ce qui existe déjà dans la configuration ou ce qui est fourni par la page ou l'article.
- Les balises titres utilisenet le titre de l'article ou de la page.  Si aucun titre n'est trouvé le nom du site est utilisé.  
- Le champs **extrait** est activé et il est utilisé pour remplir les meta **description**.  
  Si aucun extrait n'est présent c'est le slogan du site qui est utilisé.
- La meta ***name*** correspond au **titre du site**
- La meta ***url*** correspond à **l'adresse du site**
- La méta ***og:image*** correspond à l'image ***mise en avant***.  
  S'il n'existe pas d'image disponible il est prévu de configurer une image à utiliser par défaut.
  
L'objectif est de permettre de fournir les balises essentielles sans devoir passer beaucoup de temps à faire de la configuration.  
De cette manière l'auteur peut passer plus de temps sur le contenu, à réfléchir à un bon titre et la bonne description.  

