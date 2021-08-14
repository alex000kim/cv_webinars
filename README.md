# CV webinars

### Webinar materials

- 

### Prerequisites

- [pipenv](https://pipenv.pypa.io/en/latest/)

- [jupyter](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

### Setup

```bash
# Create virtual environment
pipenv shell
# Install dependencies
pipenv install
# Register this environment's python kernel in jupyter
python -m ipykernel install --user --name cv-webinars --display-name "Python (cv-webinars)"
```

After launching jupyter server, verify that the right kernel is used.
