# Azure AI Content Safety

<img width="960" alt="aacs-showpage" src="https://github.com/user-attachments/assets/0dc32856-47df-4699-bdad-b18e7d383b42">


Azure AI Content Safety est un service d'IA qui détecte le contenu nuisible généré par les utilisateurs et l'IA dans les applications et les services. Azure AI Content Safety comprend des API de texte et d'image qui vous permettent de détecter du matériel nuisible. Le Content Safety Studio interactif vous permet de visualiser, explorer et essayer du code d'exemple pour détecter du contenu nuisible dans différentes modalités.

## Analyseur de contenu textuel

Ceci est un exemple d'utilisation de la sécurité du contenu Azure avec Python pour l'analyse de texte.\
Dans ce projet, nous effectuerons les tests suivants :

* Tester comment analyser le texte en utilisant Azure.
* Rechercher toutes les catégories possibles pour filtrer le contenu textuel.
* Tester toutes les catégories pour l'analyse de contenu sur le texte.
* Catégories : Violence, Automutilation, Sexuel et Haine.

## Technologies

* Azure Content Safety
* Python
* Azure SDK
* Flask

## Installation

1. Clonez le dépôt :
    ```sh
    git clone https://github.com/votre-utilisateur/votre-projet.git
    cd votre-projet
    ```

2. Créez et activez un environnement virtuel :
    ```sh
    python -m venv env
    source env/bin/activate  # Sur Windows, utilisez `env\Scripts\activate`
    ```

3. Installez les dépendances :
    ```sh
    pip install -r requirements.txt
    ```

4. Configurez les variables d'environnement dans un fichier `.env` :
    ```
    CONTENT_SAFETY_KEY=your_content_safety_key
    CONTENT_SAFETY_ENDPOINT=your_content_safety_endpoint
    ```

## Utilisation

1. Lancez l'application Flask :
    ```sh
    python 
    ```

2. Ouvrez votre navigateur et accédez à `http://127.0.0.1:5000`.

3. Entrez le texte que vous souhaitez analyser et soumettez le formulaire pour voir les résultats.

## Structure du projet

Analyseur de Contenu Textuel/
├── .env
├── app.py
├── README.md
├── requirements.txt
├── static/
│   └── style.css
├── templates/
│   └── index.html
└── tests/ [ En Cour]
    ├── __init__.py
    └── test_app.py

Description des fichiers et dossiers :
.env : Fichier contenant les variables d'environnement nécessaires pour l'application.
app.py : Fichier principal de l'application Flask.
README.md : Documentation du projet.
requirements.txt : Liste des dépendances Python nécessaires pour le projet.
static/ : Dossier contenant les fichiers statiques (CSS, images, etc.).
style.css : Fichier CSS pour le style de l'application.
templates/ : Dossier contenant les templates HTML.
index.html : Template principal de l'application.
tests/ : Dossier contenant les tests unitaires.
test_app.py : Fichier de tests pour l'application Flask.
