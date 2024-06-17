![image](https://github.com/JSuarez-Arg/Machine-Learning-Model/assets/143549136/0a9f62e9-2b2b-4cd4-8fcf-f4d4f3ad9ec4)
## Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial

## Machine Learning Model: "Predicción de la Producción de Petróleo y Gas en Pozos No Convencionales en Tierra del Fuego"
## Objetivo del Proyecto:
El objetivo principal de este proyecto es desarrollar modelos de aprendizaje automático para predecir la producción de petróleo y gas en pozos no convencionales en Tierra del Fuego. Esto permitirá a las compañías petroleras y a las autoridades gubernamentales tener una mejor comprensión de la producción esperada de estos pozos, lo que puede influir en la planificación y la toma de decisiones en la industria del petróleo y gas en la región.

## Contexto y Relevancia:
Tierra del Fuego es una región importante en Argentina para la industria petrolera y gasífera, con una cantidad significativa de pozos no convencionales en producción. La producción de petróleo y gas en esta región es crucial para la economía nacional y regional, así como para el suministro de energía del país. Sin embargo, la producción en pozos no convencionales puede ser más volátil y difícil de predecir en comparación con la producción en pozos convencionales, lo que hace que el desarrollo de modelos predictivos sea especialmente relevante.

## Preguntas de Investigación:
* ¿Es posible predecir con precisión la producción de petróleo y gas en pozos no convencionales en Tierra del Fuego utilizando técnicas de aprendizaje automático?
* ¿Qué características de los pozos, como la profundidad, la formación productiva y la ubicación geográfica, tienen mayor impacto en la producción de petróleo y gas?
* ¿Cuál es el rendimiento comparativo de diferentes algoritmos de aprendizaje automático en la predicción de la producción de petróleo y gas en pozos no convencionales?
* ¿Cómo varía la producción de petróleo y gas a lo largo del tiempo en diferentes pozos y formaciones en Tierra del Fuego?


<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>



## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for {{ cookiecutter.module_name }}
│                         and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── {{ cookiecutter.module_name }}                <- Source code for use in this project.
    │
    ├── __init__.py    <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py
```

--------

