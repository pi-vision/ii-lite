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

- `notebooks/spad-g2-temporal-coherence.ipynb` - initial SPAD notebook for `g2` and temporal coherence calculations.

## Dependencies

The initial notebooks require only:

- NumPy
- Matplotlib
