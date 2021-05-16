# Thesis_SourceSeparation
repository with code for thesis

In the zip file, the files for our algorithm can be found. 
Gras_simulation is the main program, this file writes to specific folers so emptry folders with the following names should be made:
  - roomrecordings
  - split_positions
  - dataframes

The main program indicates when you should switch to R for the von Mises fitting. Both R and Python write their results to the dataframes folder. Furthermore the program is setup to immediatly run 15 different microphone positions. To run only one setup, you can uncomment all other source positions in the array "sources" on line 65. Make sure to update the loop in R accordingly! This has to be set manually aswell.

SignalFunctions provides some usefull code to make spectograms, generate white noise, etc.



