We provide the large-scale PeMS speed datasets (nearly 90 million observations) to demonstrate the usage of LETC model. Graph information is also provided for construction of adjacent matrix by unzipping the file `adj_mat.7z`. The original PeMS-4W traffic speed data can be downloaded from [this link](https://zenodo.org/record/3939793). Ones should first download the raw data `pems-4w.csv` from source and save the csv file in `dataset/pems'.
`graph_sensor_locations_11k.csv` provides the id, longitude, and latitude for each unique sensor. Geometric files are also provided in the `shape_files` folder to visualize the California highway network.

- PeMS-4W data set:
> This data set contains freeway traffic speed collected from 11160 traffic measurement sensors over 4 weeks (the first 4 weeks in the year of 2018) with a 5-min time resolution in California. It can be arranged in a spatiotemporal tensor with size 11160 x 288 x 28. The pre-processed dataset is stored in the csv format.
`
