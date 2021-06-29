# Hyperspectral-Image-Denoising-Toolbox-V2
This toolbox contains the following HSI denoising methods: 3D Wavelets,FORPDN, and HyRes (all can be found in
[Hyperspectral Image Denoising Matlab Toolbox](https://github.com/BehnoodRasti/Hyperspectral-Image-Denoising-Matlab-Toolbox)),
[SSTV](https://www.mathworks.com/matlabcentral/fileexchange/49145-mixed-noise-reduction),
[NAIRLMA](https://sites.google.com/site/rshewei/home),
[FastHyDe](https://github.com/LinaZhuang/FastHyDe_FastHyIn),
[DIP](https://github.com/DmitryUlyanov/deep-image-prior). For DIP, you need to download the original toolbox and copy the python file (DN4Rev_Real.py) into the master folder (change the path, line 48 of DN4Rev_Real.py, to the mat file of Indian Pine) and run. Addtionally, you need to install the dependencies (see [readme](https://github.com/DmitryUlyanov/deep-image-prior)) 

To reproduce the resutls below you can find the Indian Pines dataset in [Hyperspectral Image Denoising Matlab Toolbox](https://www.researchgate.net/publication/328027880_Hyperspectral_Image_Denoising_Matlab_Toolbox) and use the matlab and python demos provided to run the codes

![image](https://user-images.githubusercontent.com/61419984/123767477-c6c7b380-d8c7-11eb-9bd0-1fa3b746351a.png)

