Ignacio Loyola Hernández

El proyecto consiste en desarrollar un Dashboard, que integre un conjunto de visualizaciones significativo en el dominio o ámbito del dataset "https://www.kaggle.com/datasets/anandshaw2001/airlines-reviews-and-rating/data".
EDA.ipynb contiene la exploración de los datos.
main.ipynb contiene el desarrollo y despliegue de la app.

Requerimientos
# Manejo de la Data
import pandas as pd
import numpy as np
from sklearn.preprocessing import LabelEncoder

# Graficos
import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px
import re
import string
from wordcloud import WordCloud

# Dashboard
import dash
from dash import dcc, html
import plotly.graph_objs as go
from dash.dependencies import Input, Output
