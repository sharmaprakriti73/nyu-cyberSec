# nyu-cyberSec
Projects created and submitted as part of course - Machine Learning in Cyber Security (EL-GY-9163)

## I. The repository contains the following files:

1. The .ipynb file containing all the code that I have written as part of my solution to lab2.
2. The direcotry 'models/' contains the files for the badnet model.
3. Empty data directories : 'data/bd' and 'data/cl' since the datasets were too large to upload on github. They need to be manually uploaded to google colab from [here](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq) into respective directories while running the code.

## II. Following steps are needed to run my code:

1. Please open my .ipynb file on google colab.

2. Datasets required to run my code could not be uploaded to the data/ directory in this repository due to its large size. But the path to the dataset as specified in my code is:

#### For clean validation data:
data/cl/valid.h5

#### Clean test data:
data/cl/test.h5

#### Poisoned test data:
data/bd/bd_test.h5

These datasets need to be uploaded under these directories on google colab for the code to run.

3. The models/ directory in this repository contains the model and the weights associated with the badnet model which whill be required to run the code. These need to be uploaded on colab as well under the following directory:

models/bd_net.h5
models/bd_weights.h5
