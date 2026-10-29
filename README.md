# Motion and River Forecasting

- **River forecasting:** a proposal for one-hour water-level forecasts at four stations.
- **Moving MNIST:** ConvLSTM prediction with speed augmentation, a larger-reach model and symmetry averaging.

[Report](25280039_PA2.pdf) · [Q2 notebook](Question2_normalized/Question2_final.ipynb)

## Run

Use Python 3.12. From the repository root:

```bash
python3.12 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m notebook Question2_normalized/Question2_final.ipynb
```

Restart the kernel and run sections in order. The notebook downloads Moving MNIST into
`data/` and writes new outputs to `Question2_normalized/run_artifacts/`. Both locations are
ignored by Git. A fresh run trains all four models for seeds 0 and 1, 30 epochs each.
No training weights are included. Saved notebook outputs show the completed experiment.

## Included files

- `25280039_PA2.pdf`: final report.
- `predictions.txt`: Q2.5 and Q2.11 text.
- `Question2_normalized/Question2_final.ipynb`: complete Q2 code and saved outputs.
- `Question2_normalized/artifacts/gifs/`: eight required GIFs at the paths cited in the PDF.
- `requirements.txt`: dependencies.
- `.gitignore`: local environments, data and new-run outputs excluded from Git.
