Vegetable Classification: CNN vs Random Forest

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kielu91/vegetable-classification-cnn/blob/main/vegetable_classification_cnn.ipynb)
## ?? Szybki start
**Kliknij przycisk "Open in Colab" powy?ej** i uruchom wszystkie kom車rki!

## ?? Projekt
- **Autor**: ?ukasz Kielczyk 
- **Dataset**: [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)
- **Modele**: CNN + Random Forest
- **Wyniki**: CNN 98.87%, RF 98.77% accuracy

## ??? Architektura
- **CNN**: 4 warstwy konwolucyjne 
- **Features**: 64-wymiarowe cechy z CNN dla Random Forest
- **Dane**: 21,000 obraz車w, 15 klas warzyw
- **Augmentacja**: ColorJitter, RandomFlip, Rotation


## ?? Zawarto?? notebook'a
1. **Setup & Data Loading** - Kaggle dataset download
2. **Data Analysis** - Rozk?ad klas i wizualizacja
3. **CNN Architecture** - Model definition i trenowanie
4. **Feature Extraction** - CNN jako feature extractor
5. **Random Forest** - Klasyfikacja na CNN features
6. **Results & Comparison** - Szczeg車?owa analiza wynik車w

## ?? Wymagania
Notebook automatycznie instaluje potrzebne biblioteki: