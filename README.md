# Tidy Tuesday with Python
My weekly (or monthly) data visualisation practicing using data from TidyTuesday, using Matplotlib and Python instead of R!

# Projects

## 14 June 2022
The data set is on droughts in the US but I focused on California. It isn't going well...
![IMG_6613](https://user-images.githubusercontent.com/77285010/173525177-0d7c189f-62a7-4e32-b12a-fa870e78a982.JPEG)

Code: [Here](https://github.com/xh313/TidyTuesdayWithPython/blob/main/TidyTuesday140622.ipynb)

## 7 June 2022
Holding companies donating to anti-LGBTQ politicians accountable.
![image](https://user-images.githubusercontent.com/77285010/172539932-98749a80-a3f1-42e1-8570-26daa07c6f28.png)
Condensed:
![image](https://user-images.githubusercontent.com/77285010/172540033-f1fd89da-2932-4224-a0bb-62c658a997ef.png)



Code: [Here](https://github.com/xh313/TidyTuesdayWithPython/blob/main/TidyTuesday07062022.ipynb)

## 24 May 2022
Women's rugby.
![image](https://user-images.githubusercontent.com/77285010/172507547-2bd106f1-24d0-430c-83f6-383b9fc0f744.png)

Code: [Here](https://github.com/xh313/TidyTuesdayWithPython/blob/main/TidyTuesday24052022.ipynb)

## 17 May 2022
Eurovision! And the drastic contrast between 2022 and 2021.

2021:
![image](https://user-images.githubusercontent.com/77285010/168933051-b9dd7e9a-8796-4dc8-879d-8d03ee2457d5.png)

Whereas 2022:
![image](https://user-images.githubusercontent.com/77285010/168933069-18ee2f83-b542-4e1b-99e2-e5cf932eaf88.png)

All of our best wishes go to Ukraine <3

Plotted on Python using Basemap in Matplotlib and Geopy.

Code: [Click here](https://github.com/xh313/TidyTuesdayWithPython/blob/main/TidyTuesday17052022.ipynb)

## 3 May 2022
After a month of random COVID disruptions and UCLA DataFest I am finally back to TidyTuesday!

Today's raw data: https://github.com/rfordatascience/tidytuesday/tree/master/data/2022/2022-05-03

Graphic:
![image](https://user-images.githubusercontent.com/77285010/166563044-82c86dd3-f435-4d74-87f8-190df2046339.png)


## 29 Mar 2022

Plotly is so cool!

** LOGGING IN PROCESS NOT FINISHED **

![ncaafunds](https://user-images.githubusercontent.com/77285010/160757774-009472e4-ab94-4876-93d4-a698e16894c4.png)


## 22 Mar 2022

Cheesiest plot I've made so far...

** LOGGING IN PROCESS NOT FINISHED **

Data processing logic:
- Raw data: [https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2022/2022-03-22/babynames.csv]
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
![A graphic showing the trendiness of a selection of feminine baby names across the time span from 1960 to 2017.](https://user-images.githubusercontent.com/77285010/159595530-db8cbe5c-5565-4507-8b18-5a7ff6cd0c0e.png)

XH
22 Mar 2022


## 08 Mar 2022

**PENDING**


## 01 Mar 2022

Tried Geopandas and Geoplots the first time! I'd say I would probably rather use seaborn the next time though...

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
