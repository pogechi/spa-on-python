# Read SPA on python

## Usage:

Use PySimpleGUI to select as many .spa files as you wish.

The function extracts count and wavenumber data to generate a Pandas DataFrame.

Finally, the spectra are plotted on top of each other using Seaborn. For multiple plots in the same image, an optional plot is provided at the end of the script.

This Python function is based on [lerkoah/spa-on-python](https://github.com/lerkoah/spa-on-python), which in turn is based on [LoadSpectra](https://la.mathworks.com/matlabcentral/fileexchange/57904-loadspectra) from matlab. The original file allows working with FTIR spectra.

## Example

Execute script. You will be prompted to:

![PySimpleGUI](https://user-images.githubusercontent.com/84137850/119478250-f24b0180-bd4f-11eb-8b08-17c38b479a92.PNG)

Select your .spa file(s) and click "Submit".

Your spectrum/spectra will be plotted. Below is a sample image using polystyrene:

![Polystyrene](https://user-images.githubusercontent.com/84137850/119478100-d0517f00-bd4f-11eb-88fc-8bc895a70fce.png)


# License
GNU General Public License v3.0 or later

See [COPYING](COPYING) to see the full text.
