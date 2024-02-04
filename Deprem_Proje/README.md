# PROJECT OBJECTIVES

- Examining the geographical distribution of earthquakes, in which regions earthquakes occur more frequently.
- Earthquake distributions over time.
- Understanding the relationships between earthquake and depth, earthquake magnitude types.

# DATA SET CLEANING

- Examine null values and determine an appropriate strategy (filling, subtracting, guessing).
- Remove columns with unnecessary or missing information.
- Check data types and update accordingly. (Date column)

# EXPLORATORY DATA ANALYSIS AND VISUALIZATION

- Visualize relationships, distributions and patterns in the data set.
- Gain a deeper understanding of the data set using statistical analysis and graphs.
- Identify anomalies or interesting patterns.

# CREATE PREDICTION MODELS

- Decide which model you will use (regression, classification, clustering, etc.)
- Convert the data set into a format suitable for model training.
- Create and train a starter model.
- Measure the performance of the model.
- Evaluate the model's successes and failures.

# COMMENT AND REPORT THE RESULTS

- Interpret and make sense of the results of the project.
- Reason for the success or failure of the model.
- Report results clearly and understandably.


# DATA SET REVIEW AND UNDERSTANDING
                                                                                                         
- No: Number given to earthquakes
- Earthquake Code: Special code given to earthquakes
- Date of occurrence: Date of occurrence in day, month and year.
- Time of occurrence: The time the earthquake occurred
- Latitude: Latitude information
- Longitude: Longitude information
- Der(km): Earthquake depth
- xM: It refers to the moment magnitude of the earthquake.
- MD (Time-dependent magnitude): It is measured how long the earthquake creates a vibration on the seismometer and is scaled with the distance from the earthquake center. This method is used for small (M<5.0) and close (Distance<300 km) earthquakes.
- ML (Local) Magnitude: This method is used for relatively small (magnitude less than 6.0) and close (less than 700 km distance) earthquakes.
- Mw: This type of magnitude is the most reliable compared to the others. In the scientific world, it is thought that if the moment magnitude for an earthquake can be calculated, there is no need for other magnitude types. In practice, Moment Magnitude can only be calculated for earthquakes above a certain magnitude (M>4.0).
- Ms (Surface Wave Magnitude): This method was developed to measure large earthquakes (M>6.0) for which the first two methods were insufficient. Unlike other methods, the reliability of this method increases even more in long distance measurements.
- Mb (Body Wave Magnitude): This method is similar to the Surface Wave method, the only difference is that waves propagating at depth are used instead of waves propagating from the surface.
- Type: "Ke" code indicates that the earthquake is of tectonic origin and occurs along a fault line. The "Se" code indicates that the earthquake has a strike-slip fault type.
- Location: The location where the earthquake occurred
