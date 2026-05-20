# sampley: sample survey data

## Description
The ```sampley``` package serves to sample survey data (hence 'sampley': 'sample' + 'survey'). By 'survey data', we refer 
principally to systematic visual survey data, nevertheless, the ```sampley``` package may also be applicable to other 
kinds of survey data. By 'sample', we mean process those data to produce distinct samples that can then be input to a 
model.
<br><br>Data can be processed by one or more of three approaches referred to here as the grid, segment, and point approach.
<br>The **grid approach** consists of overlaying a grid, typically rectangular or hexagonal, onto the study area and 
allocating detections and, optionally, survey effort to the cells that they lie within. Additionally, data may be 
allocated to temporal periods. Each cell within a given period then serves as a sample.
<br>The **segment approach** involves taking sections of continuous, uniform survey effort and cutting them into segments
of standardised lengths. Each segment, with associated detections and other data, then serves as a sample.
<br>The **point approach** consists of using the detections, or a subset thereof, as presences and then sampling absences
from absence zones (i.e., areas that were surveyed but where the species was not detected).
<br><br>For more information, please consult the User Manual (available on the GitHub repo at: 
https://github.com/JSymeCT/sampley/blob/main/sampley%20-%20User%20Manual.pdf) 
or the associated paper (available at: https://doi.org/10.1111/2041-210x.70320)

## Installation
```pip install sampley```

## Import
For basic use of ```sampley```, run:
<br>```from sampley import *```

To access the underlying functions, run:
<br>```from sampley.functions import *```

## User Manual
A user manual containing more detailed information is available on GitHub at:
https://github.com/JSymeCT/sampley/blob/main/sampley%20-%20User%20Manual.pdf

## Example usage
Several exemplars illustrating how to use ```sampley``` are available on GitHub at: 
https://github.com/JSymeCT/sampley/tree/main/exemplars

See the _Introduction to sampley exemplars_ (```intro.ipynb```) for more information 
(https://github.com/JSymeCT/sampley/blob/main/exemplars/intro.ipynb)

## License
MIT

## Citation
To cite ```sampley```, please cite the following paper:
<br>Syme, J., Pendleton, D. E., Meyer-Gutbrod, E. L., Tupper, B., & Record, N. R. (2026).
sampley: A Python package for sampling visual survey data. 
Methods in Ecology and Evolution. https://doi.org/10.1111/2041-210x.70320

You can also cite the package directly with:
<br>Syme, J., Pendleton, D. E., Meyer-Gutbrod, E. L., Tupper, B., & Record, N. R. (2026). 
sampley: sample survey data (v0.0.16). https://doi.org/10.5281/zenodo.19616964

Thank you!
