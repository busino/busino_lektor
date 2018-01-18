# Website for busino


## Installation of dependencies

```
conda env create -f environment.yml
```

## Develop

```
activate www_lektor_env
lektor server
```

[http://127.0.0.1:5000/](http://127.0.0.1:5000/)


## Build

```
activate www_lektor_env
lektor quickstart
lektor server
lektor build -O ../busino.github.io
```




