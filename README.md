# Set of scripts to explore NEMAR EMG Datasets shared by META

You'll need to install:

- a recent version of mne (possible nightly)
- this branch from mne_bids (https://github.com/mne-tools/mne-bids/pull/1129)

To get the data:

```shell
datalad clone https://github.com/nemarDatasets/nm000104.git
cd nm000104
datalad get sub-01438774
```

and to get all datasets:

```shell
datalad clone https://github.com/nemarDatasets/nm000104.git
datalad clone https://github.com/nemarDatasets/nm000105.git
datalad clone https://github.com/nemarDatasets/nm000106.git
datalad clone https://github.com/nemarDatasets/nm000107.git
```
