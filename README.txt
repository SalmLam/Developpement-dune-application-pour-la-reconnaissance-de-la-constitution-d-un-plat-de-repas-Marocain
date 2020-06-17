L'apprche HOG + SVM:

-Le fichier feature_sourcer_test permet de visualiser l'extraction des features HOG.

-Les fichiers ipynb suivant sont pour extraire les caractéristiques HOG depuis les images de training positives et negatives:

    *Le fichier Pomme de terre classifier_training.ipynb: pour entrainer le modele des pommes de terre.
    *Le fichier Poulet_classifier_training.ipynb: pour entrainer le modele Poulet.
    *Le fichier olive_classifier_training.ipynb: pour entrainer le modele des Olives.
    *Le fichier hamberger_classifier_training.ipynb: pour entrainer le modele Hambeger.

-Les fichiers ipynb suivant sont pour Tester les modèles entrainés: 
    *Le fichier Pomme de terre classifier_test.ipynb: pour tester le modele des pommes de terre.
    *Le fichier olive_classifier_test.ipynb: pour tester le modele des olives.


-Les fichiers ipynb suivant sont pour Tester les modèles entrainés et localiser les ingrédients dans les images en utilisant la methode Sliding window :
     *Le fichier Pomme de terre slider_test.ipynb: pour detecter les pommes de terre.
     *Le fichier Poulet_slider_test.ipynb: pour detecter du poulet.
     *Le fichier slider_test-Olive.ipynb:: pour detecter les Olives.

-Les fichiers: - helpers.py - featuresourcer.py - binaryclassifier.py - slider.py sont des modules python contenant des classes qu'on a utilisé dans cette approche.
-Les fichiers scaler.pkl et svc.pkl sont les modèles entrainés sauvegardés.

-Les dossiers: Hamberger; poulet; olive; cropedPT contient quelques images positives(non toutes) utilisés dans l'entrainement positives pour donnée une idée sur la dataset.
-Les dossiers: no_Hamberger; no_poulet; no_olive; NoPTC contient quelques images négatives(non toutes) utilisés dans l'entrainement négatives pour donnée une idée sur la dataset.