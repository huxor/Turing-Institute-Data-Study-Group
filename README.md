# Turing-Institute-Data-Study-Group
Code and documents in support of Data Study Group Application, July 2019

They include my MSc thesis, which analysed a massive database of US patent data (their classifications, dates, forward and backward citations to other patents) to build a recommender system. This looked at the measure of innovativeness of patents (using forward citations as a proxy), as a funxtion of the cognitive distance between patent classifications (i.e. which ideas and technologies they embody).
Much of the python code used to generate the results in the thesis are to be found in *heatmaps_PV_data.ipynb.*

The remaining files are python notebooks related to my current work on the LeDeR programme (http://www.bristol.ac.uk/sps/leder/). This study collects reviews of the deaths of people with learning disabilities. These reviews are manually coded by a team of full-time expert coders using NVivo. 

*create_master_nvivo_turing_institute.ipynb* takes these manual coding and converts them into a pandas dataFrame.

*generate_spss_file_nvivo_turing_institute.ipynb* take sthis dataFrame and generates a file that can be used by the popular data analysis tool SPSS

*leder_text_classif_turing_institute.ipynb* are some initial experiments using the free-text to label codings as a training set for future automated coding of new reviews.

PLEASE NOTE:
Sometimes the well-known GitHub feature occurs which prevents the display of Notebooks for some time. If this occurs
copy/paste the GitHub URLs linked above into:
https://nbviewer.jupyter.org/

