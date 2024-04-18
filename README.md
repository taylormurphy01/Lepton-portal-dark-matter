# Lepton portal dark matter

The lepton portal dark matter package is designed to enable automated calculations for models with various couplings between Standard Model leptons and scalar dark matter.
It contains a set of models written in the `FeynRules` language for `Mathematica` and pre-exported to the UFO format for usage within Monte Carlo event generators such as `MadGraph5_aMC@NLO`.

## Releases

This repository hosts `Lepton portal dark matter v1.0` and higher. 

## Available files

FeynRules source files are included for use in `Mathematica`. These files work in `Mathematica` v12.0 and above and with `FeynRules` v2.3.43 and above.

The SM `FeynRules` model file and various optional restriction files are also included. 

An example `Mathematica` notebook is included to demonstrate loading the model and generating a UFO output.

A UFO for `MadGraph` is included. This UFO has been (lightly) tested in MadGraph v3.3.1. It uses the four-flavor scheme and a diagonal CKM matrix.

## License

`Lepton portal dark matter` is released under the MIT License.
