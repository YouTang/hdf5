# HDF5_Caller
We develop a cross-platform plugin called HDF5_Caller to convert .fasta reference sequence data to .hdf5 format and provide efficient indexing and querying services for HDF5_based reference files. By calling the plugin, hundreds of gigabytes of data can fast access to reference genome data, while retaining a small disk space footprint by using HDF5 special index mechanism. It supports parallel process on desktop computer, by which the access speed of human genome file is 40 times faster in a single thread mode and 100 times faster in multi-threaded mode than that of .fasta formats. HDF5_caller packaged as an executable JAR file can be called by other programs based on C, R or Java development environment, and it could provide open interface for researchers to develop their various downstream analyses extremely fast and flexible by themselves.
