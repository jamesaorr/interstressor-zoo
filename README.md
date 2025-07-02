Data and code associated with the interstressor zooplankton project.

The `data` folder contains the raw data from the study (in the `input` subfolder) and the processed data (in the `output` subfolder). The `input` data folder contains the experimental design (`interstressor-design.csv`), water volume data (`water-volume-interstressor.csv`), and the raw zooplankton data (`microscope`, `x2`, `x4`).

The `1-data-prep.Rmd` R notebook cleans and combines all of the raw data into a single data frame. 

The `2-data-organisation.Rmd` R notebook summarises the raw data by sample (n = 512) and computes community metrics. 

The `3-univariate.Rmd` R notebook visualises and analyses the univariate community data to explore co-tolerance patterns, recovery dynamics, and memory effects.

The `4-multivariate.Rmd` R notebook visualises and analyses the multivariate community data to explore recovery dynamics and memory effects.


