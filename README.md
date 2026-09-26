# Transport Network Criticality

Graph-based experiments analysing transport-network disruption and alternative connections in Istanbul, Boston, and Islamabad–Rawalpindi.

## Contents

| File | Original filename |
|---|---|
| [notebooks/01_istanbul_metrobus_criticality.ipynb](notebooks/01_istanbul_metrobus_criticality.ipynb) | Istanbul Metro Stations VErsion 3.ipynb |
| [notebooks/02_boston_silver_line_criticality.ipynb](notebooks/02_boston_silver_line_criticality.ipynb) | Metro of Buston.ipynb |
| [notebooks/03_islamabad_rawalpindi_network.ipynb](notebooks/03_islamabad_rawalpindi_network.ipynb) | ISLM-Pindi Metro.ipynb |

## Run

For Python notebooks, install the inferred dependencies:

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open a notebook and run cells from the beginning. Alternatively upload the notebook to Google Colab. Replace local or Google Drive paths with your own data locations before running. Notebooks are independent unless explicitly stated otherwise. For C++ files, compile and run each example separately with a compatible C++ compiler.

## Status and limitations

Supply the GTFS feeds and station/interchange CSVs referenced in each notebook. Istanbul and Boston use different edge-weight assumptions; do not directly compare numerical scores without reconciling units and methodology. This is a candidate version selection, not an executed comparison of all variants.

This collection was organised from existing files. Code-cell contents were preserved; saved outputs, execution counts, and transient notebook metadata were removed. The notebooks have not been executed as part of this preparation. Dependencies are inferred and unpinned, not a tested environment lockfile.

## Results

Run the examples to regenerate results. No accuracy, performance, or correctness claims are made here.

## Provenance

See [SOURCE_MAP.csv](SOURCE_MAP.csv) for the source archive and original filename. Preserve existing acknowledgements. No blanket open-source licence has been added because rights for adapted course material and datasets have not been established.
