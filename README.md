# pco-python

PCO camera drivers based on the PCO python SDK at https://pypi.org/project/pco/

*FIXED:* Bug which prevents the original SDK from opening cameras using the function OpenCameraEx which allows specification of exact camera number (when >1 camera connected).

*ADDED:* Functions GetCmosLineTiming, SetCmosLineTiming, GetCmosLineExposureDelay, SetCmosLineExposureDelay for light-sheet readout mode on the PCO edge cameras.
