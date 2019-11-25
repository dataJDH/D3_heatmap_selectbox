# D3_heatmap_selectbox
Heatmap with interactive select box.

earthquakes.csv describes the earthquake counts for different states from 2010 to 2015 in the US. 

Code creates a heatmap of the earthquakes for different states from year 2010 to 2015 (inclusively) and places the state name on the heatmap's horizontal axis and the year on its vertical axis. 
Code adds axis labels and a legend to the chart. Places the year (2010, 2011, 2012, etc.) on the vertical axis (i.e. top → bottom: 2010 → 2015). Places the state name ("Alabama", "Arizona", "Arkansas", etc.) on the horizontal axis also in alphabetical order (i.e. left → right: A → Z).
Code creates a drop down select box with D3 based on the total counts (from 2010 to 2015) of earthquakes of a state. The selections are “0 to 9”, “10 to 99”, “100 to 499”, and “500 or above”. When the user selects a different range in this select box, the heatmap and the legend are both updated with values corresponding to the selected range. Legend threshold values will change.
When the mouse cursor is on a heatmap cell , the value of that cell will be displayed between the chart title and the heatmap.
