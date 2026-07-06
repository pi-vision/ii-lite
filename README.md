# ii-lite

Lightweight intensity interferometry simulations for SPADs and single-photon counters.

`ii-lite` starts as a small notebook-first workspace for simple calculations around photon counting, coincidence rates, and temporal coherence. The long-term direction is intensity interferometry imaging, but the initial repo intentionally stays bare bones.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Notebooks

- `notebooks/01_timestamp_g2_basics.ipynb` - timestamp-based `g2` estimation with expected pairs per `g2` bin as the brightness control.
- `notebooks/02_spad_nonidealities.ipynb` - SPAD timing jitter and its effect on timestamp `g2`, comparing the Poisson-limited estimate with the jittered estimate.

## Dependencies

The initial notebooks require:

- NumPy
- Matplotlib
- Astropy
- tqdm
