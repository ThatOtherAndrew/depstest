This is just a quick test demo of an approach I'm considering to handle parallel installations of multiple versions of the same dependency.

To install the dependencies for this project, use the following two commands:

```sh
python -m pip install --target=lib/a cowsay==4.0
python -m pip install --target=lib/b cowsay==6.1
```

The entrypoint is `main.py`:

```sh
python main.py
```
