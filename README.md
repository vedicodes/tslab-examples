[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vedicodes/tslab-examples/master?filepath=notebooks%2Fgetting_started.ipynb)

# tslab-examples

Example notebooks of tslab (https://github.com/yunabe/tslab)

## nbviewer links

[notebooks in nbviewer](https://nbviewer.jupyter.org/github/yunabe/tslab-examples/tree/master/notebooks/)

## Development

### Clean `"execute_count"`

To clear `"execute_count"` in notebooks, run `npm run clearcount`.

## Make the prebuilt image

```shell
docker build -t yunabe/tslab:20191114 -f Dockerfile_prebuilt .
docker push yunabe/tslab:20191114
```

## Build src to lib

```
yarn build
```
