Pour transformer le script en .exe il faut executer la commande `pyinstaller -F --hidden-import=win32timezone scr.py`.  
Pour installer le service `py scr.py --startup=auto  install`.  
Pour lancer le service `py scr.py start`.  
Le service se lancera automatiquement à chaque démarrage