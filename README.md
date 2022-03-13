# UFOs

## Overview of Project
In this project, we helped a Data Journalist work on a story regarding UFO sightings. Utilizing a file containing UFO sighting data, we were able to build a dynamic webpage using JavaScript, HTML and CSS.

## Results 

Webpage users are able to filter the table by date, city, state, country and shape. 

<img width="340" alt="Filter_Search_Image" src="https://user-images.githubusercontent.com/60076980/158062342-844d469c-580e-4d6a-aef8-853ea166a561.png">

In the image below, I entered "circle" in the shape filter on the left side of the page. This then brought up only the results with circle entered in the shape column.  

### Shape Filter
![UFO_Shape_Filter](https://user-images.githubusercontent.com/60076980/157444918-1c0bff02-6645-4a40-a6f6-12fa96883f67.png)

As seen in the image below, if a search yields no results the data section on the right side of the page will be blank. In this example, I searched the the state "mn", however there were no results found.

Users can also search by multiple filters at the same time to narrow down the results. In the example below, I entered "ca" in the state field and "triangle" in the shape field to narrow down the results.

### Multiple filters
<img width="1435" alt="Multiple_Filters" src="https://user-images.githubusercontent.com/60076980/158062876-6e0f8952-4117-4147-b470-03f8fcad17c5.png">

### No results
<img width="1322" alt="Filter_Search_2" src="https://user-images.githubusercontent.com/60076980/158062415-f51abed7-46e7-4e71-bb92-bd5a9c452bae.png">

### Final Webpage
![UFO_Webpage](https://user-images.githubusercontent.com/60076980/157444472-12f19cea-4f37-4a0d-9a11-3760ba24ab39.png)

## Summary

One drawback that I noticed is that the comments that are too long get cut off mid-sentence. It would be helpful to have an option to expand the row by clicking on it or hovering over it. Another drawback is that the filter fields are case sensitive, so for instance searching by the state "ca" will return several results, but searching for "CA" will not return any. I would recommend removing the case-sensitivity in order to make the webpage more user friendly. The data file only included UFO sightings from 2010, so I would recommend using data from additional years in order to look for any trends or anomalies.
