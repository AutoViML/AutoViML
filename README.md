[![Repos Badge](https://badges.pufler.dev/repos/AutoViML)](https://badges.pufler.dev)
[![Updated Badge](https://badges.pufler.dev/updated/AutoViML/featurewiz)](https://badges.pufler.dev)
Join our elite team of contributors!<br>
[![Contributors Display](https://badges.pufler.dev/contributors/AutoViML/AutoViz?size=40&padding=5&bots=true)](https://badges.pufler.dev)
[![Contributors Display](https://badges.pufler.dev/contributors/AutoViML/deep_autoviml?size=40&padding=5&bots=true)](https://badges.pufler.dev)
[![Contributors Display](https://badges.pufler.dev/contributors/AutoViML/Auto_TS?size=40&padding=5&bots=true)](https://badges.pufler.dev)
[![Contributors Display](https://badges.pufler.dev/contributors/AutoViML/featurewiz?size=40&padding=5&bots=true)](https://badges.pufler.dev)
![image3000](4000_stars.png)
<h1 align="center">👋 Welcome to the AutoViML Fan Club Page!<br> We just hit 4000 stars for our amazing AutoViML libraries on Github!!</h1>
<h3 align="center">AutoViML creates innovative Open Source libraries to make data scientists' and machine learning engineers' lives easier and more productive! </h3>
<h3 align="center">
  <img src="https://komarev.com/ghpvc/?username=AutoViML&label=Profile%20views&style=for-the-badge" alt="kanchitank"/>
</h3>

### Our innovative libraries so far:
- 🤝 [AutoViz](https://github.com/AutoViML/AutoViz) Automatically Visualizes any dataset, any size with a single line of code. Now with Bokeh and Holoviews it can make your charts and dashboards interactive!
- 🤝 [Auto_ViML](https://github.com/AutoViML/Auto_ViML) Automatically builds multiple ML models with a single line of code. Uses scikit-learn, XGBoost and CatBoost.
- 🤝 [Auto_TS](https://github.com/AutoViML/Auto_TS) Automatically builds ARIMA, SARIMAX, VAR, FB Prophet and XGBoost Models on Time Series data sets with a Single Line of Code. Now updated with [DASK](https://dask.org/) to handle millions of rows.
- 🤝 [Featurewiz](https://github.com/AutoViML/featurewiz) Uses advanced feature engineering strategies and select the best features from your data set fast with a single line of code. Now updated with DASK to handle millions of rows.
- 🤝 [Deep_AutoViML](https://github.com/AutoViML/deep_autoviml) Builds tensorflow keras models and pipelines for any data set, any size with text, image and tabular data, with a single line of code.
- 🤝 [lazytransform](https://github.com/AutoViML/lazytransform) Automatically transform all categorical, date-time, NLP variables to numeric in a single line of code, for any data, set any size. 
- 🤝 [pandas_dq](https://github.com/AutoViML/pandas_dq) Automatically find and fix data quality issues in your dataset with a single line of code, for pandas.

## BREAKING News! AUTO-VIML libraries have been upgraded to be compatible with Python 3.12 and pandas 2.0  ###
I have finally taken the plunge towards Python 3.12 and pandas 2.0. Yes, it was difficult, but I have now upgraded the following libraries to their latest versions:
- featurewiz
- autoviml
- autoviz
- lazytransform
- pandas-dq
  
My humble request to everyone who may have some errors after upgrading my libraries above is to make sure you have these below versions:

- numpy<2
- category_encoders <=3.6.3
- xgboost<=1.7.6
- scikit-learn<=1.5.2

These are my "recommended" versions of those libraries. So please check your machine to see if these libraries are in "correct" versions. <br>
Wish you all the best and thanks for the support always!<br>

### Feb-2024: Added "Auto Encoders" for automatic feature extraction to featurewiz library for #feature-extraction
On Feb 8, 2024, we released a major update to our popular "featurewiz" library that will transform your input into a latent space with a dimension of latent_dim. This lower dimension (similar to PCA) will enable you to extract the best patterns in your data for the toughest imbalanced class and multi-class problems. Try it and let us know! <a href="[https://ibb.co/X5dDqFv](https://github.com/AutoViML/featurewiz)"><img src="https://i.ibb.co/sJsKphR/VAE-model-flowchart.png" alt="autoencoders-screenshot" border="0"></a><br /><a target='_blank' href='https://github.com/AutoViML/featurewiz/blob/main/updates.md'>how to use autoencoders in featurewiz</a><br />

### April-2023: Released a major new python library "pandas_dq" #data_quality #dataengineering
On April 2, 2023, we released a major new Python library called "pandas_dq" that will automatically find and fix data quality issuesin your train and test dataframes in a single line of code, for any data, set any size. 
<a href="[https://ibb.co/X5dDqFv](https://github.com/AutoViML/pandas_dq)"><img src="https://i.ibb.co/vdrhSLK/fix-dq-screenshot.png" alt="fix-dq-screenshot" border="0"></a><br /><a target='_blank' href='https://whatsmyscreenresolution.com/'>how many pixels wide is my screen</a><br />

### April-2022: Released a major new python library "lazytransform" #featureengineering #featureselection
On April 3, 2022, we released a major new Python library called "lazytransform" that will automatically transform all categorical, date-time, NLP variables to numeric in a single line of code, for any data, set any size. 
<a href="https://github.com/AutoViML/lazytransform"><img src="https://i.ibb.co/xYm0jwW/lazy-code2.png" alt="lazy-code2" border="0"></a>                                                                                                                                           
### Jan-2022: Major upgrade to featurewiz: you can now perform feature selection thru fit and transform #MLOps #featureselection
As of version 0.0.90, featurewiz has a scikit-learn compatible feature selection transformer called FeatureWiz. You can use it to perform fit and predict as follows. You will get a Scikit-Learn Transformer object that you can add it to other data pipelines in MLops to select the top variables from your dataset. <br>
<a href="https://github.com/AutoViML/featurewiz"><img align="center" src="https://i.ibb.co/VTd0kcv/featurewiz-class2.jpg" alt="featurewiz-class2" border="0" /></a>

### Dec-23-2021 Update: AutoViz now does Wordclouds! #autoviz #wordcloud
AutoViz can now create Wordclouds automatically for your NLP variables in data. It detects NLP variables automatically and creates wordclouds for them.
<img align="center" src="https://i.postimg.cc/DyT466xP/wordclouds.png">

### Dec 21, 2021: AutoViz now runs on Docker containers as part of MLOps pipelines. Check out Orchest.io
We are excited to announce that AutoViz and Deep_AutoViML are now available as containerized applications on Docker. This means that you can build data pipelines using a fantastic tool like [orchest.io](orchest.io) to build MLOps pipelines visually. Here are two sample pipelines we have created:

<b>AutoViz pipeline</b>: https://lnkd.in/g5uC-z66
<b>Deep_AutoViML pipeline</b>: https://lnkd.in/gdnWTqCG

You can find more examples and a wonderful video on [orchest's web site](https://github.com/orchest/orchest-examples)
![banner](https://github.com/rsesha/autoviz_pipeline/blob/main/autoviz_orchest.png)

### Dec-17-2021 AutoViz now uses HoloViews to display dashboards with Bokeh and save them as Dynamic HTML for web serving #HTML #Bokeh #Holoviews
Now you can use AutoViz to create Interactive Bokeh charts and dashboards (see below) either in Jupyter Notebooks or in the browser. Use chart_format as follows:
- `chart_format='bokeh'`: interactive Bokeh dashboards are plotted in Jupyter Notebooks.
- `chart_format='server'`, dashboards will pop up for each kind of chart on your web browser.
- `chart_format='html'`, interactive Bokeh charts will be silently saved as Dynamic HTML files under `AutoViz_Plots` directory
<img align="center" src="https://i.postimg.cc/MTCZ6GzQ/Auto-Viz-HTML-dashboards.png" />

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.docker.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> </p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=AutoViML&show_icons=true&locale=en" alt="AutoViML" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=AutoViML&" alt="AutoViML" /></p>

<h2 align="left">Our Kaggle Badges:</h2>

![notebook](https://road-to-kaggle-grandmaster.vercel.app/api/badges/rsesha/notebook/light) ![discussion](https://road-to-kaggle-grandmaster.vercel.app/api/badges/rsesha/discussion/light)

<h3 align="left">Connect with us on Linkedin:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/ram-seshadri-nyc-nj/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="ram seshadri" height="30" width="40" /></a>
</p>

