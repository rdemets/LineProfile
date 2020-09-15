# LineProfile
%%% This program aim to draw and realign the line profile on 2D images
%%% It needs tif of a single plan with multiple channel
%%% The choosen channel is displayed to draw every profile line needed
%%% The line has to be drawn from left to right !!!
%%% Image will then be rotated to have an horizontal line. A window around the line is defined
%%% Range of adjustable size are used to bin the data to improve realignment. 
%%% Realignent in done based on the selected channel. The profile along the
%%% selected line is then performed and saved in the Result variable.
%%% 
%%% The program give the posibilty to select only a range of data according
%%% to the intensity level of one of the channel, or range of population. The result is then
%%% plotted and fitted with a gaussian curve.

%%% Adjustable parameter : Staining, Window for line profile, width of the
%%% line for realignment, range for intensity selection, Range around the junction to visualize (L197) 
%%% Not yet : /
%%% Save for different range of intensity


Please cite "Artificial microniche array with spatially structured biochemical cues"
X Gao, C Stoecklin, Y Zhang, Z Weng, R De Mets… - Cell-Based Microarrays, 2018
