Utilized Pupil Player (from Pupil Labs) to convert raw video footage captured using eye-tracking glasses into sequential image frames.

Performed gaze data extraction for 22 individual pedestrians by processing Pupil Labs' gaze and scene data streams.

Developed a custom pipeline in MATLAB to:

Parse and analyze gaze points.

Map gaze positions to key visual categories within the scene such as:

4-wheelers (cars, vans)

2-wheelers (bikes, scooters)

Heavy vehicles (buses, trucks)

Urban infrastructure (e.g., poles, sidewalks, signboards)

Miscellaneous surroundings (trees, sky, ground, etc.)

Implemented categorization logic to classify each gaze instance based on the object of attention and correlated this with the level of time pressure the pedestrian was under (e.g., high, moderate, or low urgency to cross).

Designed a structured Excel-based dataset to store and organize the categorized gaze data, enabling further behavioral and statistical analysis.

The work provided insights into visual attention distribution among pedestrians in real-world urban scenarios, supporting future research in traffic safety and human behavior modeling.# -Pedestrian-Gaze-Data-Extraction-Across-Road-Types-and-Time-Constraints
