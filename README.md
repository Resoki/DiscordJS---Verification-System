/* Discord bot made by Resoki /*

**Installation**
Ouvrir un terminal et verifier qu'on se situe bien dans le dossier 

```diff
+ npm install 
+ npm start 
```

Changer le token dans Config/global.json

**Utilisation**
Pour qu'un utilisateur verify son compte > !verify
un code lui sera demandé, exemple :  !verify 123234
Son profil sera ensuite verifié, il recevra le rôle 'Verifie', réglable dans Config/global.js à *roleVerified*
Il faut regler coté serveur discord le role Verifie pour faire en sorte que si l'user n'as pas le role verifie qu'il voit seulement quelques channels, par exemple.
Une log est envoyé > *channelLog*
