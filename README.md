# Mushroom Identifier

Training and evaluating state-of-the-art deep architectures for plant mushroom  classification task using pyTorch.

Models are trained on the preprocessed dataset which can be downloaded [here](https://drive.google.com/open?id=xxx).

Dataset consists of **24** of most common mushroom classes in Catalonia (Spain). This dataset has been build by means of Google images and Instagram scraping, and manually verified in order to be as good as possible. **80%** of the dataset is used for training and **20%** for validation.

## Configuration
| Model      | Library   | Training Platform | Accuracy    |
| ---------- |:---------:|:-----------------:|:-----------:|
| Resnet50   | Fastai    |    Google Colab   |   60.086%   |

## Dataset Description:

|Name                       | No of Images  | Class Names
| ------------------------- |:-------------:|:-----------------:|
| Amanita_caesarea          |     04        | 'Apple___Cedar_apple_rust' 'Apple___healthy' |
| Amanita_muscaria          |     01        | 'Blueberry___healthy' |
| Amanita_pahlloides        |     02        | 'Cherry_(including_sour)_Powdery_mildew', 'Cherry_(including_sour)_healthy' |
| Boletus_calopus           |     04        | 'Corn___Cercospora_leaf_spot', 'Corn___Common_rust', |
| Boletus_edulis            |     04        | 'Black_rot','Leaf_blight_(Isariopsis_Leaf_Spot)','Grape___healthy' |
| Calocybe_gambosa          |     01        | 'Orange___Haunglongbing_(Citrus_greening)' |
| Cantharellus_cibarius     |     02        | 'Peach___Bacterial_spot','Peach___healthy' |
| Cantharellus_lutescens    |     02        | 'Pepper,_bell___Bacterial_spot','Pepper,_bell___healthy' |
| Craterellus_cornucopioides|     03        | 'Potato___Early_blight','Potato___Late_blight','Potato___healthy' |
| Hebeloma_laterinum        |     01        | 'Raspberry___healthy' |
| Hygrophorus_eburneus      |     01        | 'Soybean___healthy' |
| Hygrophorus_latitabundus  |     01        | 'Squash___Powdery_mildew' |
| Hygrophorus_russula       |     02        | 'Strawberry___Leaf_scorch','Strawberry___healthy' |
| Lactarius_deliciosus      |     10        | Tomato: 'Septoria_leaf_spot', 'Spider_mites','Target_Spot' |
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

