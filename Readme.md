![images DATA Analyst](https://user-images.githubusercontent.com/129564426/233806053-d57039f1-41ca-435b-a1d7-c4b90d97390c.jpg)


# Data Analysis of H1B Visas in USA on 2022 in Python

In this project, we perform an Exploratory Data Analysis of the Different H1B Visas granted in USA during 2022, on the way to know which are the best places to work, what are the carreers most needed, and which are the employers paying better wages.


## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform


## FAQ

#### Which are the Top 3 Sponsorship Employers for  H1B Visas in USA

Amazon.com Services LLC	/ Cognizant Technology Solutions Us Corp/ Google LLC

#### What are the Top 3 Cities where H1B Visas were Granted in 2022

New York, New York	/ Seattle, Washington / San Francisco, California


## Authors

- [@LTorrado777](https://www.github.com/LTorrado777)


## Usage/Examples

```python
%matplotlib inline
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

df = pd.read_csv("LCA_FY_2022.csv")
