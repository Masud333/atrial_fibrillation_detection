#

(1) Import data files (phsyionet-data) into home directory of cygwin64/32

(2) Download and install cygwin. Follow installtion guide on:
(https://archive.physionet.org/physiotools/cygwin/)
Make sure to install all the necessary packages provdied at the bottom of step 9!

(3) Follow the steps provided in the README.md of this github: 
(https://github.com/mondejar/WFDB-utils-and-others#3-using-ecgpuwave-to-detect-p-qrs-t-onoff-waves)

(4) Run in cygwin terminal any of the commands 

(example for reading record "04936")	----->	 rdann -r 04936 -f 0 -a atr -v > rdann/04936_atr.txt

See also Testing.ipynb file for ideas on programming linux command in from jupyter notebook.
OBS! Not all have been working, but it is possible to get some output. 

(5) Output found in the root C-drive, where cygwin is installed: C:\cygwin64\home\username

(6) IF POSSIBLE: explore ecgpuwave command from the cygwin terminal.
(https://physionet.org/content/ecgpuwave/1.3.4/)
