OpenFOAM® and OpenCFD® are registered trademarks of OpenCFD Limited, the producer OpenFOAM software. All registered trademarks are property of their respective owners.
This offering is not approved or endorsed by OpenCFD Limited, the producer of the OpenFOAM software and owner of the OPENFOAM® and OpenCFD® trade marks.
http://openfoam.org/

# varingPressureGradientExplicitSource
Creates a time-varying pressure gradient source.
This code is based on the original
 pressureGradientExplicitSource but incorporating the DataEntry class is the same way as fixedTemperatureConstraint class.


pressureGradientExplicitSource sourc code:
https://github.com/OpenFOAM/OpenFOAM-2.4.x/tree/master/src/fvOptions/sources/derived/pressureGradientExplicitSource

fixedTemperatureConstraint source code:
https://github.com/OpenFOAM/OpenFOAM-2.4.x/tree/master/src/fvOptions/constraints/derived/fixedTemperatureConstraint



This modification is based on a discussion on CFD-online with Mr. Mahmoud Aboukhedr: 
http://www.cfd-online.com/Forums/openfoam-programming-development/153156-assigning-time-dependent-heat-source-terms.html#post557822

This code is not fully tested yet and should be used with caution! 
