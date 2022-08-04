# Tanzania Water Pump Status

**Author**: [Samuel Kabati](sam.kabati@student.moringaschool.com)

## Business Problem
Water is critical to the health of people. In Tanzania, there's a population of 59 million. Four million of these people lack access to an improved water source and 29 million lack access to improved sanitation. As most of the country is arid or semi-arid, Tanzania's ground water(wells/waterpoints) is the main source of water for the people.
There are many waterpoints already established in the country. An NGO focused on improving Tanzania's water situation would like to be able to predict functional waterpoints, those that are functional and need repair and those that are completely non-functional. This would go a long way in trying to maintain the already existing water infrastructure to allow for better water access across the country improving people's quality of life.
## Data
The data used in this analysis is downloaded from [DrivenData](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/data/).The data comes from the Taarifa waterpoints dashboard, which aggregates data from the Tanzania Ministry of Water

## Methods

This project uses exploratory data analysis and machine learning techniques.

## Conclusions 
- The classifier is suitable for predicting the status of the waterpoints.
- The quantity of water is crucial in determining the status of a waterpoint
- The location is important in determining the status of a waterpoint
- Shallow wells and boreholes have the highest number of non-functional wells in comparison to the functional ones.


## Recommendations
- Waterpoints with low water quantities should be frequently looked at as they have a very high chance of failing.
- Locations that have a very high number of nun-functional waterpoints should be prioritised during repairs.
- Shallow wells and boreholes should be closely monitored as they tend to have a very high number of non-functional wells.


## Repository Structure
```
├── Data              
├── images             
├── Presentation.pdf                    
├── README.md              
├── Tanzania Water Pump Staus.ipynb 
 ```