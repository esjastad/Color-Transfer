# Color Transfer
## Color Transfer CS410/510 Computer Vision
This python program transfers the color scheme from one image to another

## Linux: 

**1. Install anaconda:**

wget https://repo.continuum.io/archive/Anaconda3-2018.12-Linux-x86_64.sh  
bash Anaconda3-2018.12-Linux-x86_64.sh -b -p $HOME/anaconda  
export PATH="$HOME/anaconda/bin:$PATH"  
conda update --all  

**2. Install necessary libraries:**

pip install opencv-python  
pip install scikit-image  


## Windows: 

**1. Download and install anaconda environment Python 3.7: **
Download: https://www.anaconda.com/download/#windows  
Install: http://docs.anaconda.com/anaconda/install/windows/  

**2. Open Anaconda Prompt**
Start Menu / Anaconda3 / Anaconda Prompt  

**3. In Anaconda Prompt, type commands to install necessary libraries:**

pip install opencv-python  
pip install scikit-image  

## Running the file
color_transfer.py takes in 5 arguments  
arg 1 = the image file to apply the color scheme to  
arg 2 = the image file to take the color scheme from  
arg 3 = The resulting transfers file name for using Lab color space  
arg 4 = The resulting transfers file name using RGB color space  
arg 5 = The resulting transfers file when using CIECAM97s color space  
**EXAMPLE**  
python color_transfer.py source1.png target1.png LabResult.png RGBResult.png CIECAM97sResult.png  

## Examples Provided
The provided sources are for argument 1  
The provided targets are for argument 2  

The results files are what you should get for your file name in argument 3,
**May contain errors if depending on the images used**
.
Author: Erik Jastad  

Resources: http://www.cs.tau.ac.il/~turkel/imagepapers/ColorTransfer.pdf
