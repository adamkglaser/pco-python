# pco-python

PCO camera drivers based on the PCO python SDK at https://pypi.org/project/pco/

*FIXED:* Bug which prevents the original SDK from opening cameras using the function OpenCameraEx which allows specification of exact camera number (when >1 camera connected). Issue with recorder function of the camera class which resets the shutter mode of the camera. Now split into two functions, first generates/initializes the recorder (then camera shutter mode can be set) followed by a second which starts the recorder.

*ADDED:* Functions GetCmosLineTiming, SetCmosLineTiming, GetCmosLineExposureDelay, SetCmosLineExposureDelay for light-sheet readout mode on the PCO edge cameras.
