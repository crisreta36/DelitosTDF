Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.

Politécnico Malvinas Argentinas.

Aprendizaje Automático

Autor: Cristian Roman Retamar

Clasificación DelitosTDF

--------------------------------------------------------------------------
Utilizacion de las técnicas de aprendizaje automatico aprendidas a lo largo de la cursada donde se utilizaran en el campo de de los delitos ocurridos en el año 2023 en la provincia de Tierra del Fuego a fin de clasificar eficazmente los delitos esclarecidos (resueltos) y no esclarecidos (no resueltos).
==============================

ENTREGA N 1

EL OBJETIVO PRINCIPAL DEL PROYECTOS ES: Identificar patrones en los incidentes delictivos en Tierra del Fuego, con el fin de mejorar la asignación de recursos de seguridad y prevención para poder esclarecer los delitos que no fueron resueltos. Para lograrlo, construiremos un modelo basado en clasificar eficazmente los delitos en dos categorías: Esclarecidos (resueltos) y No esclarecidos (no resueltos).

PROBLEMA A ABORDAR

Contexto:
El esclarecimiento de delitos es un aspecto crucial en la administración de justicia y en la mejora de la seguridad pública. Un delito esclarecido no solo significa que se ha identificado y aprehendido al responsable, sino también que se ha cerrado un caso, brindando justicia a las víctimas y contribuyendo a la disuasión de futuros delitos. En el contexto de Tierra del Fuego, como en muchas otras regiones, la tasa de esclarecimiento de delitos puede ser un indicador de la efectividad de las fuerzas de seguridad y del sistema judicial.

RELEVANCIA:
Identificar los factores que contribuyen a que un delito sea esclarecido puede ayudar a las autoridades a mejorar sus estrategias de investigación y prevención. El modelo que estamos desarrollando no solo servirá para predecir la probabilidad de que un delito sea esclarecido, sino que también permitirá analizar cuáles son las características más importantes que influyen en el esclarecimiento de un delito.

LAS PREGUNTAS DE INVESTIGACION DE PROYECTO SON:

¿Cuáles son los factores más determinantes que influyen en la probabilidad de que un delito sea esclarecido en Tierra del Fuego?

Esta pregunta busca identificar las características más relevantes dentro del dataset que tienen una mayor influencia en el esclarecimiento de un delito. Analizaremos variables como Zona, Franja horaria, Tipo de Lugar, Hechos, Modus Operandi, entre otras, para comprender su impacto en el resultado de la investigación.


¿Existen patrones en los delitos no esclarecidos que puedan sugerir áreas de mejora en la asignación de recursos y estrategias de prevención?

Investigaremos si hay patrones comunes en los delitos que no han sido resueltos, lo que podría indicar áreas donde los recursos de seguridad pública y las estrategias de investigación necesitan optimización. Esto podría incluir análisis de tiempo, lugar y método delictivo.


¿En qué medida las características del lugar y la hora de un delito pueden predecir la probabilidad de su esclarecimiento?

Evaluaremos cómo variables como la ubicación del delito (por ejemplo, zona y tipo de lugar) y el momento en que ocurrió (como la franja horaria) influyen en la probabilidad de que un delito sea esclarecido. Esto ayudará a entender si ciertos contextos temporales y espaciales son más propensos a ver delitos resueltos.


¿Es posible entrenar un modelo de clasificación supervisado para predecir con precisión si un delito será esclarecido usando las variables disponibles en el dataset?

Esta pregunta se centra en la viabilidad de utilizar datos históricos sobre delitos para entrenar un modelo de clasificación supervisado. El objetivo es evaluar si las variables actuales son suficientes para predecir con precisión el esclarecimiento de futuros delitos.


¿Puede el modelo de clasificación supervisado ayudar a mejorar la toma de decisiones estratégicas para las fuerzas de seguridad pública en Tierra del Fuego?

Nos enfocaremos en cómo las predicciones del modelo pueden ser utilizadas para mejorar la asignación de recursos, la planificación de operaciones y la formulación de políticas de seguridad pública. Esto incluye la capacidad del modelo para proporcionar información accionable que pueda guiar las decisiones estratégicas y tácticas.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data set original delitos-tdf_2023.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Origen y descripción del dataset delitosTDf.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
