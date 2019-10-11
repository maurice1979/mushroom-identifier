# Mushroom Identifier

Training and evaluating state-of-the-art deep architectures for plant mushroom  classification task using pyTorch.

![Mushroom indentifier](app/static/img1.png)

Models are trained on the preprocessed dataset which can be downloaded [here](https://drive.google.com/drive/folders/1exBl5jKAoofDkoWhok2uJUJ8av0FKQEF?usp=sharing).

Dataset consists of **24** of most common mushroom classes in Catalonia (Spain). This dataset has been build by means of Google images and Instagram scraping, and manually verified in order to be as good as possible. **80%** of the dataset is used for training and **20%** for validation.

## Configuration
| Model      | Library   | Training Platform | Accuracy    |
| ---------- |:---------:|:-----------------:|:-----------:|
| Resnet50   | Fastai    |    Google Colab   |   60.086%   |

## Dataset Description:

|Name                       | No of Images  | Tags
| ------------------------- |:-------------:|:-----------------:|
| Amanita_caesarea          |     04        | '-'|
| Amanita_muscaria          |     01        | '-'|
| Amanita_pahlloides        |     02        | '-'|
| Boletus_calopus           |     04        | '-'|
| Boletus_edulis            |     04        | '-'|
| Calocybe_gambosa          |     01        | '-'|
| Cantharellus_cibarius     |     02        | '-'|
| Cantharellus_lutescens    |     02        | '-'|
| Craterellus_cornucopioides|     03        | '-'|
| Hebeloma_laterinum        |     01        | '-'|
| Hygrophorus_eburneus      |     01        | '-'|
| Hygrophorus_latitabundus  |     01        | '-'|
| Hygrophorus_russula       |     02        | '-'|
| Lactarius_deliciosus      |     10        | '-'|
| Lactarius_sanguifluus     |      'k'   | 't' |
| Laetiporus_sulphureus     |      'k'   | 't' |
| Lycoperdon_perlatum       |      'k'   | 't' |
| Macrolepiota_procera      |      'k'   | 't' |
| Marasmius_oreades         |      'k'   | 't' |
| Melanoleuca_excissa       |      'k'   | 't' |
| Morchella_deliciosa       |      'k'   | 't' |
| Rubroboletus_satanas      |      'k'   | 't' |
| Suillus_variegatus        |      'k'   | 't' |
| Tricholoma_terreum        |      'k'   | 't' |




Packages:

- fastai
- instagram-scraper (To create the dataset)

# **DISCLAIMER**

Identifying mushrooms from just a picture and a brief description can be very difficult.

This project is not intended to provide a 100% effective mushrooom identification. Thus, if you plan to collect mushrooms to be eaten, misidentified mushrooms can make you sick or kill you. Do not eat mushrooms you are not 100% certain of. Use many resources, and be skeptical of your own conclusions. This project takes no responsibility for damage caused by wrong identifications. If you continue, you agree to view this website under these terms.

