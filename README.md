# Sistemas de recomeção com PySpark e MLlib usado o Databricks
#### Curso Alura

Dados usados foram o Spotify_dataset do Kaggle

- Exploração, tratamento e analise dos dados
- Utilização do Pandas API
- Criação de arquivos .PARQUET
- VectorAssembler
- StandardScaler
- PCA
- Pipeline
- Clustering KMeans
- vector_to_array
- Spark SQL
- Distância Euclidiana
- Spotipy

  - import pyspark.pandas as ps
  - from pyspark.ml.feature import VectorAssembler
  - from pyspark.ml.feature import StandardScaler
  - from pyspark.ml.feature import PCA
  - import numpy as np
  - from pyspark.ml import Pipeline
  - from pyspark.ml.clustering import KMeans
  - from pyspark.ml.functions import vector_to_array
  - import plotly.express as px
  - from pyspark.ml.evaluation import ClusteringEvaluator
  - from pyspark.sql.functions import rand
  - import matplotlib.pyplot as plt
  - from pyspark.ml.linalg import Vectors
  - from scipy.spatial.distance import euclidean
  - from pyspark.sql.types import FloatType
  - import pyspark.sql.functions as f
  - import spotipy
  - from spotipy.oauth2 import SpotifyOAuth, SpotifyClientCredentials
  - from skimage import io