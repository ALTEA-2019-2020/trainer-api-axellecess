# Trainer API
### Par Cess Axelle - M2 MIAGE FA

Ce projet est pour la gestion des objets de type "Trainer".  
Il est déployé sur Heroku, accessible à ce lien : **https://trainer-api-juwit-cess.herokuapp.com**.

Il est aussi accessible localement au port **8081**.

Avec les endpoints :
- /trainers/ => Pour récupérer tous les trainers
- /trainers/{name} => Pour récupérer le trainer de nom name

La sécurité est aussi mise en place sur ce projet.
<details>
  <summary>Identifiants publics</summary>
  
  ```javascript
  userName = user
  password = 4fca73f0-c17d-4039-9b85-a00197e2322a 
  ```
  
</details>

Il y a une collection Postman pour tester les fonctionnalités disponibles dans le dossier src/test/resources.
