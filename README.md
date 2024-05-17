# Benedetti et al. 2024

## Supporting Software for Benedetti et al. 2024

This repository contains Julia <a href="https://plutojl.org/">Pluto.jl</a> notebooks in support of Lorena Benedetti et al. 2024

## Contents

The repository contains four Pluto.jl notebooks:

1. imagej_peaks_and_intervals_with_area.jl: Analyze ImageJ line traces for peaks
2. fft_analysis.jl: Perform Fourier-based filtering to analyze interval
3. raincloud.jl: Generate raincloud plots
4. periodicity.jl: Analysis periodicity via Fourier analysis

## Installation

1. Download the latest stable version of Julia (version 1.10.3 at the time of this writing).
2. Instantiate and activate the project contained in this repo.
```julia
using Pkg
Pkg.activate("Benedetti2024")
Pkg.resolve()
Pkg.instantiate()
```
3a. Run Pluto.jl and select the included notebooks.
```
using Pluto
Pluto.run()
```
3b. Alternatively, indicated the desired notebook as a keyword to `Pluto.run()`
```
using Pluto
Pluto.run(notebook="Benedetti2024/notebooks/periodicity.jl")
```

## Data

Currently, this repository only contains Julia code in the form of notebooks. It does not contain any of the underlying data. Please contact the authors to access the raw data.

## Maintainer

This repository is maintained by <a href="https://www.janelia.org/people/mark-kittisopikul">Mark Kittisopikul</a> on behalf of Janelia <a href="https://www.janelia.org/support-team/scientific-computing-software">Scientific Computing Software</a> and the <a href="https://www.janelia.org/lab/lippincott-schwartz-lab">Laboratory of Jennifer Lippincott-Schwartz</a>.

## License

See the LICENSE file for the 3-Clause BSD license. Copyright Howard Hughes Medical Institute.
