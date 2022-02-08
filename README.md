# install

### initial setup...

```
% mkdir ./unicode_normalization_notebook_stuff

% cd ./unicode_normalization_notebook_stuff/
```

### get code...

```
% git clone https://github.com/birkin/unicode_normalization_notebook.git

% cd ./unicode_normalization_notebook/
```

### set up venv...

```
% python3 -m venv ../env

% source ../env/bin/activate
```

### populate venv...

```
% pip install pip_tools

% pip-compile ./requirements.in --upgrade-package jupyter

% pip install -r ./requirements.txt
```

### run the notebook

```
% jupyter notebook
```

---
