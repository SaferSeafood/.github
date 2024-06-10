# SaferSeafood 
![Uploading team-saferseafood.jpg…]()


## Improving Access to Fish Consumption Advisories and Maintaining Confidence in California’s Healthy Seafood Products

This is a [capstone project](https://bren.ucsb.edu/projects/improving-access-fish-consumption-advisories-and-maintaining-confidence-californias) for the Master of Environmental Data Science at Bren School of Environmental Science and Management, University of California, Santa Barbara. The authors of this project are [Hope Hahn](https://github.com/h-hahn), [Luna Herschenfield - Catalan](https://github.com/lunacatalan), [Ben Versteeg](https://github.com/BenVerst) ,and [Kate Becker](https://github.com/kateebeckerr) and created for our clients at [Scripps: ](https://scripps.ucsd.edu) Institute of Oceanograhy UC San Diego  and the California Cooperative Oceanic Fisheries Investigation ([CalCOFI](https://calcofi.org/)). 


## Project Summary

Dichlorodiphenyltrichloroethane (DDT) is an insecticide that is resistant to degradation and can cause increased risks of cancer, premature births, developmental abnormalities, and neurological diseases in humans and animals. A recent rediscovery of a vast barrel field of DDT-laced sludge off the coast of southern California has captured the attention of the public and raised concerns regarding consumption of contaminated seafood. Alongside direct public health impacts, a decrease in seafood consumers poses a threat to the regional economy and recreational fishing communities. Currently there statewide consumption advisories for coastal communities. However, these advisories are severely limited as they are site and species-specific, covering only two chemicals: Mercury and PCBs. These limitations make it nearly impossible for consumers to receive proper guidance on all safe and healthy seafood products. 

Scientists at the Scripps Institute of Oceanography and CalCOFI have collected and compiled fish and sediment monitoring data in order to understand the human and ecological impact as a result of the DDT dumping. Their current model has shown that they can predict localized risk in sport fish, and our goal is to expand on this to develop a spatiotemporal statistical model to produce more accurately predicted DDT concentrations for unmeasured species and locations. We will also develop an interactive online application that will allow users to input species, location, and demographic information and receive predicted DDT concentrations and advisories. This project will help to inform the public and give users the autonomy to understand the risk and make informed decisions on their seafood consumption.

## What's in this repository?
This organization holds three GitHub repositories (**Models, Shiny-Dashboard, and .github**) that contain all files and data used in completing the deliverables of this project will be published and openly available. All code, data, and metadata are thoroughly commented and workflows are cleaned to ensure reproducibility.

Within the **Models repository**, there are two main folders which are named ‘code’ and ‘data’. The data folder contains three folders, two of which (‘fish_data’ and ‘sediment_data’) contain the data that was received from the client, and the third ‘data_outputs’ folder contains cleaned data and tables that were produced in the process of completing this project. All code files exist in the folder called 'code', which has two folders nested within it: data_cleaning and models. The 'data_cleaning' folder contains a script that includes all necessary data cleaning, and all cleaned data was saved as a data output in the 'data_outputs' folder within the main 'data' folder to streamline data usage within the modeling files. The 'models' folder contains files of model analysis processes. All of the model testing processes are in .Rmd files that contain all the code including a written description of each step, which is described in detail in the Analysis section. The session_info.txt file documents all packages and versions used in the processing of code.

The **Shiny-Dashboard repository** includes all code used for creating the interactive web application. The main files for building the shinydashboard are the ui.R, server.R, and global.R. This repository also includes a ‘data’ folder with all the data outputs from the analysis in the ‘Models’ repository that are needed, a ‘sediment_data’ folder to build the maps of fishing zones, ‘polygons’ folder with polygons of OEHHA advisory zones, and ‘OEHHA’ folder with the .csv files of advisories associated with each polygon, and ‘fish_image’ with images of fish rendered at each prediction. The ‘www’ folder includes any logos and other images used.


## Acknowledgments 

This project could not have been completed without the support and guidance of this project.

- **Faculty Advisor:**
  - Dr. Bruce Kendall, Bren School of Environmental Science & Management

- **Capstone Advisor:**
  - Dr. Carmen Galaz García, Bren School of Environmental Science & Management

- **Clients:**
  - Dr. Erin Satterthwaite, Sustainability Researcher, Sea Grant & CalCOFI, Scripps Institution of Oceanography, UCSD
  - Dr. Lillian McGill, Scripps Institution of Oceanography, UCSD
  - Dr. Brice X. Semmens, Director, California Cooperative Oceanic Fisheries Investigations (CalCOFI), Professor, Scripps Institution of Oceanography, UCSD

- **Special Thanks:**
  - Allie Caughman, Ph.D. Candidate, Bren School of Environmental Science & Management
  - Dr. Amalia Aruda Almada, Extension Program Leader, Science, Research, and Policy Specialist, University of Southern California Sea Grant Program
  - Maria Madrigal, M.S., Education Manager, University of Southern California Sea Grant Program
  - Ian Brunjes, SCCOOS
  - Dr. Wes Smith, Chief, Fish, Ecotoxicology & Water Section, OEHHA/CalEPA
  - All the amazing people in the Masters of Environmental Data Science Cohort and Capstone Committee

## References 
California Cooperative Oceanic Fisheries Investigations. (n.d.). CalCOFI: California cooperative oceanic fisheries investigations. Retrieved June 3, 2024, from https://calcofi.org/.

McGill, L., Sleugh, T., Petrik, C., Schiff, K., McLaughlin, K., Aluwihare, L., & Semmens, B. (2024).
The persistent DDT footprint of ocean disposal and ecological controls of bioaccumulation in fishes. Unpublished manuscript, Scripps Institution of Oceanography, University of California, San Diego, La Jolla, CA, USA, and Southern California Coastal Water Research Project, Costa Mesa, CA, USA.

Scripps Institution of Oceanography. (2024, June 6). https://scripps.ucsd.edu/ 

