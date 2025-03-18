# Datasets

This folder is mainly for storing datasets used for training/validation/testing.

## Practice

1. Separate your codes and datasets. So it is better to soft link your dataset (such as DIV2K, FFHQ, *etc*) here.
    ```bash
    ln -s DATASET_PATH ./
    ```

## Example Datasets
datasets can be downloaded from https://github.com/csguoh/MambaIR
```bash
python scripts/prepare_example_data.py
```

The example datasets are now in the `datasets/example` folder.
