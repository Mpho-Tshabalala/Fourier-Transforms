<h1>Fourier Transforms</h1>

<h2>Description</h2>
For this section of the practical you will find the Signals and Systems textbook and hand-
out Sampled Signals, the DTFT and the DFT useful. In an experimental situation we of-
ten measure a time-series which we want to Fourier transform to obtain a spectrum, or a

frequency-dependent quantity which we wish to inverse Fourier transform in order to retrieve
a time-dependent quantity. This requires us to perform a Discrete Fourier Transform (DFT),
which is usually calculated using the Fast Fourier Transform (FFT) algorithm (Brigham). The
DFT (and therefore the FFT) work on a finite number N data samples, and return the same
number of transform samples. The FFT algorithm places restrictions on the possible values of
N, and the FFT algorithm used by the Excel FFT tool restricts us to N = 2n, i.e. N must be
an integer power of 2 (e.g. 64, 512, 2048).<br />


<h2>Languages and Utilities Used</h2>

- <b>Excel</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
