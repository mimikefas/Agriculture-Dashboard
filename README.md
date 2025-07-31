Dashboard Link : https://app.powerbi.com/links/OEP14mKHo1?ctid=10836287-602e-42db-9c46-f4184a33234b&pbi_source=linkShare

## Project Overview
This Power BI project explores how different season soil irrigation combinations affect agricultural yield, water usage, fertilizer consumption, and crop distribution. The goal is to uncover insights that can guide more efficient and sustainable farming practices.

## Dataset Overview

The dataset is split by season — Kharif, Rabi and Zaid

## Feature	Description
Season type & soil type	Combination of seasonal planting and soil conditions
Total yield (tons)	Combined crop yield per condition
Total water used (liters)	Water applied under each condition
Farm area (hectares)	Total land area under cultivation
Fertilizer used	Both in tons and kilograms
Crop type	Primary crops cultivated in each scenario

## Key Questions Addressed
	•	Which soil and irrigation types deliver the highest yield per hectare?
	•	How does irrigation method affect water efficiency?
	•	Which crops are most resource-intensive vs efficient?
	•	Are there significant seasonal differences in yield vs input cost?

## Key Findings

## Kharif
Season type and soil type 	Total Yield(tons) 	Total Water_used	Total Farm_Area 	Total Fertilizer(tons)	Total Fertilizer(kg)	Crop_type
           						
Clay & Flood	                8.08		          88.98k	             145.32	           3.01	                   2.27	              Sugar cane
Sandy & Flood	                35.01	            85.21k	             370.79	           8.18	                    4.99	             Rice
Silty & Flood	                33.44	            75.54k	             306.03	           2.91                   	0.56	             Sugar cane
Clay & Rain-fed	22.51	39.36k	375.10	0.50	4.76	                                                                                Cotton
Peaty & Rain-fed	28.77	33.62k	305.15	5.39	2.15	                                                                              Sugar cane
Silty & Rain-fed	45.15	90.23k	292.25	4.08	0.76	                                                                              Tomato
Clay & Sprinkler	71.08	133.85k	575.17	4.10	1.15	                                                                              Barley
Loamy & Sprinkler	14.44	76.65k	329.40	8.14	2.21	                                                                              Cotton
Peaty & Sprinkler	18.85	37.47k	326.69	5.24	0.55	                                                                              Tomato
Sandy & Sprinkler	18.85	92.48k	58.85	3.61	3.32	                                                                                Barley

## Rabi
Season type and soil type	Total Yield(tons)	Total Water_used	Total Farm_Area	Total Fertilizer(tons)	Total Fertilizer(kg)	Crop_type
                          						
Clay & Drip	29.17	26.74k	377.05	5.95	0.91	Cotton
Clay & Flood	55.04	114.46k	443.09	15.35	6.58	Wheat(30.70), Carrot(24.34)
Loamy & Drip	12.92	92.75k	264.12	4.75	4.79	Tomato
Loamy & Flood	24.63	65.84k	162.28	5.85	2.42	Wheat
Loamy & Rain-fed	16.67	18.66k	128.23	4.91	0.77	Maize
Peaty & Drip	3.86	60.20k	389.37	0.57	4.93	Maize
Sandy & Drip	44.93	40.58k	360.06	1.83	2.37	Soybean
Sandy & Flood	11.38	71.95k	246.02	1.01	3.45	Rice
Sandy & Manual	24.77	40.61k	84.12	4.46	2.53	Soybean

## Zaid
Season type and soil type	Total Yield (tons)	Total Water_used	Total Farm_Area	Total Fertilizer (tons)	Total Pesticide (kg)	Crop_type

						
Clay & drip	72.75	113.18k	1.09k	19.59	4.36	Wheat(5.44), Rice(67.31)
Clay & flood	22.39	112.65k	356.64	15.83	4.27	Barley(11.86), Cotton(10.53)
Clay & sprinkler	69.57	127.42k	554.55	9.11	5.06	Tomato(43.28), Sugarcane(26.29)
Loamy & drip	64.60	135.52k	462.43	17.74	3.95	Barley(46.47), Potato(18.13)
Loamy & Manual	100.38	200.82k	886.27	11.42	8.71	Carrot(47.70), Cotton(12.530, Soybean(40.15)
Loamy & Rain-fed	30.50	93.41k	286.52	8.91	0.77	Potato
Loamy & Sprinkler	38.18	46.49k	12.50	6.42	2.25	Sugarcane
Sandy & drip	39.96	34.31k	460.93	1.09	1.31	Maize
Sandy & Flood	27.48	119.89k	139.01	3.54	3.35	Barley(16.03), Cotton(11.45)
Sandy& Rain-fed	46.19	12.01k	166.82	2.85	1.36	Cotton
Silty & Drip	34.45	43.61k	266.03	8.57	1.35	Soybean
Silty & flood	6.14	43.85k	75.64	6.69	3.54	Barley
Silty & Manual	36.90	23.21k	288.52	1.79	4.78	Wheat

Silty & Rain-fed
	34,08	45.40k	380.21	3.32	4.35	Tomato
Silty & Sprinkler	20.53	5.87k	77.39	9.34	3.00	Potato



## Summary of Insights

## Top-Performing Combinations by Yield
	•	Kharif:
	•	Clay & Sprinkler produced the highest yield (71.08 tons), mostly Barley, using ~133.85k liters of water.
	•	Silty & Rain-fed gave a strong return (45.15 tons) with relatively low water use (~90k liters) for Tomato.
	•	Rabi:
	•	Clay & Flood led with 55.04 tons of yield from Wheat and Carrot, but water usage was also high (114.46k liters).
	•	Sandy & Drip was a strong performer with 44.93 tons (mostly Soybean) and only 40.58k liters of water.

## Water Use & Irrigation Efficiency
	•	Drip irrigation in Rabi (especially Sandy & Drip) gave the best water efficiency, producing high yields with less than half the water used in flood methods.
	•	Flood irrigation, especially in Sandy and Clay soils, showed high water consumption with mixed efficiency outcomes.

## Fertilizer Use
	•	Loamy & Sprinkler (Kharif) used the most fertilizer (8.14 tons) but yielded only 14.44 tons, suggesting low input efficiency.
	•	Clay & Rain-fed (Kharif) and Sandy & Drip (Rabi) delivered solid yields with relatively minimal fertilizer usage.

## Crop Observations
	•	Sugar cane and Rice dominate in flood irrigated systems with higher water and fertilizer requirements.
	•	Tomato, Soybean, and Maize perform well across multiple systems, offering flexibility with input levels.

## Project Insights
	1.	Clay & Sprinkler (Kharif) yielded the highest production (71.08 tons) primarily from Barley, but water use was relatively high.
	2.	Sandy & Drip (Rabi) stood out with strong yield (44.93 tons) and very low water use, especially for Soybean.
	3.	Flood irrigation had the highest water consumption with varying yield efficiency across soil types.
	4.	Some combinations like Loamy & Sprinkler (Kharif) used a lot of fertilizer with low yield return suggesting inefficiency.
	5.	Tomato and Maize appeared in several efficient yield combinations with modest inputs.

## Problem Statement

	How do seasonal, soil, and irrigation conditions influence agricultural yield, resource consumption (water & fertilizer), and crop efficiency?

## Business Questions Answered
	•	Which combinations produced the highest crop yield?
	•	Clay & Sprinkler (Kharif) and Clay & Flood (Rabi) were top performers.
	•	Which combinations used the least water per yield unit?
	•	Sandy & Drip (Rabi) delivered high efficiency in yield-to-water ratio.
	•	Which soil-irrigation pairs wasted resources?
	•	Loamy & Sprinkler (Kharif) showed high input, low output — poor return on fertilizer use.
	•	Are there crops that consistently perform well?
	•	Yes — Tomato, Soybean, and Barley appeared in multiple high-yield, efficient setups.

## Recommendations
	1.	Scale up use of drip irrigation, especially in sandy soils during the Rabi season they offer strong water efficiency.
	2.	Avoid flood irrigation in sandy areas unless yield return justifies the heavy water use.
	3.	Optimize fertilizer allocation — combinations with high fertilizer but low yield should be deprioritized.
	4.	Focus on versatile crops like Tomato and Soybean for their adaptability and efficient resource use.
	5.	Introduce monitoring of yield per hectare and resource per ton metrics in future reporting.

## Conclusion

This dashboard provides a clear view of how soil, season, and irrigation methods interact to affect crop yield and resource use. It helps identify not only the most productive combinations but also the most sustainable ones — guiding better farming practices that balance productivity with efficiency.






