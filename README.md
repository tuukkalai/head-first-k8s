# Head first Kubernetes

## Init venv (if `~/.venv/k8s` is not found)

```sh
python3 -m venv ~/.venv/k8s
```

## Activate venv

```sh
source ~/.venv/k8s/bin/activate
```

## Install packages

```sh
pip install -r requirements.txt
```

## Run the application

```sh
FLASK_APP=hello.py flask run
```

## Exiting

Close the running app with `Ctrl-C`. Deactivate python venv with 

```sh
deactivate
```

