### Jupyter Notebook running Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn

#### How to use

```
mkdir notebooks

docker run -it --rm -p 8888:8888 -d -v notebooks:/notebooks durgeshm/jupyter-sklearn

OR 

docker run -it --rm -P -d -v notebooks:/notebooks durgeshm/jupyter-pydata
```

Then, navigate to http://localhost:8888 on your host browser. (or, better - ssh tunnel to host server on port 8888 and navigate from your local machine).

