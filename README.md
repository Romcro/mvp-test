# mvp-test

forest-health-detection/
│
├── app/                     # Code de l'application FastAPI
│   ├── main.py              # Point d'entrée de l'application
│   ├── models/              # Schémas de validation (Pydantic)
│   ├── services/            # Fonctions de traitement des images
│   ├── utils/               # Fonctions utilitaires
│   └── routers/             # Routes FastAPI
│
├── data/                    # Données locales et résultats
│   └── sentinel2/           # Images Sentinel-2
│
├── tests/                   # Tests unitaires et fonctionnels
│   └── test_main.py         # Tests pour l'application FastAPI
│
├── Dockerfile               # Fichier Docker pour le déploiement
├── environment.yml          # Dépendances Conda
├── requirements.txt         # Dépendances Python
├── .gitignore               # Fichiers à ignorer par Git
└── README.md                # Documentation du projet
