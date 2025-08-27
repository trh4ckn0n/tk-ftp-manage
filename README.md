# tk-ftp-manage
Just a gui tool for connect to a target with credentials and download big files ...
=====================================================
   FTP Tools with Tkinter GUI - by trhacknon
=====================================================

Ce projet contient deux scripts Python utilisant Tkinter 
pour interagir avec des serveurs FTP de manière simple 
et visuelle.

## for termux...
### if need exec that:

```bash
vncserver -kill :1
rm -f ~/.vnc/*.pid
rm -f ~/.vnc/*.lock
vncserver :1 -geometry 1280x720 -depth 24
```

```bash
export DISPLAY=:1
```

**and open localhost:1 in a vncviewer**


-----------------------------------------------------
1. ftp-get-list.py  
-----------------------------------------------------
📌 Fonctionnalité :
- Permet d'obtenir et d’afficher la liste des fichiers 
  provenant de plusieurs serveurs FTP.
- Tu peux fournir une liste de serveurs, et l’outil 
  tentera de se connecter et de récupérer l’arborescence.
  
structure attendue pour la liste de servers :

[list.txt](https://raw.githubusercontent.com/trh4ckn0n/tk-ftp-manage/refs/heads/main/list.txt)

📷 Capture d’écran :
![https://c.top4top.io/p_3526t9rvw1.jpeg](https://c.top4top.io/p_3526t9rvw1.jpeg)

-----------------------------------------------------
2. main.py  
-----------------------------------------------------
📌 Fonctionnalité :
- Permet de se connecter à un serveur FTP spécifique.  
- Affiche les fichiers et dossiers disponibles.  
- Offre la possibilité de télécharger les fichiers 
  depuis un chemin web/FTP donné.  

📷 Capture d’écran :
![https://b.top4top.io/p_3526s21s50.jpeg](https://b.top4top.io/p_3526s21s50.jpeg)

-----------------------------------------------------
💻 Dépendances :
- Python 3.x
- Tkinter (inclus par défaut avec Python)
- ftplib (inclus par défaut avec Python)

-----------------------------------------------------
▶️ Utilisation :
- Lance `ftp-get-list.py` pour tester la récupération 
  de fichiers depuis une liste de serveurs FTP.
- Lance `main.py` pour parcourir et télécharger 
  les fichiers d’un serveur spécifique.

-----------------------------------------------------
⚠️ Notes :
- Ces scripts sont destinés à la démonstration / test 
  de connexions FTP.  
- Assurez-vous d’avoir les droits nécessaires avant 
  de télécharger ou parcourir un serveur FTP.
