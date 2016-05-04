# final_project
This repository will contain the data, code, summaries and reports generated for our final project in completion of the Spring 2016 AM207 course--Stochastic Methods for Data Analysis, Inference and Optimization.

The iPython Notebooks listed in the head of this repository contain all the code used to develop and formalize the analysis used in our poster, video and report. We named them to reflect the piece of analysis and the function the provide to our project. You are welcome to peruse them at your will.

We utilize an online repository for the 2012 Hubway data, located at:

https://raw.githubusercontent.com/CS109Hubway/classp/master/data/hubway_stations.csv

https://raw.githubusercontent.com/CS109Hubway/classp/master/data/tripsthrough2012.csv

All data we generated such as timeseries are stored in data/

All videos and other images are stored in images/

Our screencast can be found at: https://youtu.be/mCAfvDxA3w8

Feel free to contact any of the repository contributors if you have questions.

-SD, JF, TK, AP

[//]: # (Overview of Methods and Analyses we’ll perform (with contributor highlighted to the right))

[//]: # ( **Exploratory Data Analysis** *(Taylor, ?)*)

[//]: # ( - Get a sense of the periodicity of the data, what stations are heavily used at which times. What are the most likely pick up and drop off zones? Can use www.hubwaydatachallenge.org www.bostonography.com/hubwaymap (among other works) to get a sense of what’s out there.)

[//]: # ( - Key output of this will be Station/System Usage Rates in terms of time series, histograms and maps (to be used for poster, paper and future time series analysis))

[//]: # ( **Simulated Annealing/Stochastic Sampling** )

[//]: # ( - Finding optimal location for extra service (helmet rental) based on ridership data *(Andrew, ?)*)
[//]: # ( - Use complete pooling, unpooling and partial pooling sampling methods in order to get a sense of whether the capacity of any one station can be predicted in relation to other stations in the system. *(Jonathan, Taylor, ?) *)

[//]: # ( **Time Series**)

[//]: # ( - Period matching, randomly select small subset of data (unknown to us, but discoverable), add noise to it and then try to figure out where it came from using something related to Gibbs sampling *(Jonathan, ?)*)

[//]: # ( - Given a time series snippet, can we predict how many users will pick-up/drop-off bikes from any given station or from the system at large. *(Andrew, ?)*)

[//]: # ( **Gaussian Processes**)

[//]: # ( - Using GPs to interpolate missing data *(Taylor, ?)*)

[//]: # ( - Similar to the yelp check-in problem, use GP interpolation to infer station capacity both in terms of pick-ups and drop-offs. *(Taylor, Jonathan)*)

[//]: # (	- Will leverage PyMC here.)
    
[//]: # ( *For those who aim to create videos out of .png files (run in command line)*)

[//]: # ( brew install ffmpeg)
[//]: # ( [navigate to the directory of your images])
[//]: # ( ffmpeg -framerate 1 -i figure%03d.png -c:v libx264 -r 4 -pix_fmt yuv420p out.mp4)
[//]: # ( [There is a lot of information and instructions at https://trac.ffmpeg.org/wiki/Create%20a%20video%20slideshow%20from%20images])




