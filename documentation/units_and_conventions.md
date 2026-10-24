# Units and conventions

Temperatures are expressed in degrees Celsius (`_C`, `temperature_C`, `production_temperature_C`). Temperature differences have the same numerical increment as degrees Celsius. Lengths are in metres (`_m`). Time is supplied in seconds (`_s`), days (`_days`) or years (`_years`) where indicated by the column name. Energy is in joules (`_J`), power in watts (`_W`), and memory or storage normalisations use the dimensionless scales stated in the column names, notably `E0` or `Estar`.

`Fo` denotes Fourier number and is dimensionless. `eta` is the dimensionless normal-grid resolution indicator. Columns beginning with `relative`, `fraction`, `ratio`, `residual` or `error` are dimensionless unless the header gives an explicit unit. Percent values are explicitly labelled `percent`.

The energy-history and budget files preserve the sign convention of the original v0.6 numerical exports. Interpretation of individual inventory, interface, far-boundary and advective terms should follow the field names and the global-balance definitions in the associated manuscript. No sign reversal or unit conversion has been applied in this release.
