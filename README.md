# HDR-US
High Dynamic Range Ultrasound Imaging

### 1. Related Papers
* **High Dynamic Range Ultrasound Imaging**, *A. Degirmenci, D. P. Perrin, R. D. Howe*, submitted to IPCAI 2018.

### 2. Installation
Download the repo to your machine:

	git clone https://github.com/adegirmenci/HDR-US.git
	
From the root project directory, run the install script:

	installHDRUS

  
#### 2.1 Required MATLAB Toolboxes
* Image Processing Toolbox

#### 2.2 Dependencies

We use F. Banterle's HDR Toolbox (https://github.com/banterle/HDR_Toolbox). The DebevecCRF function is modified to return two extra variables, logE and stack samples.

### 3 Usage
Run the MATLAB script HDR-US.m.

### 5 License
HDR-US was developed at the Harvard Biorobotics Lab.
The  licensed under the GNU General Public License
Version 3 (GPLv3).