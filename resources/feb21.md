## if you haven't already
### first, download [anaconda](https://www.anaconda.com/distribution/)

### next, download [cltk](https://github.com/cltk/tutorials/blob/master/1%20CLTK%20Setup.ipynb) by following these steps

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

## import corpora

1. get a jupyter notebook [running with cltk](/resources/runcltk)
2. import 
