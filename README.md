# Anaconda / Jupyter Customization
Some work in progress customization for my jupyter notebooks

## Functionality:
Install [jupyter notebook extensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) using ```pip install jupyter_contrib_nbextensions```. 


You [might need to](https://github.com/ipython-contrib/jupyter_contrib_nbextensions/issues/1090) ```jupyter contrib nbextensions install --sys-prefix --skip-running-check``` afterwards.

After successful installation, a new menu should appear in jupyter http://localhost:8888/tree <br>
Currently in use: 
* Autopep8
* Collapsible Headings
* Hide input all
* Printview
* Table of Contents (2)
* table_beautifier

## Optics:
Use following command first:
```jupyter notebook --generate-config```

Contents of folder css to be placed under:
```C:\Users\USER\.jupyter\custom```
