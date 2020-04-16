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
6. open a jupyter notebook

```
$ jupyter notebook
```
7. ...and voila!

NB whenever you want to use the cltk again, you must recreate the virtual environment in the cltk folder before opening the jupyter notebook. For convenience, I've put the code for opening cltk [here](/resources/runcltk)

