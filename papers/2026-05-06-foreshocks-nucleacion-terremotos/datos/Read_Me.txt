This data set corresponds to the manuscript, "From foreshock to mainshock: transient sliding velocity sets nucleation time" by B. Fryer, D. Garagash, M. Lebihain, and F. Passelègue.

A description of the contents of each file follows:

Laboratory_Results_Summary.csv
Corresponds to laboratory data associated with the manuscript. Self explanatory headings.

EofM_Dslip_vs_Veff.csv
EoM data organized as [V0 mup/(b sigma cs), df0/b, Veffmin/V0, Veffmin * dtc/L]

EofM_Veff_vs_DT.csv
EoM simulation data organized as [V0 mup/(b sigma cs), df0/b, dT/(mup L), Veffmin/V0]

EofM_lc_vs_Dtc.csv
EoM simulation data organized as [V0 mup/(b sigma cs), df0/b, dtc*cs/lb, lc/lb]

Files of type "ldomainlistx.csv", "timelistsx.csv", "Vefflistsx.csv", and "vrlistsx.csv": These are EoM simulation results files. The x corresponds to the overstress of each file df0/b. Each column corresponds to a specific foreshock slip value 0.25, 0.5, ..., 2.5 microns in increments of 0.25 microns. These files should be used together.
The crack length is l/lb, the time is t*cs/L, the Veff is Veff/cs, and the rupture velocity is vr/cs

Unfortunately, Zenodo limits the size of uploads such that we cannot easily provide the raw data for the experiments nor can we readily provide the .tiffs used to make the videograms. As a compromise, we provide the treated data on separate Zenodo pages:

Experiments at 100 and 150 bar: 10.5281/zenodo.17241934
Experiments at 200 and 250 bar: 10.5281/zenodo.17242681
Experiments at 300 bar: 10.5281/zenodo.17242866

Each experiment has accelerometer data (beginning with "Acc_"), strain gauge data (beginning with "SG_") and displacement sensor data (beginning with "Disp_").

The accelerometer data contains 15 columns: 1:13 with acceleration in m/sec^2. Column 14 is time in seconds. Column 15 is the trigger.
The accelerometers' positions are:
%Accelerometer x-positions [m]
Acc.input_acc_pos_x_full = [19 50.5 80 109 139.5 170.5 201.5 231.5 260.5 297.5 320.5 351.5 382;
    19 50.5 80 109 139.5 180 201.5 231.5 260.5 297.5 320.5 351.5 382;
    19 50.5 80 109 139.5 185 201.5 231.5 270 297.5 320.5 351.5 392]'*.001;
%Accelerometer y-positions [m]
Acc.input_acc_pos_y_full = [25 26 26 29 29 28 29 30 29 30 27 29 26;
    25 26 26 29 29 31 29 30 29 30 27 29 26;
    25 26 26 29 29 10 29 30 39 30 27 29 39]'*.001;
Take row 2 for Nuc_250bar_FullStop_A and Nuc_300bar_TopStop_A. Take row 3 for Nuc_300bar_FullStop_A. Take row 1 for all other experiments.
	
The strain gauge data contains 80 columns. Columns 1:13 are exx, 14:26 are eyy, 27:39 are exy, 40:52 are Sxx [Pa], 53:65 are Syy [Pa], 66:78 are Sxy [Pa], 79 is time in seconds, 80 is the trigger.
The strain gauge positions are:
%Strain gauge x-positions [m]
SG.input_sg_pos_x = [1.90 5.05 8.00 10.90 13.95 17.05 20.15 23.15 26.05 39.4 32.05 35.15 38.20]'*.01;
%Strain gauge y-positions [m]
SG.input_sg_pos_y = [3.0 2.5 2.5 2.75 2.5 2.5 2.5 2.5 3.0 3.0 3.0 3.0 2.5]'*.001;

The displacement data contains 22 columns. Columns 1:10 are displacements in mm. Columns 11:20 are the error in mm. Column 21 is time in seconds. Column 22 is the trigger. 
The displacmeent sensors' positions are:
%Displacement sensors x-positions [m]
DS.input_sg_pos_x = [245 365 335 305 275 155 125 95 65 35]'*.001;

For questions, please contact barnaby.fryer@geoazur.unice.fr