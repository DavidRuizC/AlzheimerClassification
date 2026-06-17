# Classificació d'Alzheimer amb imatges PET

Aquest repositori conté el codi desenvolupat per al Treball de Fi de Grau centrat en la classificació de subjectes sans i subjectes amb deteriorament cognitiu a partir d'imatges PET cerebrals de la base de dades OASIS-3.

L'objectiu principal és estudiar l'ús de tècniques de preprocessament, anàlisi exploratòria, models clàssics de Machine Learning i xarxes neuronals convolucionals per a la classificació automàtica d'imatges mèdiques.

## Estructura del repositori

```text
.
├── Preprocessing.ipynb
├── EDA.ipynb
├── MachineLearning.ipynb
├── CNN.ipynb
└── README.md
```

## Descripció dels notebooks

### Preprocessing.ipynb

Conté el procés de preparació de les dades. Inclou la càrrega de les imatges PET, la selecció de mostres, l'associació amb les etiquetes clíniques i les transformacions necessàries per obtenir un conjunt de dades homogeni.

### EDA.ipynb

Inclou l'anàlisi exploratòria de les dades. Es revisa la distribució de les classes, les característiques generals del conjunt de dades i possibles representacions visuals per entendre millor la separació entre grups.

### MachineLearning.ipynb

Conté models clàssics de classificació aplicats a les dades preprocessades. S'hi proven tècniques de reducció de dimensionalitat i classificadors tradicionals per comparar el seu rendiment amb models més complexos.

### CNN.ipynb

Inclou el desenvolupament i entrenament de models basats en xarxes neuronals convolucionals per a la classificació automàtica de les imatges PET.

## Requisits

Les principals llibreries utilitzades són:

```text
numpy
pandas
matplotlib
scikit-learn
nibabel
tensorflow
keras
```

Es poden instal·lar amb:

```bash
pip install numpy pandas matplotlib scikit-learn nibabel tensorflow keras
```

## Ús

Es recomana executar els notebooks en aquest ordre:

1. `Preprocessing.ipynb`
2. `EDA.ipynb`
3. `MachineLearning.ipynb`
4. `CNN.ipynb`

## Dades

Les dades utilitzades provenen de la base de dades OASIS-3.

Per motius de mida i permisos d'accés, les imatges originals no s'inclouen en aquest repositori.
