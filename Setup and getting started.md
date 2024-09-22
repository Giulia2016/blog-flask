# Create the new repo and virtualenv
## Create virtualenv
```sh
mkdir blog-flask
cd blog-flask
python3.12 -m venv virtualenv
source ./virtualenv/bin/activate
```

## Install Flask
```sh
pip install Flask
```
## Initialise Git repo
```shell
git init .
echo "# blog-flask" >> README.md
git remote add origin git@github.com:Giulia2016/blog-flask.git
