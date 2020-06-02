# ADNI3_PIPELINE_Baycrest_grid
HCP pileline: at 
/opt/HCPpipelines-4.1.3/

Fix: /opt/HCPpipelines-4.1.3/fix

MSM at /opt/HCPpipelines-4.1.3/MSM

MSMALL at /opt/HCPpipelines-4.1.3/MSMALL

workbench at  /opt/HCPpipelines-4.1.3/workbench

ICAFIX at  /opt/HCPpipelines-4.1.3/ICAFIX

FSL 6.0-3 at /opt/HCPpipelines-4.1.3/fsl

Matlab runtime folder:
/opt/MatlabR2017b/MATLAB_Runtime/v93/

Python evironment: anaconda 2 at /home/jwang/software/anaconda2

When running ICAFIX, R 3.4.3 version is required. The R 3.4-3 is installed using anaconda 3. YOU have to change python evironment to anaconda3.
'kernlab' version 0.9.24, 'party' version 1.0.25, 'e1071' version 1.6.7 or  'randomForest' version 4.6.12

In R, runing:
require(devtools)
require(devtools)
install_version("kernlab", version="0.9-24")
install_version("ROCR", version="1.0-7")
install_version("class", version="7.3-14")
install_version("party", version="1.0-25")
install_version("e1071", version="1.6-7")
install_version("randomForest", version="4.6-12")



Anaconda 3 at /home/jwang/anaconda3

creat enviroment variable myR  for R 3.4-3

/home/jwang/anaconda3/envs/myR/bin/R

