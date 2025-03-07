## Twelve Years of Evidence: Modelling the Injury Severity of Single-Vehicle Collisions pre- and post-20mph Implementation in Edinburgh and Glasgow

## Project Overview
This project models the injury severity of single-vehicle collisions pre- and post-20mph implementation in Edinburgh and Glasgow. The analysis was motivated by recent changes to traffic calming policy in both cities: in Edinburgh, a citywide, blanket 20mph speed limit was introduced on all city centre roads from 2016 onwards; conversely, Glasgow expanded its network of 20mph roads in 2016, but the approach was less radical than that adopted in Edinburgh. The distinctness of the 20mph approaches in both cities allows intercity comparisions to be made concerning the efficacy of each 20mph approach. In particular, we were interested in the effect that each approach had on pedestrian safety (hence the focus on single-vehicle collisions—the vast majority of these are vehicle-pedestrian collisions in an urban context).

To assess the effectiveness of each 20mph approach, descriptive and statistical analyses were conducted during four distinct periods/scenarios (i.e., 1. Edinburgh pre-20mph intervention; 2. Edinburgh post-20mph intervention; 3. Glasgow pre-20mph intervention; 4. Glasgow post-20mph intervention).

This repository focuses specifically on the statistical analysis phase of the above study (i.e., the estimation of collision severity models across the four scenarios). The relevant road safety data were derived from the Department for Transport's (DfT) centralised database (see: https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data). Note: significant data preprocessing was required to generate the final model datasets (see 'model_data'), i.e., collision severity data per city per scenario. For more information on the data preprocessing methods used for the DfT's road safety data, please contact me at the address provided below.

## Usage
To use this repository, download the entire contents of 'collision_severity_analysis'. To access model code (see 'model_code'), open the Rmd versions of 'Edinburgh_models.Rmd' (i.e., model_code > Edinburgh > Edinburgh_models.Rmd) or the equivalent path for Glasgow. The model data are directly readable from the collision_severity_analysis GitHub repo; hence, you should not have to change the file pathname (however, if the data do not load, you can do this directly from your own PC). To run the entire Rmd file successfully, all required packages ('car', 'MASS', 'Rchoice' and 'lmtest') must be loaded, as per the first code chunk of each Rmd file. 

## Acknowledgments/Data Source
The authors would like to acknowledge the UK Gov. DfT for their provision of publicly accessible road safety data.

## Contact
Feel free to get in touch with questions or feedback. Email: torran.semple@nottingham.ac.uk; alt email: torranas@gmail.com

