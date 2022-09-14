### Analysis Overview

The purpose of this analysis was to create an interactive webpage using HTML, Javascript, and D3 that allows users to view a collection of UFO sighting data. Users
can input different filter criteria (Date, City, State, Country, Shape) to narrow their search and gather relevant UFO sighting information.

### Results

#### Performing a Search
To perform a search, users input filter criteria into any, all, or none of the Filter Search input boxes. If no filter criteria is entered, the UFO sightings for the placeholder inputs (1/10/2010, Roswell, CA, US, Circle) will be shown (Fig. 1), while if a filter input is entered (such as City = Aspen), the UFO sightings matching the filter criteria will show in the table (Fig. 2). 

##### Fig. 1
![UFO_unfiltered](https://user-images.githubusercontent.com/108199140/190280517-c32b95e5-c1fe-45fd-9374-acfc826314b5.PNG)


##### Fig. 2
![filtered_UFOs](https://user-images.githubusercontent.com/108199140/190280548-9cd1aa9f-fa7a-4c9a-96d0-11c8a71f0d1b.PNG)


### Summary

#### Drawbacks and Recommendations
One drawback of this webpage is the unlimited length of the table. While the UFO Finder table is interactive and will change based on filter criteria, it will display
the total amount of data down the webpage regardless of table length which can make the table overwhelming and create an unpleasing user experience. One recommendation
to develop this webpage further would be to add the ability to have a fixed table size with the ability to scroll down the table. This would create a cleaner UI with a 
fixed webpage length and compacted data. A second recommendation would be to add an additional filter for "Keyword" which would build upon the "Description" column of the table. This would allow even more specific searches to find UFO sighting relevant to user interest. For example, to do this the following code could be added within ``` </ul>: ```

```
<li class="list-group-item bg-dark">
  <label for="description">Enter Keyword </label>
  <input type="text" placeholder="sky" id="keyword"/>
```
