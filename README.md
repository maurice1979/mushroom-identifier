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

|Name                       | No of Images | Tags
| ------------------------- |:------------:|:-----:|
| Amanita_caesarea          |     355      | '-'   |
| Amanita_muscaria          |      67      | '-'   |
| Amanita_pahlloides        |     333      | '-'   |
| Boletus_calopus           |     374      | '-'   |
| Boletus_edulis            |     380      | '-'   |
| Calocybe_gambosa          |     408      | '-'   |
| Cantharellus_cibarius     |     551      | '-'   |
| Cantharellus_lutescens    |     396      | '-'   |
| Craterellus_cornucopioides|     402      | '-'   |
| Hebeloma_laterinum        |     344      | '-'   |
| Hygrophorus_eburneus      |     426      | '-'   |
| Hygrophorus_latitabundus  |     308      | '-'   |
| Hygrophorus_russula       |     345      | '-'   |
| Lactarius_deliciosus      |     185      | '-'   |
| Lactarius_sanguifluus     |     366      | 't'   |
| Laetiporus_sulphureus     |     424      | 't'   |
| Lycoperdon_perlatum       |      99      | 't'   |
| Macrolepiota_procera      |     371      | 't'   |
| Marasmius_oreades         |     338      | 't'   |
| Melanoleuca_excissa       |     107      | 't'   |
| Morchella_deliciosa       |     367      | 't'   |
| Rubroboletus_satanas      |     391      | 't'   |
| Suillus_variegatus        |     363      | 't'   |
| Tricholoma_terreum        |     355      | 't'   |




Packages:

- fastai
- instagram-scraper (To create the dataset)

# **DISCLAIMER**

Identifying mushrooms from just a picture and a brief description can be very difficult.

This project is not intended to provide a 100% effective mushrooom identification. Thus, if you plan to collect mushrooms to be eaten, misidentified mushrooms can make you sick or kill you. Do not eat mushrooms you are not 100% certain of. Use many resources, and be skeptical of your own conclusions. This project takes no responsibility for damage caused by wrong identifications. If you continue, you agree to view this website under these terms.

