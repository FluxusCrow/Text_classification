# Text classification

## General info
Machine learning model to predict wether a word or sentence is more likely used by the artists Gorillaz or Eagles of Death Metal. The lyrics are downloaded from the website https://www.lyrics.com/.

## Technologies
* Python 3.9.7
* libraries and its versions are listed in requirements.txt and can be installed with:
```
$ conda install --name <environment_name> --file requirements.txt
```

## Setup
Run the file "Project.ipynb" in jupyter notebook. Execute all cells one time to create the model. The last cell will ask for an input. Insert a word or a sentence, the model will predict which of the two artists is more likely to use it. The last cell can be executed as often as the user likes, without executing the rest of the code.
