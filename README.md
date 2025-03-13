## Wildfire Hackathon Project
### Overview
Event details, as well as a complete list dataset can be found on the [hackathon's kaggle page](https://www.kaggle.com/competitions/wildfire-hackathon-kaggle/overview)

*Event Hosted by the University of Waterloo's Data & Artificial Intelligence Institute (Waterloo.ai) in coordination with Wat.ai and UWDSC (University of Waterloo Data Science Club) and in partnership with MAG Aerospace*

### Model
Though there was significant iterations during the hackathon, the our best model involved a CNN x LSTM approach to effectively capture spatial and temporal patterns respectively.

-Describe the model (inputs and outputs)
-Describe the technologies used

### Dataset
Describe the dataset at a high level, what form is the data in, etc. how much there is, all of that.

- Fire Geometry - Including ignition information.
- Fire Weather Indices - 6 Indices as defined in the Canadian Wildfire Danger Rating System (FFMC, DMC, DC, ISI, BUI, FWI).
- Topographical factors - Elevation and slope.
- Vegetation/fuel - Fuel type, in reference to the (Canadian) Fire Behavior Prediction (FBP) system.
- Weather factors - Weather factors include max temperature, accumulated precipitation, and a wind vector. 

The data parameters described above are provided in the form of GeoTiff files. 
For each fire in the training set, one file informs one day in a polygonal 'image'. Each parameter, as described above,
provided environmental context. The full training set was composed of 7 fires, each one providing growth information
from its ignition to its extinguishment. The test fire, dubbed ‘fire 2214’ lasted for 30 Julian days (213 to 243). Teams were provided data for the first 10 days of burning, thus predictions would be for the latter 20 days of the test fire.

### Hackathon
Event details, as well as a complete list dataset can be found on the [hackathon's kaggle page](https://www.kaggle.com/competitions/wildfire-hackathon-kaggle/overview)

*Event Hosted by the University of Waterloo's Data & Artificial Intelligence Institute (Waterloo.ai) in coordination with Wat.ai and UWDSC (University of Waterloo Data Science Club) and in partnership with MAG Aerospace*
