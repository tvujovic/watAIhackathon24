### Overview
Quick summary, nothing too in depth

### Model
Describe the model (inputs and outputs)
Describe the technologies used

### Dataset
Describe the dataset at a high level, what form is the data in, etc. how much there is, all of that

Fire Geometry - Includes ignition information
Fire Weather Indices - Including fire weather index, and integrated indicies such inclduing duff moisture code, Drought code?
Topographical factors - Elevation and slope
Weather factors - None weather factors like max temperature, wind, etc.

### Training Parameters
Talk about the parameters we used here, add short descriptions and links for more info

### Optional: Additional Parameters
Talk about the other parameters here instead if you want to split it up

### Hackathon
Hackathon background information goes here

### Wildfire Hackathon Project

*Event Hosted by the University of Waterloo's Data & Artificial Intellegence Institute (Waterloo.ai) in coordination with Wat.ai and UWDSC (University of Waterloo Data Science Club) and in partnership with MAG Aerospace*

Hackathon Preliminaries:
- Event details, as well as a complete list dataset can be found on the [hackathon's kaggle page](https://www.kaggle.com/competitions/wildfire-hackathon-kaggle/overview)
- Participant teams were provided dataset covering 8 fires, occurring in BC, from 2018. The fires all overlapped in duration and burned in the same geographic region.
- The data is mainly provided as GeoTIFF files (which can be accessed via the rasterio python library).
- 7 of these fires were used to train the model. Thus, teams were given complete data for all 7 fires, including growth information in the region, as well as, attributes for the area burned (ie. weather, vegetation/fuel indices, etc.)
- The test dataset contains the last fire. Teams were tasked with predicting the future growth for this fire.
- The test fire, dubbed ‘fire 2214’ lasted for 30 Julian days (213 to 243). Teams were provided data for the first 10 days of burning, thus predictions would be for the latter 20 days of the test fire.


