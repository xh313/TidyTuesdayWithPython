# Tidy Tuesday with Python
My weekly (or monthly) data visualisation practicing using data from TidyTuesday, using Matplotlib and Python instead of R!

# Projects
## 01 Mar 2022

Tried Geopandas and Geoplots the first time! I'd say I would probably rather use seaborn the next time though...

** LOGGING IN PROCESS NOT FINISHED **

Data processing logic:
- Raw data: [https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2022/2022-03-01/stations.csv]
- Map the points on the country map using the LONGITUDE and LATITUDE columns.
- Colour code the points using the column FUEL_TYPE_CODE distinguishing the fuel types.

Visual features:
- Designs:
  -  Map of the US (excluding Alaska and islands) as background with faint county borders
  -  Translucent data points showing the density of the distribution clearly
  -  Legend showing fuel types
- Avenir typesetting! Avenir is the best
- Also added Alt text

Issues:
- Projection: whenever I employ projection methods the session crashes, so now the map looks kind of squished
- The spots on the legend are so faint that it's hard to tell apart the difference in colours
- The legend handles are currently acronym and might work better if I type in the full name

Plans:
- Maybe fix the projection issue
- Differentiate the colours more

Graphic:
![A graphic showing the alternative fuel station distribution in the US. The shape of the country excluding Alaska and islands are shown on the background with bright points indicating the occurrences of the stations in different regions. The colours mark the type of alt fuel the stations supply. ](https://user-images.githubusercontent.com/77285010/156272212-6f779af9-70fd-4352-81c1-7ccfa4a250e0.jpg)

XH
01 Mar 2022

## 22 Feb 2022

Happy 22022022 palindrome day!

*Content note: The raw data given by TidyTuesday this week involves comparison between countries, 
which might involve some political disputes and/or underlying assumptions. The raw data does not
come from me and does not represent my political opinions. Please assess the credibility of the
original data under your own judgements.*

Data processing logic:
- Raw data: [https://github.com/rfordatascience/tidytuesday/blob/master/data/2022/2022-02-22/freedom.csv]
- Selecting the column of 'Status' (Free, partially free and not free) 
- Extract the status of each country for every year (1995-2020), count the data and funnel into 3 dictionaries.
- Show the trend of the number of countries that are in each status over the 26 years

Visual features:
- Designs:
  -  Used mock-ggplot style with some modifications (facecolor etc.)
  -  Translucent on-graph legend with sharp corners
  -  All-filling solid colours with different shades
- Avenir typesetting! Avenir is the best

Issues:
- Sort of boring (I didn't have much time to make it fancier :(
- Would probably work better if the graph is more horizontal (aka the height could be decreased)
- The grids in the background are useless since the area fills don't have an alpha (quick fix)

Plans:
- Add alphas to the filled area under curves
- Change graph dimensions
- Improving the documentation and styling
- Alt text

Graphic:
![image](https://user-images.githubusercontent.com/77285010/155228929-2977f09b-6437-45b1-88c1-fc0185085030.png)

XH
22 Feb 2022

## 8 Feb 2022 (actually using the data set from 25 Jan 2022)
I am not interested in random american airforce people so I pulled out an old boardgame data set instead!

** LOGGING IN PROCESS NOT FINISHED **

Data processing logic:
- Data on dog breeds and their different traits
- Quantifying all qualitative descriptions into scores using text processing
- Weighting and categorising each trait into two new parameters 'friendliness' and 'fluffiness'
- Plot scatter plot with each point corresponding to a breed on the quadrant of fluffiness-friendliness

Visual features:
- Detecting overlapping points or close-by points automatically and wrap/dodge off the labelling (still bugged :( )
- Generating a new colour for each data point on the tab 20b palette (or any other palettes, might change it if in the mood)
- Avenir typesetting! Avenir is the best
- Annotation of the breed name beside each data point
- Legend indexing all 190+ breed names

Issues:
- The overlap detector does not work for certain few points for some reason
- Graph too huge with too many data points -- hard to read! Don't know if there's a better way to present the data!
- Might need to adjust some weighings a bit (as I don't own a dog myself, I am biased!)

Plans:
- Indexing the position on the diagram for each breed and incorporating into the legend
- Improving the documentation and styling (it is currently unfortunately a mess!)

Graphic:
![image](https://user-images.githubusercontent.com/77285010/153077694-223bb4b3-3a34-4551-8f44-0073bddb0e35.png)

XH
8 Feb 2022

## 1 Feb 2022

Data processing logic:
- Data on dog breeds and their different traits
- Quantifying all qualitative descriptions into scores using text processing
- Weighting and categorising each trait into two new parameters 'friendliness' and 'fluffiness'
- Plot scatter plot with each point corresponding to a breed on the quadrant of fluffiness-friendliness

Visual features:
- Detecting overlapping points or close-by points automatically and wrap/dodge off the labelling (still bugged :( )
- Generating a new colour for each data point on the tab 20b palette (or any other palettes, might change it if in the mood)
- Avenir typesetting! Avenir is the best
- Annotation of the breed name beside each data point
- Legend indexing all 190+ breed names

Issues:
- The overlap detector does not work for certain few points for some reason
- Graph too huge with too many data points -- hard to read! Don't know if there's a better way to present the data!
- Might need to adjust some weighings a bit (as I don't own a dog myself, I am biased!)

Plans:
- Indexing the position on the diagram for each breed and incorporating into the legend
- Improving the documentation and styling (it is currently unfortunately a mess!)

Graphic:
![graph01022022](https://user-images.githubusercontent.com/77285010/152634365-5ebdee2d-113b-448e-b65c-a557762e87a7.png)

XH
5 Feb 2022
