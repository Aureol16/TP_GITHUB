Le TP1 ET TP2 inclut les fichiers code.py et module.py 
Observation du conflit
Ouvrir code.py :
<<<<<<< HEAD
print("Version A du code")
=======
print("Version B du code")
>>>>>>> conflit-b
Ces marqueurs indiquent le conflit.
<img width="1909" height="688" alt="Capture d&#39;écran 2025-12-02 133925" src="https://github.com/user-attachments/assets/ce2fd187-9519-471b-8cb2-4446614ffb0e" />

 Résoudre le conflit
Choisir une version finale (par exemple) :

print("Version finale du code après résolution du conflit")
Valider la résolution :

git add code.py
git commit -m "Résolution du conflit entre conflit-a et conflit-b"
git push origin main

Le TP4 inclut les dossiers Data; Notebook; rapport détaillé TP4

Dans le dossier Data vous verrez le fichiers events 
Dans le dossier Notebook vous verrer le fichier TP4_AB_Testing.ipynb 
Dans le dossier Rapporte détaillé vous verrez le fichier pdf du rapport détaillé 
