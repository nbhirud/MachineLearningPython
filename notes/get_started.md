
# Instructions for getting started

## To install jupyter: 
(Refer https://jupyter.org/install)

```
pip install jupyterlab
```

## To run jupyter

```
jupyter lab
```
But it did not work on my Windows 10 laptop. Adding `C:\Users\<USERNAME>\AppData\Roaming\Python\Python312\Scripts` to PATH fixes this.

Use the following if you do not wish to modify PATH:

(Refer https://stackoverflow.com/a/41034867/7524805)
```
py -m jupyterlab
```
