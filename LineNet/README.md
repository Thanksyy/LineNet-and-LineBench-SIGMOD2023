# LineNet

## How to prepare python environment for LineNet:

```
conda create -n linenet python=3.8
conda activate linenet
pip install -r <path-to-this-dir>/requirements.txt
```

In case you are using recent hardware with cuda version >= 12.1, use the following instructions instead:

```
conda create -n linenet python=3.8
conda activate linenet
pip install -r <path-to-this-dir>/requirements_cu12.txt
```

## How to run LineNet:

1.Place dataset under ./datasets folder.

2.Run the following scripts:

```
make run-aq-semihard
make run-eeg-semihard
make run-stocks-semihard
make run-traffic-semihard

make run-aq-diversified
make run-eeg-diversified
make run-stocks-diversified
make run-traffic-diversified
```