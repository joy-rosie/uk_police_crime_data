# UK Police Crime Data

This is a python repository to download UK police crime data and to visualise it using `pandas`, `geopandas`, `matplotlib` and `plotly`

## Instructions
1) Clone this repository using `git clone`
1) `cd` into this repository locally
1) - Create a conda environment using `conda env create -f environment.yml` 
   - Or use `pip install -r requirements.txt`
1) Use `data_gather.ipynb` to download the UK crime data using https://data.police.uk/data/archive/
1) Create a mapbox account on https://account.mapbox.com/auth/signup/ and get a token from https://account.mapbox.com/
1) - Create a JSON file `authentication.json` and put it in this folder using the following format: 
    ```json
    {
      "mapbox_access_token": "<insert token>"
    }
    ```

    - Otherwise you can directly input the token in the notebook
1) Use `data_visualisation.ipynb`