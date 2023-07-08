# 3-July-2023
	Literature review on the asbestos properties for estimation of cracks on ROOF tops in US using SAR data
	Literature review on the Concearte crack detection using SAR data.
[Doc](Documents/PaperReviewForSAR_Rohit.docx)


# 4-July-2023
	1. Reading previous documentation on galax-blue of the water quality analysis, farm status identification, Lake health monitoring
	2. Discussion with sumesh regarding galax-blue briefly 
	3. Discussion on field data, images and ground truth
	
##  Can be done:
	1. Need of atmospheric correction in sen 2 data
	2. Can use different satellite data 
	3. GT analysis with justification and its effects on input and commodity 
	4. water + satellite data interaction
	5. Very less data points
	6. Another issue of coincidence(NEED TO BE RESOLVED SO ALL DATA  POINTS CAN BE USED)
	7. identification of Nature of problems
 
# 5-July-2023
  	1. OKR meeting
  	2. EDA on available data on Galax-blue 
	3. Literature review on the yesterdays (Can be done) using SAR data.
[Doc](Documents/EDAonGaBlue.docx)  [Notebook](Documents/trialANDerror.ipynb)

<!-- ## Nature of problem: -->
<!-- Less data + complex data +  -->
	4. atmospheric correction for Sentinel-2 data is affecting mainly  490 to 740 drastically.  If we are using those bands then we have to do atm correction for sure otherwise we can check affect on other bands and use accordingly.
[Paper](Documents/Sen2indepthATMCorrection.pdf)

# 6-July-2023
	1. trying to focus on how to interpolate the satellite data for 1 or 2 days - P.S but it does work well because of aquaculture dynamics 
	2. Will this paper work with sentinel 2A  and what will be accuracy, its LR(DOC)
	3. while doing work start thinking from business rather than scientist perspective.
	4. meeting with founders and gx-blue to discuss overall progress of gx-blue
	5. Specific Model design
    6. Cluster of ponds(GT) with similar property (so multiple model)
    7. GEE earth scripts(for satellite data) needs to be automate with ML scripts
    8. geojson.io>API> template csv (cord)+ geo-json(cord) python>API> master csv (with cord info) > GEE - SAR(centroid band value) data > final csv >API> SVR model
[Paper](https://www.notion.so/galaxeye-space/Algal-Bloom-4a2e664b457d46c287b0030f9abf845f)
[Doc](Documents/Chl-aLR.docx)

# 7-July-2023
	1. Literature review on the CHL-a algae estimation 
	2. First OKR meeting
[Doc](Documents/Chl-aLR.docx)

# 8-July-2023
	1. Literature review on the CHL-a algae estimation completed with 2 approach
	2. atmospheric correction on sen 2 data
[Doc](Documents/Chl-aLR.docx)