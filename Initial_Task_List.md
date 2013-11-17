https://github.com/stat157/presenters/issues/2

TASKS:

(1) Curate Data from SCEC website {Taken by: Group Smile}

- check integrity of data (watch for duplicates, NA’s, etc.)
- store as a CSV
- return as a data frame
- provide usage sample to analyzers and visualizers
- link to github: [ ]
- consider where to reproducibly store the data

(2) Researching and Negotiating on Data Formats
- Curator: Construct interface for Curators and Visualizers to to utilize
- what is the most common one
- JSON versus CSV versus XML
- Data Frame versus 2-D Array versus List of Dictionaries
- Analyzers/Visualizers: research sufficient/functional data formats in terms of ~~
~~ ease-of-use and ability to produce visuals
- Presenters: decide on how to present the data
- iPython notebook, HTML, etc.
- what are the pro’s and con’s of each method
- which format could be used to make the graph dynamic?

(3) Explore additional data sources
- Curator: Find additional sources
- Add code integrate the new data, bolstering our data source
- Do everything we did for the SCEC source
- Integrity check
- format validation
- The new data must be plug-and-play with what Visualizers/Analyzers code

(4) ETAS Model: translating from MATLAB
- Working with MATLAB

recruit people who are familiar with MATLAB syntax - explore D-Lab resources and communicate with on-campus representatives to further interpret MATLAB code
understand what the MATLAB code is executing; translate to Python
Understanding the ETAS model
which parameters to use
which columns to use
interpretation of the models
output ETAS model in Python
(5) ETAS Model: utilizing the ETAS R Package
- research the ETAS R Package
- Understanding the ETAS model
- which parameters to use
- which columns to use
- interpretation of the models
- output ETAS model in R

(6) Alarm Model
- talk to Professor Stark/conduct research to further understand the alarm model
- Understanding the Alarm model
- which parameters to use
- which columns to use
- interpretation of the models
- decide whether to use R or Python
- communicate with Visualizers and Group 4-5
- extract relevant data from data frame to send to visualizers

(7) Visualize raw earthquake data (Time Series)
- create graph of the RAW earthquake data
- don’t have ETAS/Stark model yet
- CDF for earthquake occurences
- refine code for plotting earthquakes for particular regions
- make it dynamic to location

(8) Create Visual for ETAS and Alarm Data in Report
- understand the parameters of the model
- what are our axes
- PDF versus CDF
- create graph output for the coordinate data we receive from the analyzers
- output the two graphs on the same coordinate plane
- create a residual plot to compare the two models
- is there a correlation between the two models? Is the residual plot white
noise?
- how do we determine the fit between the lines in the plot?
