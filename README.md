# `ggplot2` Visualization Workshop

Visualizing data is extremely important for exploratory data analysis. This goal of this workshop was to demonstrate simple techniques that are helpful for visualizing data as part of the exploratory data analysis process.

The dataset that was utilized for this workshop came from the State of Delaware's Office of Management and Budget FOIA Logs. The original dataset can be found in the `Data` folder. The cleaned data (that was actually used in the workshop) can be found in the `Data_Transformations` folder. The script that was used to clean the data is called `OMB_FOIA_Log_Cleaning.Rmd`.

The fields that are available to use in the final, cleaned dataset are:

`Date_Received` - the date that the FOIA request was received by OMB
`Requesting_Party` - who made the FOIA request
`Date_Assigned` - the date the the FOIA request was assigned to a person at OMB
`Assigned_to` - who the FOIA request was assigned to at OMB
`Division` - the division at OMB that the FOIA request was directed to
`Information_Requested` - the information that the FOIA request is looking for
`Date_Review` - date that the FOIA request was reviewed by OMB
`Is_Noncustodial_Record` - whether or not the information sought after in the FOIA request is something that OMB has access to
`Noncustodial_Provided_Other_Agency` - in the case that there is a noncustodial record, which agency would be more appropriate to review the request
`Internally_Reviewed_By` - who the FOIA request will be reviewed by at OMB
`Interim_communication` - any communication that has occurred between the date received and the date of final disposition
`Date_Response` - date that the FOIA request was responded to
`Date_Estimate_Sent` - date that an estimate for the cost of the FOIA request was sent
`All_Requested_Records_Sent` - whether all requested records were sent to the requestor (original field)
`All_Requested_Records_Sent_Flag` - whether requested records were sent to the requestor
`All_Requested_Records_Sent_Detail` - detail regarding whether requested records were sent to the requestor
`Date_Requested_Records_Not_Provided` - date or note regarding whether or not records were provided
`Copying_Fees` - any copying fees (first 20 pages are free)
`Administrative_Fees` - any administrative fees
`Date_of_Final_Disposition` - date that the final records are sent
`Current_Status` - status of the FOIA request (original)
`Current_Status_Overall` - simplified status of the FOIA request
`Current_Status_Detail` - simplified detail of the FOIA request

In addition, this repository contains two files that acted as companions to the workshop. First, `OMB_FOIA_Log_Visualization_Workshop.Rmd` contains a mostly blank file that can be used to solve key questions about the analysis. Second, `OMB_FOIA_Log_Visualization.Rmd` contains a completed file that shows the solutions to answer those questions.

An interactive version of this project can be found at [RStudio Cloud](https://rstudio.cloud/project/282267).
