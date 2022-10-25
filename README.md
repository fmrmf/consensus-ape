# consensus-ape

Example project setup to use `ape-beacon` for querying the Ethereum consensus layer.


## Setup

Install the specified plugins in `ape-config.yaml`

```bash
ape plugins install .
```


## Running

To play around with the Jupyter notebook and query your [Lighthouse](https://github.com/sigp/lighthouse) beacon node, run

```bash
lighthouse bn --http
```

then

```bash
ape notebook
```
