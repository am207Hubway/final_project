# final_project
This repository will contain the data, code, summaries and reports generated for our final project in completion of the Spring 2016 AM207 course--Stochastic Methods for Data Analysis, Inference and Optimization.

Overview of Methods and Analyses we’ll perform (with contributor highlighted to the right)

**Exploratory Data Analysis** *(Taylor, ?)*

- Get a sense of the periodicity of the data, what stations are heavily used at which times. What are the most likely pick up and drop off zones? Can use www.hubwaydatachallenge.org www.bostonography.com/hubwaymap (among other works) to get a sense of what’s out there.
- Key output of this will be Station/System Usage Rates in terms of time series, histograms and maps (to be used for poster, paper and future time series analysis)

**Simulated Annealing/Stochastic Sampling** 

- Finding optimal location for extra service (helmet rental) based on ridership data *(Andrew, ?)*
- Use complete pooling, unpooling and partial pooling sampling methods in order to get a sense of whether the capacity of any one station can be predicted in relation to other stations in the system. *(Jonathan, Taylor, ?) *

**Time Series**

- Period matching, randomly select small subset of data (unknown to us, but discoverable), add noise to it and then try to figure out where it came from using something related to Gibbs sampling *(Jonathan, ?)*
- Given a time series snippet, can we predict how many users will pick-up/drop-off bikes from any given station or from the system at large. *(Andrew, ?)*

**Gaussian Processes**
- Using GPs to interpolate missing data *(Taylor, ?)*
- Similar to the yelp check-in problem, use GP interpolation to infer station capacity both in terms of pick-ups and drop-offs. *(Taylor, Jonathan)*
	- Will leverage PyMC here.



