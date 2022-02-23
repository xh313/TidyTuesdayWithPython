# Tidy Tuesday with Python
My weekly (or monthly) data visualisation practicing using data from TidyTuesday, using Matplotlib and Python instead of R!

# Projects
## 22 Feb 2022

Happy 22022022 palindrome day!

*Content note: The raw data given by TidyTuesday this week involves comparison between countries, 
which might involve some political disputes and/or underlying assumptions. The raw data does not
come from me and does not represent my political opinions. Please assess the credibility of the
original data under your own judgements.*

Data processing logic:
- Raw data: (Link to the TidyTuesday Repository)[https://github.com/rfordatascience/tidytuesday/blob/master/data/2022/2022-02-22/freedom.csv]
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
