This repository contains the input files (and some output logs) from the verification analyses of the manuscript "Multigrid-based, selective mass scaling for explicit dynamic analysis of nonlinear solids and structures" by I. Koutromanos, M. Mavros.


All analyses have been conducted by the research code FEMultiPhys. 

Each subfolder contains the input files from a specific analysis case, described in more detail in the README.txt files contained in the subfolder. Each set of input files is accompanied by a file "messagelog.txt", containing analysis data logged during the runs (timestamp of each specific output step, etc.). The messagelog.txt files also mention (in the beginning) the exact version of the code that was used to run them. Newer versions of the code should be expected to yield identical results as those shown in the manuscript (as newer versions only add features and resolve bugs).

To run an analysis (Windows systems only), simply take the FEMultiPhys latest executable, which can be downloaded from free from the following link: https://drive.google.com/open?id=13Zk7fM3T50F57HNm4Um4nHUggVOrubRx&usp=drive_fs

Extract the executable fe_program.exe from the compressed folder, then paste it inside the specific analysis case that you are interested, then start the exe. The analysis should begin and complete automatically).

If help or further information is needed, please reach out at ikoutrom@vt.edu

The analysis output should (by default) be compatible with the graphical pre- and post-processor LS-Prepost: https://lsdyna.ansys.com/ls-prepost-2/

Further information on user documentation, step-by-step tutorials, installation of GUIs for managing FEMultiPhys etc., can be accessed in the following link. 

https://www.youtube.com/watch?v=fV_83Ljt1BY&list=PLmf-Ru5Df7CyRyMwrzGRU136cmgOzSIwS

