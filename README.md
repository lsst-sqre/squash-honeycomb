# squash-honeycomb
Getting SQuaSH metrics into Honeycomb

1. Clone this repo

```
git clone https://github.com/lsst-sqre/squash-honeycomb.git
```

2. Create a virtualenv

```
cd squash-honeycomb

virtualenv squash-honeycomb -p python3
source squash-honeycomb/bin/activate
pip install -r requirements.txt
```

3. Using the virtualenv in the Jupyter notebook

```
python -m ipykernel install --user --name=squash-honeycomb
jupyter notebook
```

(You should now see your kernel in the Jupyter notebook menu: `Kernel -> Change kernel` and be able so switch to it.)

Open the `squash-honeycomb.ipynb` notebook.
