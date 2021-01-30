# Obesity Explorer

Authors: Dustin Burnham, Javairia Raza, Rafael Pilliard Hellwig, Tanmay Sharma

## Using the Obesity Dashboard

Obesity has been an increasing medical concern across the world in the 21st century. 
It is a medical precursor to diseases such as diabetes, heart diseases, high blood pressure and certain types of cancers. 
In spite of this, most people know very little about this disease, and are unaware of the factors that increase its relative risk. 
To increase awareness and deepen understanding, this [Obesity Dashboard](https://r-obesity-explorer.herokuapp.com/) allows users to explore obesity trends, probe associations with other variables and factors, and discover patterns related to this global epidemic.

[![App](doc/img/dashboard.gif)](https://obesity-explorer.herokuapp.com/)

## Contributing to the Dashboard

We love contributions! If you wish to help with this project or find a bug, please first review our [contributing guidelines](CONTRIBUTING.md).
Contributors are encouraged to clone the repository, and run the following at the terminal to have the app execute locally:

```bash
Rscript app.R
```

The path to the URL will be printed to screen, which can be copy-pasted into a browser. To exit the app, hit <kbd>Ctrl</kbd> + <kbd>C</kbd>.

This app is written in R using the Dash framework, but the authors maintain a [parallel implementation](https://github.com/UBC-MDS/obesity-explorer) for Python. 
Details of the author's vision can be found in the [proposal document](https://github.com/UBC-MDS/obesity-explorer-r/blob/main/doc/proposal.md).
