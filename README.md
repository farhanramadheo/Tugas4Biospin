 #HIGH PASS FILTER
 
 contains the source code high pass filter at 586 Hz until 863 Hz
     
  A). 
     
![](https://latex.codecogs.com/gif.latex?f%28t%29%20%3D%20%5Cfrac%7B%5Calpha0%7D%7B2%7D%20&plus;%20%5Csum_%7Bk%3D1%7D%5E%7B%5Cinfty%20%7D%20%28ak%5Ccos%282%5Cpi%20kt%20%29&plus;bk%20%5Csin%20%282%5Cpi%20k%20t%29%29) 

Equation of fourier tranform is

![](https://latex.codecogs.com/gif.latex?X%28%5Comega%20%29%20%3D%20%5Cint_%7B-%5Cinfty%20%7D%5E%7B%5Cinfty%20%7D%20x%28t%29%20e%5E%7B-j%5Comega%20t%7D%20dt)
 
 Equation of  invers fourier tranform is
 
 
 ![](https://latex.codecogs.com/gif.latex?x%28t%29%20%3D%20%5Cfrac%7B1%7D%7B2%5Cpi%20%7D%5Cint_%7B-%5Cinfty%20%7D%5E%7B%5Cinfty%20%7D%20X%28%5Comega%20%29e%5E%7Bj%5Comega%20t%7D%20d%5Comega)
 
 
   Fourier Transform decomposes an image into its real and imaginary components which is a representation of the image in the frequency domain. If the input signal is an image then the number of frequencies in the frequency domain is equal to the number of pixels in the image or spatial domain. The inverse transform re-transforms the frequencies to the image in the spatial domain. 


B) Analyze the signal


![sinyal X](https://user-images.githubusercontent.com/81222423/112156928-4a16a080-8c19-11eb-8f97-68099281b5da.JPG)![]( https://latex.codecogs.com/gif.latex?%7B%5Ccolor%7BMagenta%7D%20signal%20x%7D)
![sinyal Y](https://user-images.githubusercontent.com/81222423/112156945-4edb5480-8c19-11eb-837b-119228223580.JPG) ![](https://latex.codecogs.com/gif.latex?%7B%5Ccolor%7BTeal%7D%20signal%20y%7D)
![sinyal Z](https://user-images.githubusercontent.com/81222423/112156949-4f73eb00-8c19-11eb-8ffb-92367bb23249.JPG) ![](https://latex.codecogs.com/gif.latex?%7B%5Ccolor%7BBlue%7D%20signal%20y%7D)

   
   
   Based on the picture above, we get an X signal and  Y signal. Where signal y is denser than signal X. if we combine the two signals, the z signal is formed which has an irregular shape.



C) Analyze the audio audio Z
   
   
   From the results of the experiments we have done, we found that the sound produced is a bit harsh and noisy. this happens because the shape of the signal is irregular so that there is noise.
