# UFOS

### Overview of Project: 
  
  The purpose of this project is to have a head-dive into using Javascript and its tools along with HTML for Dana, a UFO enthusiast, so that others may have a quick and easy peak into UFO sighting datas in the form of a webpage and its easily navigatable search table.
  
### Results: 

<img width="1248" alt="Webpage filter screenshot_date" src="https://user-images.githubusercontent.com/68725398/102506137-cfa21780-4050-11eb-9fc2-6547addc9e63.png">

  In the above image, the date section is filled in for the date filter. This automatically detects, filters and populates the webpage based on the entries in the Filter Search. This differs from our initial webpage design in which a filter button must be clicked in order for the script to start processing what to filter.


<img width="1247" alt="Webpage filter screenshot_state" src="https://user-images.githubusercontent.com/68725398/102506139-cfa21780-4050-11eb-88c4-c489d676dbeb.png">

  This image shows the filter set to a specific state instead of the date. This is an additional filter criteria that we implemented for the new webpage, along with City, Country and Shape. Mupltiple criteria can be set at the same time for more specific filtering as well. The search detection also function just like when having only the date selected, it will automatically populate the selected criterias as soon as a change is detected.


### Summary: 

  A drawback of this design can be said in the fact that the placeholder and regular text somewhat blends into the background color theme. There are also no indicators for when a filter is functioning properly when it comes to zero data matches (ie. state initials entered into the country section).
  
  Recommendation for design changes would be to perhaps include an additional section in the filtering script that shows and notifies the user when there are no possible matches for what they entered into each of the search fields so that they will know what section triggered the mismatching. Another would be to perhaps create highlights on the inputboxes themselves when a field is being used in the filtering criteria, which gives a quick and prompt way for users to see what is or isn't used to populate the table.
