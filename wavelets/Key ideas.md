# Key Ideas for wavelets

## A.Fourier Transforms and their problems with time

* Fourier transforms are nice when it comes to get frequencies but we are missing the time information, that is, we don't know when they've occurred.

* For stationary signals that's is ok since they are periodical, but when it comes to non-stationary signals, it's a problem.

* We can partly mitigate it by using a windowed fourier transform, that is, taking different slices of the original signal.

* A windowed fourier transform can be replaced by a Gaussian filter that takes in two parameters the position and the intensity (sharpness). That is called the Gabor transform.

* However, this carries the problem stated by uncertainty priciple (at least, an interpretation of it), that is:

> It's not possible to simultaneously sharply localize a signal in both the time domain and frequency domain

## B.Wavelet (Transform)

* Improving Gabor Method.

***
## Self unsolved questions
* How does an image become a signal?