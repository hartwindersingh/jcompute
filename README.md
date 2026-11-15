# jCompute — Scientific Computing Studio

A browser-based workspace for exploring mathematical expressions, equations, graphs and frequency-domain analysis.

## What is included

- Scientific calculator with common mathematical functions
- Equation-solving tools
- Function plotting and graph exploration
- Fourier analysis with a function-to-graph-to-FFT workflow
- Random number and numerical utilities
- Saved programs and a shared mathematical workspace
- Built-in help and function reference

## Run locally

1. Download or clone this repository.
2. Open the HTML application in a modern browser.
3. Keep an internet connection available so the external mathematics and plotting libraries can load.

No server-side installation is required for the standalone browser build.

## Function-to-Graph-to-FFT

1. Open **Graphing** and enter a function of `x`.
2. Choose the interval to sample.
3. Plot the function.
4. Select **Send function to FFT**.
5. Review the sampling rate, transform size and window settings in the Fourier lab.
6. Inspect the spectrum and frequency peaks.

The graph is converted into numerical samples before the FFT is calculated. The sampling interval and rate affect the frequency resolution and the range of frequencies that can be represented.

## Dependencies

The standalone browser build loads its mathematics and visualisation libraries from their published CDN distributions. An internet connection is therefore needed when opening the application unless those libraries are made available locally.

## Project status

This is an actively developed project. The browser interface and individual tools should be tested in the target browsers before being relied on for research or production calculations. Numerical results should be checked against an independent reference for high-stakes work.

## Developer

Hartwinder Singh

## License

This repository includes a GNU General Public License v3.0 license. See [LICENSE](LICENSE).
