DATASETS software
Version 0.13		Friday 03 Nov 2006 at 14:23
Copyright (c) 2006 Neil D. Lawrence

This toolbox stores datasets and gives commands for accessing them.

Version 0.13
------------

Added processing for CMU data base motion capture figure 35. To load, the data should be downloaded from the CMU motion capture data base, http://mocap.cs.cmu.edu, and placed in baseDir/mocap/cmu/35/, where baseDir is the directory where you have placed 'datasetsDirectory.m'. You need the amc files and the asf file. 

Removed Example 86 motion 10 from the CMU motion capture data base.

Version 0.121
-------------

Modified robot traces example to reflect the fact that the data which is missing is genuinely missing rather than just reading low.

Version 0.12
------------

Added example 86 motion 10 in xyz format from CMU motion capture database: please credit the source of this data: http://mocap.cs.cmu.edu.

Added the datasetsDirectory.m command which makes use of the matlab which.m command to find out what directory it is in and returns this as the base directory for the datasets.

Added a command for reading in Excel spreadsheets as part of the same family as the other commands.

Version 0.11
------------

Added motion capture from Ohio State of a man running and vowel data from Jon Malkin at University of Washington.

Version 0.1
-----------

First release.

MATLAB Files
------------

Matlab files associated with the toolbox are:

datasetsDirectory.m: Returns directory where data is stored.
lvmLoadData.m: Load a latent variable model dataset.
mapLoadData.m: Load a mapping model dataset (e.g. classification, regression).
mocapConnections.m: Give a connection matrix for the motion capture data.
mocapLoadTextData.m: Load a motion capture data set from a text file.
mocapParseText.m: Parse a motion capture text file.
parseNobleKernelFile.m: Parse a kernel file from Bill Stafford Noble.
parseWirelessData.m: Load wireless strength data.
xlsLoadData.m: Wrapper function for xlsread to get files from the datasets directory.
