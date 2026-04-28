# Blazhko and LTTE Visualizer

Static web app for exploring a theoretical RR Lyrae light curve with optional Blazhko modulation and light travel time effect phase shifts.

The browser reads `data/theoretical_lightcurve.json`, generated from the OGLE-based Fourier template and fitted default parameters by:

```bash
python .\scripts\build_lightcurve.py
```

Run locally from this directory with:

```bash
python -m http.server 8765
```
