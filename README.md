# IT4242E_MovieRSystem

A Movie Recommendation System.

Machine Learning and Data Mining Project **IT4242E**

Class **131082**.

## Notes

In this project, there is a **strictly** order to run the project. Please **run** in the **guided order** so as not to see any error.

## Libraries and Packages use

We use **Anacoda** Environment to install packages, libraries when use on Anacoda.

Working in Google Colaboratory is recommended.

The libraries, packages are :

- `kaggle` important!
- `pandas`
- `numpy`
- `ast` for `literal_eval`
- `sklearn`
- `torchmetrics`
- `torch` known as `pytorch`
- `matplotlib.pyplot`

If you also have Anacoda Environment, use following commands to install libraries missing:

```
pip install <library_name>
# For example: pip install kaggle
# pip install torch
```

## How to run on VSCode Window

We use **Anacoda** Environment to install packages, libraries.

The files we will work on and also the order to execute is:

- `downloader.ipynb`
- `cleaning_data.ipynb`
- `FeatureExtractor.py`
- `Profiles.ipynb`
- `LinearRegressionModel.ipynb`
- `Recommender.ipynb`
- `ClassificationModel.ipynb`
- `Recommender_classification.ipynb`

### 1. Download Dataset

Open `downloader.ipynb` and run choose run all.

If the kaggle key doesn't work any more please download [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) directly from Kaggle and extract to \Dataset folder.

Downloaded files will be in folder `Dataset`

### 2. Cleaning Dataset

Open `Cleaning Data\cleaning_data.ipynb` and run choose run all.

Cleaned files will be in folder `Dataset\CleanedData`

### 3. Create Profiles for Movies

Open `Profiles\Profiles.ipynb` and run choose run all.

Featured Extracted files will be in folder `Dataset\FeatureExtracted`

### 4. Learning Users' Models

- For A Straight-Forward Regression Model
  Open `Machine Learning\LinearRegressionModel.ipynb` and run choose run all.
- For A Classification Models
  Open `Machine Learning\ClassificationModel.ipynb` and run choose run all.

Models related files will be in folder `Dataset\ModelStorage`

### 5. Recommend User with Movies

- For A Straight-Forward Regression Model
  Open `Machine Learning\Recommender.ipynb` and run choose run all.
- For A Classification Models
  Open `Machine Learning\Recommender_classification.ipynb` on colab and run choose run all.

In those ipynb file, there are a variable `user` to specify id of user to recommend for.

`LinearRegressionModel.ipynb` and `Recommender.ipynb` should be run by pair and so for `ClassificationModel.ipynb` and `Recommender_classification.ipynb`

## How to run on Google Colab

The files we will work on and also the order to execute is:

- `downloader_colab.ipynb`
- `Clean_data_colab.ipynb`
- `Profiles_colab.ipynb` and `FeatureExtracted.py`
- `LinearRegressionModel_colab.ipynb`
- `Recommender_colab.ipynb`
- `ClassificationModel_colab.ipynb`
- `Recommender_classification_colab.ipynb`

### 1. Download Dataset

Open `downloader_colab.ipynb` on colab and run choose run all.

Downloaded files will be in path `/content/drive/MyDrive/MovieRecommendationSystem` in your drive

If the kaggle key doesn't work any more please download [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) directly from Kaggle and extract to /content/drive/MyDrive/MovieRSystem folder.

### 2. Cleaning Dataset

Open `Cleaning Data\cleaning_data_colab.ipynb` on colab and run choose run all.

Cleaned files will be in folder `/content/drive/MyDrive/MovieRecommendaSystem/dataset/CleanedData`

### 3. Create Profiles for Movies

Open `Profiles\Profiles_colab.ipynb` on colab and upload `Profiles\FeatureExtractor.py` file to current directory of colab.

Featured Extracted files will be in folder `/content/drive/MyDrive/MovieRecommendationSystem/dataset/FeatureExtracted`

### 4. Learning Users' Models

- For A Straight-Forward Regression Model
  Open `Machine Learning\LinearRegressionModel.ipynb` on colab and run choose run all.
- For A Classification Models
  Open `Machine Learning\LinearRegressionModel_colab.ipynb` on colab and run choose run all.

Models related files will be in folder `/content/drive/MyDrive/MovieRecommendationSystem/dataset/ModelStorage`

### 5. Recommend User with Movies

- For A Straight-Forward Regression Model
  Open `Machine Learning\Recommender_colab.ipynb` on colab and run choose run all.
- For A Classification Models
  Open `Machine Learning\Recommender_classification_colab.ipynb` on colab and run choose run all.

In that ipynb file, there are a variable `user` to specify id of user to recommend for.

`LinearRegressionModel_colab.ipynb` and `Recommender_colab.ipynb` should be run by pair and so for `ClassificationModel_colab.ipynb` and `Recommender_classification_colab.ipynb`
