# UFOs
UFO Sightings with JavaScript

## Purpose
1. Explain the strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+.
2. Describe JavaScript syntax and ideal use cases.
3. Build and deploy JavaScript functions, including built-in functions.
4. Convert JavaScript functions to arrow functions.
5. Build and deploy forEach (JavaScript for loop).
6. Create, populate, and dynamically filter a table using JavaScript and HTML

## Overview 
The request from a client was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website. 

## Results:
### Welcome to UFO Sightings! 

<img width="1724" alt="Screen Shot 2022-07-27 at 12 10 50 PM" src="https://user-images.githubusercontent.com/104115586/181342722-9ff59987-4ab5-4e14-a1cb-3e48b91269a4.png">



### How the page looks when the user opens for the first time, filters are left blank.
<img width="1721" alt="Screen Shot 2022-07-27 at 12 06 11 PM" src="https://user-images.githubusercontent.com/104115586/181342444-df484ca0-8a8b-4a26-9339-30a2ff6159fb.png">

### How the filters appear after being used: 
By typing in the suggested placeholder elements as the filters, the result returns matches.  Make sure to type everything in lower case letters and do not have spaces at the end of the text.  Click off the input box or press enter to initiate the filter.  To reset the filter criteria, click the UFO Sightings at the top left of the website. 

### Filtering by city.
<img width="1724" alt="Screen Shot 2022-07-27 at 12 06 44 PM" src="https://user-images.githubusercontent.com/104115586/181342813-73274a47-f2c8-425a-b785-0b1583bda6eb.png">

### Filtering by State
<img width="1724" alt="Screen Shot 2022-07-27 at 12 07 39 PM" src="https://user-images.githubusercontent.com/104115586/181342845-58819b03-95bb-4236-b5ca-0e52f89a640b.png">

### Filtering by Country
<img width="1716" alt="Screen Shot 2022-07-27 at 12 08 03 PM" src="https://user-images.githubusercontent.com/104115586/181342871-9b447f37-5df4-4a69-8483-2454ea726ac5.png">


### Filtering by shape
<img width="1718" alt="Screen Shot 2022-07-27 at 12 07 21 PM" src="https://user-images.githubusercontent.com/104115586/181342828-23cb5c30-2d76-43df-bb96-59667b8ad80d.png">



## Summary: 

### Drawback:
The user must know specific dates, cities, or shapes to search.  Some shapes like "light" might not be as intuitive.  The filters require correct lower-case spellings and cannot include spaces at the end.  The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon".  The only acceptable input would be "el cajon".

### Recommendations: 
1. The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases.
![Pic 4](https://github.com/Baylex/UFOs/blob/main/static/images/trim.PNG)

2. A filter on a date range might be preferable than a singular date.  Typing 1/2010 did not bring up all the dates from January as hoped.  Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month.  It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings. 
