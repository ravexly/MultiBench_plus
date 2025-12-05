# MultiBench++
offical code of MULTIBENCH++: A Unified and Comprehensive Multimodal Fusion Benchmarking Across Specialized Domains 


## Requirements

### Dataset
Follow [DATASET.md](DATASET.md) to install datasets.

## Get Started
### Example usage

#### 1\. Data Preparation

All datasets should be organized under the `data/` directory.

**Setting up the IEMOCAP Dataset:**

1.  Download `IEMOCAP_features_raw.pkl` from the [soujanyaporia/multimodal-sentiment-analysis](https://github.com/soujanyaporia/multimodal-sentiment-analysis) repository.
2.  Place the downloaded file into the `data/IEMOCAP/` directory.

The expected directory structure is as follows:

```text
ProjectRoot/
├── data/
│   └── IEMOCAP/
│       └── IEMOCAP_features_raw.pkl
├── exper/
│   └── iemocap/
│       └── exper.py
└── ...
```

### 2\. Running Experiments

To reproduce the reported results, navigate to the dataset-specific directory within `exper/` and execute the python script.

**Run IEMOCAP Experiment:**

```bash
# Navigate to the experiment directory
cd exper/iemocap/

# Run the experiment script
python exper.py
```


### Acknowledgements

Our implementation is built upon [MULTIBENCH](https://github.com/pliang279/MultiBench). We thank the authors for their excellent open-source work.
