## overview

I had created this in some markdown notes, but wanted to experiment with jupyter notebooks, and also create the possibility (if this is hosted on a jupyter-hub-like server) of folk playing with the code interactively.

---

## installallation

(adjust as desired)

- initial setup...

    ```
    % mkdir ./unicode_normalization_notebook_stuff

    % cd ./unicode_normalization_notebook_stuff/
    ```

- get code...

    ```
    % git clone https://github.com/birkin/unicode_normalization_notebook.git

    % cd ./unicode_normalization_notebook/
    ```

- set up venv...

    ```
    % python3 -m venv ../env

    % source ../env/bin/activate
    ```

- populate venv...

    ```
    % pip install -r ./requirements.txt
    ```

- run the notebook

    ```
    % jupyter notebook
    ```

---
