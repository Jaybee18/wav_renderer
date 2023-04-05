Small, hacky and unoptimized renderer for .wav files

### Requirements
- sympy -> ```pip install sympy```
- numpy -> ```pip install numpy```
- matplotlib -> ```pip install matplotlib```
- scipy -> ```pip install scipy```

### Usage:
- define polygons in "generate_wav.ipynb" and run the file to render to a "data" file
- then run either
  - "display_wav.ipynb" to display the "data" file with matplotlib.pyplot
  - "export_wav.ipynb" to export the data in the generated "data" file to a .wav file

### Note
currently not supporting lines perpendicular to the x-axis, so use an offset of about 0.0001 in those cases

### Example:

![grafik](https://user-images.githubusercontent.com/64578396/230216292-7a7fe641-fbbd-448a-9ca1-ca144b772eb8.png)

View with one of the following tools:
- https://twistedwave.com/online
- https://planetcalc.com/8627/
