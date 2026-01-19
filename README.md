# MultiBench++
Official code of MULTIBENCH++: A Unified and Comprehensive Multimodal Fusion Benchmarking Across Specialized Domains 

## Requirements

### Dataset
Follow [DATASET.md](DATASET.md) to install datasets.

## Get Started
### Example usage

#### 1. Data Preparation

All datasets should be organized under the `data/` directory.

**Setting up the MAMI Dataset:**

1.  Follow the instructions in [DATASET.md](DATASET.md) to download the MAMI dataset.
2.  Place the downloaded data into the `data/MAMI/` directory.

The expected directory structure is as follows:

```text
ProjectRoot/
├── data/
│   └── MAMI/
│       └── (dataset files...)
├── exper/
│   └── MAMI/
│       └── baseline.py
└── ...

```

#### 2. Running Experiments

To reproduce the reported results, navigate to the dataset-specific directory within `exper/` and execute the python script.

**Run MAMI Experiment:**

```bash
# Navigate to the experiment directory
cd exper/MAMI/

# Run the experiment script
python baseline.py

```

### Encoders

For the Bert model, download bert-base-uncased ([Google Drive Link](https://drive.google.com/file/d/1ivh-3aHtoqRMwVN4ZOPvPm59pFP93-hD/view)) and place it in the root folder `bert-base-uncased/`.

### Acknowledgements

Our implementation is built upon [MULTIBENCH](https://github.com/pliang279/MultiBench). We thank the authors for their excellent open-source work.

