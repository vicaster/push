Pour le bon fonctionnement de ce script:

Faite la commande "sh deploiement.sh" pour mettre en place le script.

Sinon faites le a la main en suivant les etapes suivantes:
---------------------------------------------------

1- Mettre le script "push.sh" a la racine "~"

---------------------------------------------------

2- Mettre un alias dans "~/.zshrc"
pour cela, exectuter cette commande:

echo "alias push='sh ~/push.sh'" >> ~/.zshrc

---------------------------------------------------

une fois la commande echo faite, il faut fermer le shell et en rouvrir un.

---------------------------------------------------

Maintenant il suffis de faire: "push" dans le repo du .git pour l'utiliser.
Bon push.


---------------------------------------------------


