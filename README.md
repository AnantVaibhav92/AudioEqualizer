# SoundEqualizer
This code is aimed at creating a basic 8 band sound equalizer in pythion by utilizing the techniques of **Digital Signal processing**.

Here we use below techniques:

**1) FFT: Fast Fourier Transform**
  To generte a frequency domain transforation of the time domain sound. This way we get to know that how the sound is sampled in frequency spectrum. Likewise we can modify few *bins* in the FFT, by multiplying them with a factor of our choice to increse or decrese the impact of that frequency bin on the final sound.

**2) IFFT: Inverse Fast Fourier Transform**
  To generate the sound back from the modified frequency spectrum.
  
We will also view the frquency domain in orde to visualize the phenomina of equalization.
The sound is displayed as a widget in the notebook itself.
  
  
**Code File:** Equalizer.ipynb

**Data folder:** \Audio

**Dependecies:**
numpy

scipy

matplotlib.pyplot

librosa

IPython.display
