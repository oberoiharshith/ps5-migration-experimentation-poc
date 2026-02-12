# PS4 → PS5 Migration Experimentation POC (Synthetic)

This mini-project demonstrates how to design and analyze:
- A/B tests for migration campaigns
- Variance reduction (CUPED)
- Bayesian conversion readouts (Beta-Binomial)
- Sequential testing / early stopping (O'Brien-Fleming + Bayesian monitoring)
- Simple heterogeneous treatment effects

## Files
- `Migration_Experimentation_POC.ipynb` – end-to-end notebook
- `data/migration_experiment_synthetic.csv` – synthetic dataset (50k users)

## Quick start (local)
1. Create a clean env:
   - `python -m venv .venv && source .venv/bin/activate` (mac/linux)
   - `python -m venv .venv && .venv\Scripts\activate` (windows)
2. Install deps:
   - `pip install -U pandas numpy scipy matplotlib jupyter nbformat`
3. Run:
   - `jupyter notebook`
4. Open `Migration_Experimentation_POC.ipynb` and run all cells.

## Notes
The dataset is synthetic and meant only to demonstrate methodology and communication.
