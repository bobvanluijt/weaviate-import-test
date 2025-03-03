# weaviate-import-test

A simple test script to test importing with OOTB Weaviate settings.

1. Download a dataset from [here](https://weaviate.io/blog/sphere-dataset-in-weaviate#importing-sphere-with-python) (you don't have to untar).
2. Change the settings [here](load.py#L9-L14) if needed.
3. Install dependencies: `$ pip3 install weaviate-client wasabi`
4. Run the script: `$ python3 -u load.py`
