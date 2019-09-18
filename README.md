
# Amazon camera review predictor

I wanted to investigate the nature of online reviews due to their importance in purchase decisions. I am also a keen photographer/filmmaker for domain knowledge in this particular product.

The goal was to predict the star rating for a product based on the review text. I was able to use natural language processing techniques, and sentiment analysis to feed into my classification models which were gaining expected F1 scores (0.71)

Due to the imbalance in the dataset I went further to web scrape a further 4000 reviews of my own. After observing my initial results and the confusion matrix I realised I needed a more suitable metric than accuracy to evaluate the best model choice. As a final comparison I conducted a binary classification problem (predicting high or low ratings) which increased my models scores (0.91). I will further investigate procedures to over and under sample for unbalanced datasets for applications this is common in the real world.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install (name packages)

```bash
pip install foobar
```

## Usage

```python
import 
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
