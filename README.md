# Indoor Cellular Network (ICN) Mobile Service Demands

This page contains the code and data for the work "Characterizing Mobile Service Demands at Indoor Cellular Networks"

DOI link: https://doi.org/10.1145/3618257.3624807

<img src="images/paper_front.png" width="50%" height="100%"/>

For questions, please contact ssb45@cam.ac.uk or andre.zanella@imdea.org

In case you use the data/code/insights of our work in your study, please cite our paper using the following:
```bibtex
@inproceedings{10.1145/3618257.3624807,
  title={Characterizing Mobile Service Demands at Indoor Cellular Networks},
  author={Bakirtzis, Stefanos and Zanella, Andr{\'e} and Rubrichi, Stefania and Ziemlicki, Cezary and Smoreda, Zbigniew and Wassell, Ian and Zhang, Jie and Fiore, Marco and others},
  year={2023},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  doi={10.1145/3618257.3624807},
  url= = {https://doi.org/10.1145/3618257.3624807},
  booktitle = {Proceedings of the 23rd ACM Internet Measurement Conference},
  location = {Montreal, QC, Canada},
  series = {IMC '23}
}
```

## Data

The file "Antennas_RSCA.csv" includes the computed RSCA of the 73 (columns) mobile services under consideration for the 4762 (rows) indoor cellular network antennas included in our data set. The last column of the file designates the type of indoor environment in which the antenna is installed. The file "RSCA_Outdoor_Antennas.csv" includes the computed RSCA of the 73 (columns) mobile services under consideration for the neighboring outdoor antennas found within a 1km radius of the ICN antennas Access to raw traffic data can be provided upon agreement with the operator.

### Methodology:

A hierarchical clustering algorithm is employed to identify the clusters of ICN antennas based on similarities and differences in the RSCA values that denote under- or over-utilization of the 73 mobile services at each antenna with respect to typical usages. The clustering results are interpreted via SHAP and the clusters are juxtaposed with the type of indoor environment in which the antennas are installed.


## Acknowledgements
This work was supported by the European Commission through the Horizon 2020 Framework Program, H2020-MSCA-ITN-2019, MSCA-ITN-EID, under Grant 860239, BANYAN and the French National Research Agency, under Grant ANR-22-CE25-0016, CoCo5G project.
