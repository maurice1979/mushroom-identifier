# Mushroom Identifier

Training and evaluating state-of-the-art deep architectures for plant mushroom  classification task using pyTorch.

![Mushroom indentifier](app/static/img1.png)

Models are trained on the preprocessed dataset which can be downloaded [here](https://drive.google.com/drive/folders/1exBl5jKAoofDkoWhok2uJUJ8av0FKQEF?usp=sharing).

Dataset consists of **43** of most common mushroom classes in Catalonia (Spain). This dataset has been build by means of Google images scrapping, and manually verified in order to be as good as possible. **80%** of the dataset is used for training and **20%** for validation. 

## Configuration
| Model      | Library   | Training Platform | Accuracy    |
| ---------- |:---------:|:-----------------:|:-----------:|
| Resnet34   | Fastai    |    Google Colab   |   90.3892%   |

## Dataset Description:

|    Name                    | No. of Images |
| -------------------------- |:-------------:|
| Helvella Crispa            |     311       |
| Lactarius Deliciosus       |     75        |
| Calocybe Gambosa           |     156       |
| Rubroboletus Satanas       |     131       |
| Hygrophorus Latitabundus   |     129       |
| Amanita Pahlloides         |     199       |
| Hygrophorus Marzuolus      |     147       |
| Macrolepiota Procera       |     217       |
| Helvella Lacunosa          |     304       |
| Amanita Pantherina         |     336       |
| Hydnum Rufescens           |     157       |
| Russula Aurea              |     174       |
| Entoloma Lividum           |     127       |
| Russula Delica             |     153       |
| Craterellus Cinereus       |     125       |
| Clathus Ruber              |     310       |
| Morchella Deliciosa        |     246       |
| Amanita Muscaria           |     59        |
| Clitocybe Costata          |     135       |
| Amanita Citrina            |     177       |
| Phallus Impudicus          |     220       |
| Craterellus Cornucopioides |     258       |
| Hydnum Albidum             |     107       |
| Gyromitra Esculenta        |     227       |
| Amanita Vaginata           |     222       |
| Amanita Caesarea           |     229       |
| Lactarius Vinosus          |     40        |
| Boletus Aereus             |     317       |
| Lactarius Sanguifluus      |     110       |
| Hygrophorus Personii       |     32        |
| Hygrophorus Russula        |     174       |
| Boletus Lupinus            |     117       |
| Boletus Regius             |     130       |
| Russula Cyanoxantha        |     180       |
| Boletus Edulis             |     187       |
| Omphalotus Olearius        |     145       |
| Cantharellus Lutescens     |     245       |
| Chroogomphus Rutilus       |     225       |
| Clavulina Cinerea          |     526       |
| Hygrophorus Eburneus       |     172       |
| Boletus Calopus            |     166       |
| Marasmius Oreades          |     132       |
| Cantharellus Cibarius      |     333       |


Packages:

- fastai
- pandas

# **DISCLAIMER**

Identifying mushrooms from just a picture and a brief description can be very difficult! This project is not intended to provide a 100% effective mushrooom identification. Thus, if you plan to collect mushrooms to be eaten, misidentified mushrooms can make you sick or kill you. Do not eat mushrooms you are not 100% certain of. Use many resources, and be skeptical of your own conclusions. This project takes no responsibility for damage caused by wrong identifications. If you continue, you agree to view this website under these terms.

