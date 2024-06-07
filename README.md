## Collection of field IP data

In the 7th workshop we (again) came across the idea of sharing field data sets for the purpose of improving our data analysis methods. 

They should ideally have a few properties
* availability of reference data, e.g. borehole logs, cores, samples, lab measurements
* citeability by an accompagnying paper with some results to compare with
* long-time availability by a DOI or archive (e.g. zenodo, supplementary data to paper)

We don't attempt to collect all data, but we should aim for a wide range of applications (e.g. landfills, mineral exploration, groundwater studies) and technical details (instruments, arrays, geometries, acquisition settings) but also effects like inductive and capacitive coupling.

Furthermore, I think this repository should NOT necessarily contain raw data, because there is another repository dedicated to processing (and it would quickly become very large). Instead, we should use any sort of processed data: directly from the instrument, hand processing, Workbench etc.

We are still developing a unified data format that the inversion codes (there is also a repository about software) can import. In the meanwhile, we can use any ASCII-readable format that is widespread use and well documented. 

Let us first start with
* some discussions
* collecting papers in a bibliography file
* maybe one issue for any of the datasets with descriptions, discussions, results
