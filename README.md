# TRAP-In-Vivo-Analysis
Code and data related to Figures 1 and S1 in Ryan et al., 2024

TRAP_InVivo_Analysis.m performs analysis of data collected using Plexon MAP system and spike sorted using Plexon Offline Sorter. Data is then saved as nex files and NeuroExplorer is used to open and export data to matlab.
TRAP_Remove_INs.m is run once data has been analyzed and Summary struct made to remove putative INs, identified based on waveform, from the data and added to a separate struct.

Summary.mat is a struct that contains summary behavior and electrophysiology for each animal/session used to generate figures 1B-C,G-K and S1B-D,M.

Raw and processed data can be found here:
