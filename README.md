# CLExplorer

CLExplorer is a standalone interactive 3D tool for Chain Lightning upgrade analysis.

It visualizes all Damage/Quantity/Chance combinations, where:
- marker size = Effective Damage (`Damage x Quantity x Chance`)
- marker color = Total Cost

## Repository Structure

- `index.html` - main explorer app (GitHub Pages entry point)
- `data/Tower Stats - Chain Lightning.csv` - source stat table
- `data/chain_lightning_combinations_efficiency.csv` - all computed combinations
- `data/chain_lightning_best_value_efficiency.csv` - global Best Value points
- `data/chain_lightning_efficient_path.csv` - step-by-step efficient upgrade path

## Run Locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

Set Pages source to branch `main` and folder `/ (root)`.
