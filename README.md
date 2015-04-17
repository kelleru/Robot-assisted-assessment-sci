# Robot-assisted-assessment-sci
This repository was set up accompanying the publication 'Robot-Assisted Arm Assessments in Spinal Cord Injured Patients: A Consideration of Concept Study' in the PLOS ONE journal. 

Contact information: urs.keller@hest.ethz.ch, robert.riener@hest.ethz.ch, verena.klamroth@hest.ethz.ch 

This repository encompasses two zip-files. 'MATLAB_evaluation_with_sample_data' consists of the MATLAB evaluation code to calculate the assessment parameters and 'SPSS_assessment_parameter_data' includes all the robot-assisted assessment parameters which were used for the analysis in the paper.

MATLAB_evaluation_with_sample_data folder
---------------------------

The subfolder 'data' consists of the logged files from the five different robot-assisted assessment packages. The files are sample data from a subject recording. In order to compute the assessment parameters the 'Evaluate.m' file has to be run with MATLAB. The output parameters are saved as .txt files in the 'Evaluate_output' folder. There are more parameters saved during the MATLAB evaluation than we actually used in the SPSS analysis. 
The subfolder 'auxiliary functions' holds all the non-standard functions needed to run 'Evaluation.m'.

SPSS_assessment_parameter_data folder
------------------------------------

The SPSS folder consists of three subfolders. The first two folders comprise the assessment parameters calculated for the healthy subjects for the dominant and the nondominant hand: 'Healthy dominant (intra-rater analysis)' and 'Healthy nondominant (to complete norm data)'. The third folder includes the patient assessment parameters for the five patients measured: 'Patients all assessments.sav'.
For healthy subjects and for patients the parameter data for the five different assessments are included (ROM, WORKSPACE, QOM, STRENGTH and RPM). Furthermore, there are parameters in the SPSS data files for single directions and for single targets, while in the paper, only the mean values were used. Additionally, parameters are listed for the WORKSPACE assessment, which were not used for the analysis in the paper.

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.16933.svg)](http://dx.doi.org/10.5281/zenodo.16933)
