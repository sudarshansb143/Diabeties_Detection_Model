# Diabetes detection model

The model is designed to detect the occurrence of the diabetes with percent of the confidence

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install 
sklearn
pickel

pip install sklearn
pip install pickel
```

## Usage

```python
import sklearn
import pickel
loaded_model = pickel.load("diabetes.sav")
y_pred = loaded_model.predict(variable)```
print(y_pred)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

