**System requirements**

The 1P-2P-coregistration software is used with Python 3, and was tested on macOS Tahoe 26.2. All packages are listed in the requirements.txt file. See installation guide for details. No non-standard hardware is required.

**Installation guide**

Pacakges can be installed in a jupyterlab cell with python 3 kernel.
```
pip install -r requirements.txt`
```

**Demo and instructions for use**

The folder `vessel&plaque2.oif.files` contains the raw image data from 2-photon microscope, which is necessary when you read the `vessel&plaque2.oif` file. 

`1P_MAXproj.tiff` is the image data from 1-photon miniscope.

The `1p-2p-coreg.ipynb` notebook does the co-registration of vessels from 1-photon miniscope and 2-photon microscope, so that 1-photon imaging can be transformed into the space of 2-photon imaging. It takes `1P_MAXproj.tiff` and `vessel&plaque2.oif` as input, and output co-registered vessels as well as computed transformation parameters.
