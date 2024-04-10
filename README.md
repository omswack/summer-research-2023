# Climate Dynamics @ USC 🌍
+ Over the summer of 2023, I interned as a research assistant under the Climate Dynamics Lab at USC. My primary task was to produce a model that analyzes the net warming trends at Earth's atmosphere (Troposphere) from the last few thousand years through the 22nd century. All of the data I used is from [CMIP6](https://www.carbonbrief.org/cmip6-the-next-generation-of-climate-models-explained/).

+ Notebooks shared include comments and explanations to serve as a step-by-step tutorial. Not all of the work / final results are shared as these contributions are apart of an ongoing research paper. To learn more about the results, please contact my email: swack@usc.edu. For information about the pens package ('utilities for comparing paleoclimate reconstruction ensembles'), check out this link [here](https://fzhu2e.github.io/pens/)

### hist_picontrol_anomalies
+ In this notebook, I get accquainted with the relevant packages I need to use to normalize the data (Pens, Xarray, NumPy, etc.)
  
+ For both historical and picontrol simulation data, I **[ 1 ]** use zero normalizations to return the anomalies and **[ 2 ]** stack them into KDEs

### trends_continued
+ Here, I apply the processes in the other notebook to all of the other types of simulations
  
  +  I also create helper functions to load and normalize all of the data from Google Cloud

+ Visualize all of the data via Matplotlib
