# Tools We Want

In this file we put in ideas about tools we want, and feature additions we want into the logfiles. Anyone putting in new tools idea should put their initials and the date this discussion started, and also give the idea a name. This is so we can search.
See example below for how.


## AD::4/21/2021::AcrossExperiments
A tool that can search for data across experiments in the same study given a set of keyswords.
For example one could say list average/max/min time for gcfill in hydro on 2K MPI  ranks.
The result should come out in a tabular form.


## TK::06/02/2021::Requirements-for-Flash-X
- Output csv table of timers data from IO unit
- Include a header with important metadata
	- Problem name
	- Repo version
	- Number of procs
	- Problem size (nblockx,nblocky,nblockz)
	- Total num blocks at each refinement
- There should be 4 columns - time for proc 0, min, max, avg
- If prossible, try to include the proc that had max, min

## TK::06/02/2021:Requirements-for-Graphical-Analysis
Import all data into Python, should be able to query and plot various quantities. Start with just plotting one timer vs. number of procs.


## AVD:10/18/2022::Jobrunner
A tool to enable re-use of files/scripts for job runs and manage complexities of simulation runs. Initial design is available here: https://github.com/akashdhruv/Jobrunner
