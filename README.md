# Python and JavaScript, side by side

Comparison of Python and JavaScript features, to be presented live to a group of Pythonistas.

Order of featues inspired by [naucse.python.cz](https://naucse.python.cz/course/pyladies/), modified to my personal taste. Scroll down for more complex topics and some features from Python 3.8.1 and ES2020.

The Notebook is published at [peter.hozak.info/python-javascript](https://peter.hozak.info/python-javascript/).

## Contribution

Please create a github issue. Don't expect active development after the end of year 12020 HE.

## Development

1. Edit [python-javascript.ipynb](./python-javascript.ipynb) in a modern desktop browser (e.g. Firefox 78.0.2):

```sh
cd python-javascript
conda create -n python38 python=3.8 anaconda=2020.02
conda activate python38
nvm use
jupyter notebook
```

2. Re-run all cells, including the one to change CSS formatting.
3. Save as [docs/index.html](./docs/index.html).
4. git add, commit, push
