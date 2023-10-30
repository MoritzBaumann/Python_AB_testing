# Python_AB_testing
In this project, I use chi-square tests and pairwise post-hoc comparisons in Python to A/B test the re-design of a button of the Montana State University Library website.

It is a learning project, in which I practise the basics of carrying out statistical A/B tests.

## Content
- `AB_testing_montana_library.ipynb` -> working notebook
- `chisq_test_wrapper.py` -> helping script for post-hoc comparisons, see credits for further info

### Data
The data from the A/B testing experiment can be downloaded from here:

https://learn.wbscodingschool.com/wp-content/uploads/2023/03/MSU-ABTest-CrazyEgg.zip

### Credits
The `chisq_test_wrapper.py` is an easy wrapper for conducting chi-square post-hoc comparisons and was downloaded from 
[this repository](https://github.com/neuhofmo/chisq_test_wrapper/blob/master/README.md).
A big thank you to **Moran Neuhof** (neuhofmo) for providing this awesome piece of stats source.

## Context
This A/B test was carried out in the context of a 4.5 month-long Data Science bootcamp with WBS Coding School. 
Many thanks to WBS Coding School for the guidance and learning materials.
