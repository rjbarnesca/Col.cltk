# Downloads of Anaconda and cltk

## first, download [anaconda](https://www.anaconda.com/distribution/)
- this will provide you provide you with the langauge ([Python](https://www.python.org)) and the platform ([Jupyter Notebooks](https://jupyter.org)) for using the cltk

### next, download cltk by following these steps

1. download [git](https://git-scm.com/downloads) for use with corpus management 
2. open terminal
3. make a cltk directory:
```
$ cd ~/
$ mkdir cltk
```
3. navigate to cltk directory: 

```
$ cd cltk
```
4. create a virtual environment: 
```
$ pyvenv venv
$ source venv/bin/activate
```
5. from here, install cltk

```
$ pip install cltk
```

6. at this point it will be useful to pip install several other tools which cltk will depend on down the road 

```
$ pip install beautifulsoup4
$ pip install python-Levenshtein
$ pip install -U matplotlib
```

7. open a jupyter notebook

```
$ jupyter notebook
```
8. ...and voila!

**NB** *whenever you want to use the CLTK again, you should open it from your terminal after recreating the virtual environment within the same CLTK folder. I have put the code for opening CLTK [here](/resources/runcltk)*

