# clothes-classifier-cnn

This repository uses a convolutional neural network to classify different clothing items. The CNN model is inside of cnn.ipynb, models.ipynb contains a standard nn, non-linear and linear layers model, and a cnn with different benchmarks

## To start
### Create virtual environment

- Windows: `virtualenv env`
- Linux/MacOS: `python3.12 -m venv env`

### Activate virtual environment

- Windows: `.\env\Scripts\activate`
- Linux/MacOS: `source env/bin/activate`

### Download dependencies
- `pip3 install -r requirements.txt`

### If in vscode
- select "select kernel" on top right corner, select path to env/bin/python -> 3.12.7 or less
- Pytorch is not compatible with python > 3.13