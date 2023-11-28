
##  les commandes  utiliser  pour faire le travail 

1. **Vérification de la Branche Actuelle (master):**

    ```bash
    git branch
    git checkout master
    ```

2. **Création des Branches pour Hussein et Yasmine:**

    ```bash
    git checkout -b hussein master  # Hussein travaille sur sa branche

    git checkout master  # Revenir à la branche master

    git checkout -b yasmine master  # Yasmine travaille sur sa branche
    ```

3. **Fusion des Branches de Travail dans Master:**

    ```bash
    git checkout master  # S'assurer d'être sur la branche master

    git merge hussein   # Fusionner la branche hussein dans master
    git merge yasmine   # Fusionner la branche yasmine dans master
    ```
