# libm2k-labview

LabVIEW bindings for the [libm2k](https://github.com/analogdevicesinc/libm2k) interface library.

Documentation is available on [wiki.analog.com](https://wiki.analog.com/university/tools/m2k/labview).

The C++ API reference is available on [GitHub](https://analogdevicesinc.github.io/libm2k/index.html).

The LabVIEW VI documentation is available on [GitHub](https://analogdevicesinc.github.io/libm2k-labview/index.html).

## Releases

Always use the latest release VI Package from the [releases page](https://github.com/analogdevicesinc/libm2k-labview/releases/latest).


## Installing

1. The first step is to install libm2k using the Windows system installer. Go to [libm2k release page](https://github.com/analogdevicesinc/libm2k/releases/latest) or use the [nightly builds](https://ci.appveyor.com/project/analogdevicesinc/libm2k).
The LabVIEW wrapper is available only starting from official version v0.4.0.
In the libm2k system installer, check the "Install wrapper for LabVIEW bindings" box. The base library and the wrapper will be installed in your system.

2. Download the latest ADALM2000 VI Package from the Release section on the following page: [ADALM2000 LabVIEW repository](https://github.com/analogdevicesinc/libm2k-labview) .
Load the VIP package in the VI Package Manager, install the package.
After that, there will be a new palette, named Analog Devices -> ADALM2000, in LabVIEW.


## Documentation

Documentation is provided on the following page: [ADALM2000 LabVIEW Documentation](https://wiki.analog.com/university/tools/m2k/labview)


## Note

1. The VI Package was tested on version 2015 and 2020 of LabVIEW.
2. The VI Package was only tested on Windows so far.
3. As this is still under development, bugs might still appear.
4. Feedback is appreciated - bugs and questions can be posted on the [Github issue tracker](https://github.com/analogdevicesinc/libm2k/issues) or the [ADI Engineer Zone](https://ez.analog.com/adieducation/university-program/).
