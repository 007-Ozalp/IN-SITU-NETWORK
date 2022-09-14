

### TEMPORAL STABILITY FOR IN-SITU NETWORK STATIONS

Input contains informations from 11 in-situ stations by Date, Time, Station Code and Soil Moisture.

Each date contains 5 time cycle, therefore the "Hourly Mean" frequency time is calculated.

The code section includes:

1. Input Data Elaboration
    * Row Selection by station
    * Group by Frequency-Time
    * Filter for 0 < SM values < 0.8
2. Data Analysis
    * TS Plot
    * Mean Relative Difference
    * STD for bias
    * RMSE
