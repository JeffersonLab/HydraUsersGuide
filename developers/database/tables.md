---
title: "Table Descriptions"
parent: "Database"
grand_parent: "Developers"
nav_order: 1
---

# Table Descriptions

Hydra's back end is an extensive MySQL database with numerous tables. A brief description of the tables is provided below.

## AI Plots
Used for:  
Used by:  

## AI_Plots_Top_Classification_View
Used for:  
Used by:

## Balancer Status
Used for:  
Used by:  

## Feeder Status
Used for:  
Used by:  Status page, Feeder module

## Hydra Roles
Used for:  Lists the available roles in Hydra, including: Admin, Developer, Detector Expert, Labeler, Viewer and Liaison

Used by:  Labeler

## Hydra Users
Used for:  
Used by:  

## Keeper Status
Used for:  
Used by:  

## Model Thresholds
Used for:  Storing the Model ID, Plot Classification ID, Threshold, and Threshold Method (usually F1 score)
Used by:  Library Page

## Models
Used for:  Storing references to trained models, confusion matrices, loss and accuracy curves,  

Used by:  
- **Front end:** Model Library
- **System:** Hydra training script 

## Monitoring Log
Used for:  Monitoring Log stores information about all confirmed "Bad" and unconfirmed images.

Used by:  Hydra Log

## News
Used for:  To store News and alerts during Hydra operations. 

Used by:  All front end pages

## Plot Groups
Used for:  This has been deprecated, but was used to create a mapping of images to groups. 

Used by:  

## Plot Type Groupings
Used for:  This table enables a one-to-one correspondance between plot types and plot groups. 

Used by:  

## Plot Classifications
Used for:  Used to store the different types of classifications and their associated label and reserved color. The labels typically correspond to "Good", "Bad", and "NoData", but can be extended based on the end user's needs. We also reserve certain colors for the labels, for instance "Red" is reserved for Bad. 

Used by:  

## Plot Classification Types
Used for:  
Used by:  

## Plot Types
Used for:  Indicating which images Hydra should track. 

Used by:  

## Plots
Used for:  Storing references to all of the images in Plot Types  

Used by:  Image Labeler, Image Browser

## Predict Status 
Used for:  
Used by:  

## Run History
Used for:  
Used by:  

## Run Status
Used for:  
Used by:  

## Run Time
Used for:  

Used by:  

## Run Conditions
Used for:  Storing run conditions. This table is currently not used. 
Used by:  

## Status Map
Used for:  
Used by:  

## Super Groups
Used for: Advanced image filtering. This table allows for a group to contain another group. An application of this would be defining a set of images belonging to a specific run period as one group, and then having a sub-group of images related to calorimeters or tracking detectors.

Used by:  

## Training Report Elements
Used for:  Used to store the individual plots included in each training report. 

Used by:  

## Training Report Responses
Used for:  Stores the results of all the responses for every training report. 

Used by:  

## Training Reports
Used for: After a model has been trained, the model analysis script will generate a training report page that is automatically emailed to the relevant detector experts. It contains image cards where the expert can adjust the labels on the images that the model has misclassified. 

Used by:  Training Reports

## User Roles
Used for:  Tracks users and their associated roles from HydraRoles
Used by:  Labeler

## User_Permissions
Used for:  
Used by:  

## Users Plots
Used for: Labeling images  
Used by:  

## Users Plots History
Used for:  
Used by:  

## Valid Classifications
Used for:  
Used by:  

## Yoyo log
Used for:  
Used by:  

## Yoyo migration
Used for:  
Used by:  

## Yoyo version
Used for:  
Used by: 

## Yoyo lock
Used for:  
Used by:  


