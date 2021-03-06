vizNII is a visualization tool of NIFTI images in Matlab

Here is an example
![alt tag](https://github.com/gostopa1/vizNII/blob/master/results/Tutorial4_result8.png)


I've made a couple of tutorials that should run rightaway just to show its possibilities.

Tutorial 1 horizontal:  reads a couple of niftis (from example_niftis/ folder) and  generates images (one of each plane, i.e. one saggital, coronal and axial) and stacks them horizontally  <br />
Tutorial 1 vertical:  same as the previous but in vertical fashion   <br />
Tutorial 2:  reads a couple of niftis but generates only axial slices amd then shows the slice level in a saggital view   <br />
Tutorial 3: Instead of generating ready plots it creates an image array to be manipulated or stored later. It works faster and better while the exported image is smaller in size but good quality (its results are saved in results folder!)  <br />
Tutorial 4: Same as tutorial 3 but with color gradients  and exporting colorbars<br/>

The toolbox uses (and includes) the NIFTI toolbox made by Jimmy Shen which has saved my life. 
No other files are needed in order to run the visualization tool but I need to cite Jimmy's work:
http://www.mathworks.com/matlabcentral/fileexchange/8797-tools-for-nifti-and-analyze-image

The main visualization functions are the:
viznii_image 

viznii 

viznii_levels 


Some other functions included:

slices_of_max_info: it finds the coordinates of the slices with the maximum information  <br />
overlap_niis: finds the overlapping regions of two images given a threshold <br />
mni2coords: transforms MNI coordiantes to matrix coordinates given a reference NIFTI file <br />
coords2mni: it does the opposite <br />

There might be files in the toolbox that are not used. And I am aware that the documentation and the code are not very detailed but I made this for my needs and then I thought I should share it. But you are very welcome to make comments, requests, questions or whatever. I will be glad to help.

