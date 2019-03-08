# Visualization-using-matplotlib

Visualizing the json files unzipped via bash script.
Each of the json files extracted is a single match that was played. 
The deserialized json files using Python contains an events field. This field contains a list of events that occurred.
There are several event types (round start, round end, etc) but I am only interested right now in spawn and death.
Produced for each match (each json file) a "spawn-death" png image that shows the spawns as BLUE dots and the deaths as RED dots.
A sample image is attached in the repository.


