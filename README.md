# das


Notes for 2023 winter incubator


- **D**istributed **A**coustic **S**ensing ***Store***
- photonic 100-10kHz; what means 'multi channel'? "(100s-10,000s)" 
- community brainstorming best data format and metadata structure
- Two early programs
    - [DAS Research Collaboration Networks on Data formats](https://github.com/DAS-RCN/RCN_DASformat)
    - [Colorado School of Mines](https://github.com/DASDAE/dascore)
- IRIS not hosting; but the IRIS-DMC archive is moving to the cloud in 2023 with [TileDB](https://tiledb.com)
- UW Photonic Sensing Facility (PSF): 100sTBs of DAS data from early experiments
    - OOI
    - Whidbey Island
    - SeaDASN
    - Hanford-Dessication
    - Pending: NZ, AA, Cook Inlet Alaska, Central Valley California, Mt. Rainier Washington
    - PB scale in 2023
- Local cloud-store / emulator using [MinIO](https://min.io/)
    - Prep
        - += eScience
        - select data
        - benchmark local
        - github / conda
        - test scripts: I/O, feature extraction
    - Data format space
        - HDF5, but as inspired by see above
        - [Zarr](https://zarr.readthedocs.io/en/stable/#)
        - TileDB
    - Test; query system; 
    - Reporting / pub


- [MacCarthy, J., Marcillo, O., & Trabant, C. (2020). Seismology in the cloud: A new
streaming workflow. Seismological Research Letters, 91(3), 1804-1812.](https://github.com/robfatland/das/blob/main/references.md)
- Zhu, W., Hou, A. B., Yang, R., Datta, A., Mousavi, S. M., Ellsworth, W. L., & Beroza, G. C.
(2022). QuakeFlow: a scalable machine-learning-based earthquake monitoring workflow
with cloud computing. Geophysical Journal International, 232(1), 684-693.
- Zhan, Z. (2020). Distributed acoustic sensing turns fiber-optic cables into sensitive seismic
antennas. Seismological Research Letters, 91(1), 1-15.
- Guimaraes, A., Lacalle, L., Rodamilans, C. B., & Borin, E. (2021). High-performance IO
for seismic processing on the cloud. Concurrency and Computation: Practice and
Experience, 33(18), e6250.
- Spica, Z. J., Ajo-Franklin, J., Beroza, G., Biondi, B., Cheng, F., Gaite, B., ... & Zhu, T.
(2022). PubDAS: a PUBlic Distributed Acoustic Sensing datasets repository for
geosciences.
- Wang, X., Zhan, Z., Williams, E. F., Herráez, M. G., Martins, H. F., & Karrenbach, M.
(2021). Ground vibrations recorded by fiber-optic cables reveal traffic response to COVID-
19 lockdown measures in Pasadena, California. Communications Earth & Environment, 2(1), 1-9.
- Yang, Y., Atterholt, J. W., Shen, Z., Muir, J. B., Williams, E. F., & Zhan, Z. (2022). Sub-
Kilometer Correlation Between Near-Surface Structure and Ground Motion Measured With 
Distributed Acoustic Sensing. Geophysical Research Letters, 49(1),
e2021GL096503.
