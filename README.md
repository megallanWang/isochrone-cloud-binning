# isochrone-cloud-binning

Interactive comparison of observed and synthetic CMDs for NGC 6866.

## Contents

- `index.html`: GitHub Pages entry point
- `cmd_comparison.html`: main interactive poster page
- `parsec_cmd_subset.json`: PARSEC model grid subset
- `mist_cmd_subset.json`: MIST model grid subset
- `ngc6866_cmd_points.json`: observed CMD data
- `pulsators_gdor.json`: g-mode pulsator data

## Local preview

From this folder, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## GitHub Pages

If GitHub Pages is enabled for the `main` branch at the repository root, the site will open from:

```text
https://megallanWang.github.io/isochrone-cloud-binning/
```
