# CV webinars

### Webinar materials

- [Image Classification: pollen grains](https://github.com/alex000kim/cv_webinars/blob/main/1_ImageClassification.ipynb)
  - Learn how to work with pretrained deep learning models using the pytorch framework
  - Learn how to train a powerful image classification model using a combination of image embeddings and logistic regression
  - Learn how to save and load a trained model for further integration into software applications
- [Image Similarity Search: Van Gogh paintings](https://github.com/alex000kim/cv_webinars/blob/main/2_ImageSimilaritySearch.ipynb)
  - Learn how to generate image embeddings using pretrained deep learning models
  - Learn how to perform image similarity search in latent embedding space

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
