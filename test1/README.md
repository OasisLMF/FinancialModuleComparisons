# Direct insurance exposed limit test

This test demonstrates how different catastrophe loss modelling platforms;

1) express deductibles and limits in their input exposure data format

2) calculate the maximum insurance exposed limit for a ground up loss scenario of 100% damage for all locations


## Source exposures

The source exposures for this test come from the OasisLMF validation test 'insurance' covering direct insurance terms, in OED v2.0.0 format.
https://github.com/OasisLMF/OasisLMF/tree/main/validation/insurance

There are 300 accounts with commonly used combinations of deductibles and limits which apply at various hierarchal levels.


## Platform results 

The naming convention for each set of results is;

{platform/UI name - version}_{engine name - version}_{exposure format name - version}

### Input

The input folder consists of one or more files representing the source exposures translated in the platforms's native exposure data format, or if the platform supports multiple exposure data formats, the input format used to generate the results in the output folder.

### Output

The output is a flat file showing ground up and gross loss by policy with identifiers.


