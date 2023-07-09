# What's in a name? A whole category of restaurants

## Analysis of names of darshini-type restaurants in Bangalore

This is my submission for the 2023 Lede Program's second project. 

#### Goal
Inspired by [The Pudding's piece on pub names](https://pudding.cool/2019/10/pubs/) in the UK, I wanted to recreate the analysis for the names of a particular type of fast-food restaurant in Bangalore. In my 7 years of living here, I intuitively knew that they all have similar-sounding names - I wanted to test this hunch and find a pattern of naming. I intended for it to be simple and visual.

### Data collection
My dataset was from Kaggle- [Here's the link](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)

I filtered out the darshini-type restaurants by looking for:
1. keywords in names
2. cost for two < Rs 500 

### Data Analysis:

I used pandas for basic value_counts, splitting the names into prefix, suffix

The data for the first chart can be found in the Jupyter Notebook in the [docs folder](https://github.com/aishyv/darshini-names/tree/4877d126968144ffb47e71ba6b73554e65320c59/docs)
For the second chart, I took the data into Apple Numbers and analysed it via filters and categories

### New skills, approaches
- figma 2 html (!!)
- Adding footer, favicon to the page - tiny flourishes but deeply satisfying
- a simple mapbox map

### What I tried to do (struggles)
I tried to keep it simple on data collection and heavy on data viz and CSS. HOWEVER, since I chose to do my viz through figma2html I spent too long on the execution of figma2html in html. I also tried to include maps - to show which type of names are where. But I ran out of time - so I included a very basic version 

### What I wanted to do, will probably do the next time
~Start the next project immediately?~ Pay for AI or use Datawrapper/RAWgraphs for viz. Focus more on analysis and viz. MORE CSS

The project can be found here: https://aishyv.github.io/darshini-names/
