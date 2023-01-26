# SEA

Superposed Epoch Analysis (SEA) is a statistical method used to study the temporal variability of a signal by averaging multiple instances of the signal that occur around a certain event or condition. The event or condition is defined by the user, and the signal is averaged over a user-specified time window around each instance of the event or condition. The resulting average signal is called the "superposed epoch" and can reveal patterns or trends that would be difficult to detect by simply looking at the raw signal.

Here we provide a function that performs SEA using python.

The function takes as an input the dataframe containing the signal, the conditions used to identify the event or condition, the time window around the event or condition, and the signal to be analyzed. 

The function  first filters the dataframe to only include instances of the event or condition, then it creates a new dataframe with the signal values averaged over the specified time window around each instance of the event or condition. The function outputs the resulting superposed epoch signal as well as the time values corresponding to the center of each time window.


 # Download the package
``` bash
git clone https://github.com/nsioulas/SEA/
```

# Usage

Examples can be found in ```example.ipynb```

# Contact
If you have any questions, please don't hesitate to reach out to nsioulas@g.ucla.edu.

# Citation

If you use this work, please cite:

```
@software{nikos_sioulas_2023_7572468,
  author       = {Nikos Sioulas},
  title        = {MHDTurbPy},
  month        = jan,
  year         = 2023,
  publisher    = {Zenodo},
  version      = {0.1.0},
  doi          = {10.5281/zenodo.7572468},
  url          = {https://doi.org/10.5281/zenodo.7572468}
}
```

