# Wine-Quality
A project investigating the relationship between wine quality and the 
chemical properties of the wine. It uses the 
[Wine](http://archive.ics.uci.edu/ml/datasets/Wine) dataset from the
[UCI Machine Learning Repository](http://archive.ics.uci.edu/ml).

## Playing With Outliers

I have added a fun interactive application using the Python 
visualization library called Bokeh. The app allows you to pick features 
from the wine data set and define an outlier threshold to explore how 
this affects the data. The application source code is in the 
`playing_with_outliers` directory and is called `main.py`. To run this 
application, you will need to install bokeh:

```
pip install bokeh
```

Then, to run the application, download the `playing_with_outliers` 
directory and its contents. Then, in the directory where you downloaded 
it, run:

```
bokeh serve --show playing_with_outliers
```

The application will open in your browser.
