# PyRVAwebsiteV2
Using Pelican to update existing PyRVA website

# Getting Started
```shell
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

# Using Pelican

Reset output starting from a clean slate
```shell
make clean
```

generate the html
```shell
make html
```

deploy a test server
```shell
make serve
```
>[!note] I hard mapped the port to 5001 in the pelicanconf.py as it conflicts with another service I run on the default port. You should be able to run -port **port number** with the make command but I am lazy. Iono willing to discuss with team if there is any heartburn here. 





