# Reproducible engineering analysis

All displayed experiment charts are generated using Python, NumPy and Matplotlib. Numeric data are transcribed from named lab reports in the author’s Google Drive; source CSV files are in `/data`. Charts labeled “reported” are based on reported measurements or reported aggregate estimates. They are not fabricated measurements.

- **LVDT**: `lvdt_reported_fits.csv` contains three reported fitted slopes, correlations and factory factor. `lvdt_reported_daq.csv` contains nine recorded voltage/displacement pairs. Do not treat the fit summary as raw samples.
- **Pressure vessel**: `pressure_reported_trials.csv` has 12 paired hoop/axial pressure estimates against 40 psi applied pressure. Difference and systematic bias can be recomputed.
- **Springs**: `spring_reported_estimates.csv` contains the three reported static/dynamic stiffness estimates.
- **Friction**: `friction_reported_estimates.csv` contains nine reported coefficients. The source has some ambiguous headings; these values are reported results rather than raw time-of-flight reconstructions.
- **UAV**: `uav_model_ground_roll.csv` is **calculated, not measured**. The simplified spreadsheet assumptions are m=230 kg, rho=1.225 kg/m3, S=3.025 m2, CL=0.6, CD=0.01, T=300 N, rolling coefficient=0.02, dt=0.1 s. The model uses constant thrust/mass, no wind, and lift-reduced normal force. These are preliminary assumptions, not a validated aircraft design.

The source reports also include plots without numerical backing tables. Those are not reconstructed as measured data. For thermal, airfoil, turbidity, LCR and tuned-mass-damper entries, further original datasets are needed before publishing numeric measured curves. ANSYS is not presented as completed project experience.
