# Key Ideas for wavelets

## Part A.Fourier Transforms and their problems with time

* Fourier transforms are nice when it comes to get frequencies but we are missing the time information, that is, we don't know when they've occurred.

* For stationary signals that's is ok since they are periodical, but when it comes to non-stationary signals, it's a problem.

* We can partly mitigate it by using a windowed fourier transform, that is, taking different slices of the original signal.

* A windowed fourier transform can be replaced by a Gaussian filter that takes in two parameters the position and the intensity (sharpness). That is called the Gabor transform.

* However, this carries the problem stated by uncertainty priciple (at least, an interpretation of it), that is:

> It's not possible to simultaneously sharply localize a signal in both the time domain and frequency domain

## Part B. Improving Fourier transforms with wavelets

* Wavelet can refer to: 
    * Small wave that vibrates for a while and then stops.
    * The wavelet function, including a wavelet, its scale and the shift (position).
    * The wavelet transform: the collection of several wavelet functions at different scales and positions. Used to decompose a signal (or image) in different resolutions.

* There are (in this doc) four wavelet transforms, say:
    1. Continous wavelet transform (CWT) (progressive)
    2. Discrete wavelet transform (DWT)
    3. Undecimated wavelet transform (UWT)
    4. Starlet transform

***
*Asorted stuff from guide to wavelets*
* The multires analysis is the sum of several wavelets. 
* These wavelets are genrated from the mother wavelet by scaling and translation.


***
## Self unsolved questions
* what does exactly represent the area under the curve of a wavelet (which we want to be 0, see wavelets section intro)?
* How does an image become a signal?
