# clean_rawdata EEGLAB plugin

This plug-in, clean_rawdata uses methods (e.g., Artifact Subspace 
Reconstruction, ASR) by Christian Kothe from the BCILAB Toolbox 
(Kothe & Makeig, 2013), first wrapped into an EEGLAB plug-in by 
Makoto Miyakoshi and further developed by Arnaud Delorme with 
Scott Makeig.

This plugin clean raw EEG data. Methods from the BCILAB toolbox
are being used (in particular Artifact Subspace Reconstruction)
designed by Christian Kothe.

These functions were wraped up into an EEGLAB plugin by Makoto
Myakoshi, then later by Arnaud Delorme with input from Scott
Makeig.

The private folder contains 3rd party utilities, including:
- findjobj.m Copyright (C) 2007-2010 Yair M. Altman
- asr_calibrate.m and asr_process.m
 Copyright (C) 2013 The Regents of the University of California
 Note that this code is not free for commercial use.
- sperhicalSplineInterpolate.m Copyright (C) 2009 Jason Farquhar
- oct_fftfilt Copyright (C) 1996, 1997 John W. Eaton
- utility functions from the BCILAB toolbox Copyright (C) 2010-2014 Christian Kothe

The folder "manopt" contains the Matlab toolbox for optimization on manifolds.

# Version history
v0.34 and earlier - original versions

v1 - new default values for some of the rejection tools, new GUI

v2 - new improved GUI, compatibility with studies
