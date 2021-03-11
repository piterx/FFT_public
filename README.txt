This is an implementation of FFT using Radix2 Decimation in time algorithm as described in:
Oppenheimer A., Schaffer R. W. "Digital Signal Processing" 1975 Prentice Hall International

Although the input x is double it is treated as complex number by the algorithm and further optimisation can be made for real inputs
The algorithm works and was tested against FFT implementation in Numpy, but I give no guarantees.