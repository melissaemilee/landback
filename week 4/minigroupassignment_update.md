# Landback: UP206A GIS mapping around open and public lands for the people


**Group**: Lupe Renteria Salome & Mel Liu
**Group Name**: Land Access 4 All
[Here is the link to our original propoals on Land Access and Use for Humans & Non-Humans]()

## Roles
Lupe Renteria Salome will be working on shape and demographic data explorations, and chloropleth color displays of mapping
Mel liu will work on coordinates, points, lines, and edges exploration and projection wrangling, as well as isochrones

## Status update 
remote work has been okay for us. while not ideal for class instruction, it has given us time to connect over zoom on our workflow. we feel we are both on the same page with direction of the project, but we both don't feel we know enough to make big picture decisions on how to focus the scope of our spatial analysis around vacant land in urban regions that community members can take back


Data update: 
We met with Yoh this week can were able to dcide to commite to these two data sets:

[**shape file of Los Angeles Country Community Boundaries (CSA) Countywide Statistical Area (formerly called Board Approved Statistical Areas).**](https://data.lacounty.gov/GIS-Data/Community-Boundaries-CSA-/g4rb-en2z) These provide a common geographic boundary for reporting departmental statistics for unincorporated areas to the Board of Supervisors. They can serve as proxies for neighborhood areas.

[** Vacant Parcels LA County - from ASR Use Code.**](https://data.lacounty.gov/Parcel-/Vacant-Parcels-LA-County-from-ASR-Use-Code/vcaw-zeg9) This is a subset of the Valuation and property description for parcels on the Assessor's annual secured assessment roll for 2015. This set is only parcels that were vacant in 2015 (see note under concerns below).

Lupe spent this week doing data exploration and mapping of the shape file. Mel spent this week doing data exploration and mapping of the coordinates for vacant parcels. Because there are so many vacant parcels, it is not realistic to plot as parcels, nor is it possible to get this data. Both Lupe and Mel had to struggle with data conversions to get these mappable. Lupe had challenges with finding and removing unincorporated data from the dataset above. We may need to do another data exploration of alternative shape files for LA county.

Our plan is to map these 2 first, narrow down the area in LA county to neighborhoods. Add in lines like highways, and hopefully also add in natural and industrial zones. We so far have only tackled the 2 data sources listed here.


## Major concerns
- we are still not 100% sure we are committed to LA county, but may just move forward with it given that there are a good amount of existing datasets we want to use to layer with vacant parcel data
- focusing on marginalized communities, specifically Indigenous communities in LA county has proven to be challenging given that data is limited and problematic in it consistency, specificity, and integrity. We learned this from last week's Census assignment. 
- parcel data file Mel worked on is large, at 39 mb. Mel is trying to balance deleting columns without losing important information in reducing file size.

## Minor concerns
- we haven't learned how to layer shape and points yet from imported data. Lupe and Mel have a learning curve to figure this out
- learning how to work with projections across all of our geodataframes
- Mel's time has been spent with the steep learning curve of python on figuring out how to work with converting csv longitude and latitude to geomtries and getting them on projections and maps...


