DATASETS software
Version 0.12		Friday 20 Jan 2006 at 18:42
Copyright (c) 2006 Neil D. Lawrence

This toolbox stores datasets and gives commands for accessing them.

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

lvmLoadData.m: Load a dataset.
mocapConnections.m: Give a connection matrix for the motion capture data.
mocapLoadTextData.m: Load a motion capture dataset.
mocapParseText.m: Parse a motion capture text file.
parseWirelessData.m: Load wireless strength data.
parseNobleKernelFile.m: Load wireless strength data.
mapLoadData.m: Load a dataset.
xlsLoadData.m: Wrapper function for xlsread to get files from the datasets directory.
datasetsDirectory.m: Returns directory where data is stored.
