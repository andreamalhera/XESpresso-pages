<p align="center"><img src="logo.svg" alt="XESpresso logo" width="120"></p>

# XESpresso

XESpresso is a metadata collector for event logs. It collects the characteristics of an event log without collecting the log itself: it runs in your browser, so your event data never leaves your computer, and you choose whether to send the computed features and metadata to the collection. The collection combines seven data collections: BPIC (BPI Challenge logs), Synthetic Benchmark, 4TU Real-Life Logs, Community Repositories (GitHub and Kaggle), IoPT (IoT lab logs), OCEL Publication (object-centric event logs) and SuXXES. Each event log is described by the Costa et al. metadata schema, its data collection and dataset source, and its FEEED features.

Open the app: [XESpresso](https://andreamalhera.github.io/XESpresso-pages/). This repository holds the built site that GitHub Pages serves.

## Features

- **Event Data Catalog**: search, filter and open the event datasets, grouped into tiles by any concept and arranged by publication year in a landscape.
- **Event Data Space**: a 2D map (PCA) of the event datasets by their FEEED features. Similar datasets lie close together.
- **Feature Correlations**: how the FEEED features correlate, and which repeat each other the least.
- **Add Event Data**: load your own XES, XES YAML or CSV files to compare them with the collection. Files are processed in your browser and never uploaded.
- Filters apply on every page and the plots are recomputed for them. Categories can be told apart by shape as well as color.

## Data

The dataset is under review. Until it is published, only a sample is listed by name, but all event datasets count in every chart and statistic. Logs made from one file (e.g. one per OCEL object type) count as one event data source.

## Proposing event data

Add your event data on the site, then choose **Open a GitHub issue**, or download your entries and email them to xespresso.maldonado@tum.de. The maintainers review every entry. Accepted entries are published under CC BY 4.0.

## License and contact

Code: [MIT](LICENSE). Data and site content: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please cite the event log sources listed on the About page along with XESpresso. Contact: Andrea Maldonado, xespresso.maldonado@tum.de
