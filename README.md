## Mise en place de l'environnement de Formation

## configuration de git localement pour palier au problème d'authentification(plusieurs comptes sur un seul appareil)


- git config --local user.name "Mir-del-dev"
- git config --local user.email "email-du-compte-mir-del-dev@exemple.com"

# Ensuite on demande à git de se connecter avec cet username

- git config --local credential.https://github.com.username Mir-del-dev