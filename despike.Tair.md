Despike 2m air temperature (Tair)
=================================

1. detect spikes (applied for each month)
    - when residual after remove diurnal and sub-diurnal cycle (harmonic wave number = days & days*2) is greater than 6-sigma
    - only for grids having considerable diurnal cycle (here, when 3-hourly variance < diurnal & sub-diurnal cycle * 2)

2. apply fail-safe
    - considering observational record lowest/highest (-89.2, 58 degC), clipping out 3-hourly value which exceeds -95 and 65 degC.

3. replace spikes
    - spikes replaced with linearly interpolated residuals + diurnal & sub-diurnal cycle

