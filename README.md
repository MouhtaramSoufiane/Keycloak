<p align="center">
 <img width="100px" src="https://www.keycloak.org/resources/images/icon.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">Keycloak</h2>
 <p align="center">Keycloak est une solution open source d'identité et d'accès (IAM) qui fournit une gamme de fonctionnalités pour sécuriser les applications et les services. Il comprend la prise en charge de l'authentification, de l'autorisation, de l'authentification unique (SSO) et plus encore.</p>
</p>
</p>




### Télécharger Keycloak 

![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/34708c63-5071-4e52-b39a-bd2fd94a8296)

### Démarrer Keycloak

 * Localisez le répertoire d'installation de Keycloak.
 * Accédez au répertoire bin.
 * Exécutez le script ``` kc.sh start-dev ```.

  ![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/2119a06d-88a0-42d7-813e-641d43af10cb)

### Créer un compte Admin
* Aprés la création on va faire <strong>Login</strong> .
![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/78d21ed3-d8f8-4120-8b4d-a51320fe9bab)

### H2 Database Keycloak

 * Localisez le répertoire d'installation de Keycloak.
 * Aprés deplacer vers ``` \lib\lib\main ``` .
 * Exécuter sur enligne de commnade ou vous etes ``` java -jar com.h2database.h2-2.2.220.jar ```
 * Entrer ``` https://locahost:8082 ```


![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/1ab186da-6291-44d6-918d-71441121ae7f)


###  Créer une Realm

![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/1ec44a34-24cb-491e-ad78-6e146e431749)

### Créer un client à sécuriser

![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/de6b0106-2faf-42b7-a838-54b42b77b596)

### Création des Utilisateurs

![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/9397528d-8691-43c2-ba4d-fe530ef62b04)

### Création des Rôles 

![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/c538f7f7-9b96-4221-a077-31e70c4a3060)

### Assigner les rôles à les utilisateurs

![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/22514a3f-9824-4fe7-ab33-6c96052badd3)

### Postman
*  Tester l'authentification avec le mot de passe
  
  ![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/f830d48a-a2ff-4659-9ca6-d5539c94d756)

*  Analyser les contenus des deux JWT Access Token et Refresh Token

   ![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/01861a13-23d5-4616-8655-93919ef20b70)

  
*  Tester l'authentification avec le Refresh Token

   ![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/3016f9cc-8a76-4fbf-b9ed-7c7628e5eb7c)
   
*  Tester l'authentification avec Client ID et Client Secret

  ![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/262d8e77-3391-4b80-801a-a812b92aa5a5)
  

*   Changer les paramètres des Tokens Access Token et Refresh Token

  ![image](https://github.com/MouhtaramSoufiane/Keycloak-UI/assets/104082651/51239e4b-3b14-4eb8-ba61-0d91074b7d00)


 






