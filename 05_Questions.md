## **Questions for better understanding GEDI Data**
### This file contains all questions from the notebook.

Solve these questions for yourself in preparation for the exam 😉

#### 3. Visualise a GEDI orbit

- How does the spatial distribution of GEDI shots relate to the ISS orbit path? Why do they appear in a narrow strip?

#### 4. Work with GEDI L2B data
   - The two plots have different elevation ranges. What does this tell us about the two shots and what would change if we use the same y-axis for both graphs?
   - How does the PAVD vary with elevation, and what does its distribution reveal about the vertical structure and continuity (continuous or patchy) of the canopy?
   - How do these profiles relate to forest structure? Can you infer anything about canopy height or density?
   - If you were collecting more data, what other variables would you want to include for a better understanding of PAVD?

**Extra**: Using what you've learned, describe what you would expect to see in a PAVD profile for:
   - A dense tropical rainforest
   - An open savanna
   - A recently logged forest

#### 5. Work with GEDI L2B Beam Transects
- Do you notice any patterns in the canopy height across the transect?  
- What could cause the sharp peaks and valleys observed in the graph, and conversely, are there sections where canopy height appears more consistent? What might these different patterns indicate about the underlying terrain or vegetation?
- The plot appears "messy" with scattered points. What might be causing this?  
- What kinds of errors or uncertainties might be present in GEDI measurements? How can filtering (e.g., using the quality flag) help?  
- If you plotted a different GEDI beam, would you expect to see similar patterns, or would they be different? Why?  
- If you had access to ground-based LiDAR data, how could you validate the accuracy of these canopy height measurements? 
**Extrat** Same as earlier, what you would expect to see in a transect for different vegetation types?

#### 5.2 Plot of Beam Transects
- How does the **Tandem-X DEM** compare to the **GEDI-derived elevation**? What could explain any differences?  
- What does the **Canopy Top Elevation** represent, and how is it different from the other two variables?  
- Where in the transect do you see the highest canopy elevations? What could explain these peaks?  
- Are there sections where canopy height is consistently low or missing? What could this indicate about the landscape?  
- Looking at the x-axis, do you see any changes in terrain? Can you hypothesize what type of environment this transect might pass through (e.g., dense forest, open land, mountains)?  
- The plot is "messy" - what do you think causes this?  
- What role might terrain slope, dense vegetation, or surface water play in affecting these elevation measurements?  
- How might cloud cover or atmospheric conditions impact GEDI’s elevation and canopy height estimates?
- If you analyzed a different GEDI beam, how might this graph look different?  
- How do you expect elevation and canopy height patterns to change in a tropical rainforest compared to an open woodland?  
- If you were to analyze multiple transects, what trends would you look for to study forest structure on a larger scale?  

#### 6. Plot Profile Transects
- What do the different lines and color intensities represent in this plot?
- How does setting the same y-axis for both plots improve the comparison between the two transects?
- What are the key differences between the ground elevation and canopy top elevation in the left and right plots, where is this difference the largest, and what does it reveal about the vegetation structure along the transect?
- How does the topography influence canopy height? Do you see patterns where forested areas follow terrain contours?
- How does the distribution of PAVD align with canopy height and terrain changes?
- In which areas do you see more variation in PAVD, and how does this relate to different forest types?
- What landscape or ecological factors might explain the differences observed between these two transects?
- How could this type of visualization be used for forest monitoring and conservation planning, and how might changes in these plots over time help detect forest degradation, regrowth, or land-use change?


#### 7. Spatial visualisation
- Do you notice any correlations between canopy height and elevation? What landscapes show the highest canopy heights?
- What variations in Plant Area Index (PAI) do you see along the transect? How might this relate to forest density?
- Are there regions where canopy height is low, but PAI is high? What could explain this?
- How could these maps help in identifying areas of deforestation or forest degradation?
- How could this data be integrated into forest conservation or carbon storage assessments?
- What are some potential errors or uncertainties in the GEDI data? How might atmospheric conditions or terrain features affect accuracy?
- If you had access to higher-resolution airborne LiDAR, how might it improve upon GEDI’s spatial coverage and detail?
- How can the QPRP plots be integrated with the GEDI data later on? For example, how field plots can be used to calibrate GEDI biomass models, or as validation data for wall-to-wall GEDI-maps (by integration with Sentinel-1/2/ Landsat/...)?
