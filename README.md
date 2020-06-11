# Project - X

**Best Interactive Visualization/Dashboard**

Criteria 
- [ ] Simplicity and ease of navigation 
- [ ] Choice of encodings and colors
- [ ] Ease of understanding
- [ ] Impact and take-aways
- [ ] Documentation

Hackathon info at [UW-COVID-19-Hackathon](https://data-science-hackathon.github.io/COVID-19-Hackathon/)

Using data from 
- [Oxford Covid-19 Government Response Tracker (OxCGRT)](https://github.com/OxCGRT/covid-policy-tracker)
- [Coronavirus (Covid-19) Data in the United States](https://github.com/nytimes/covid-19-data)

Basic Project Outline
1. **World View**
2. **Country View (USA)**
3. **County/State View**

Keeping visualizations and flow as as interactive as possible... 
## 1. World View
Visualizations based on COVID tracking from all over the world.

*This could be a Dashboard, can take some kind of inspiration from this: [JH covid tracker ](https://coronavirus.jhu.edu/map.html) 
- World Map showing latest data of:
	- covid cases per country
	- covid deaths per country
	- government response index per country
- Visualization for Severity of covid cases over a user-given time-frame.
- Rate of change in covid cases per country based on doubling factor.

clicking on a country or using a magnifying icon leads to the next section...

## 2. Country View 

- Current covid cases, deaths, and government policies, with implemented indicators, will have an add button to include more countries for comparison of stats. 

Kinda like [versus.com](https://versus.com/en) maybe?  User can see which country is better off with the response index, we could even have a radar wheel chart regarding the extent to which a policy was implemented. Check out this example [comparing phones.](https://versus.com/en/apple-iphone-11-pro-vs-oneplus-8-pro-vs-samsung-galaxy-s10-vs-sony-xperia-1-ii-5g) (might be ambitious but we could implement a portion of it).

- A playground for user to experiment with Different indicators for a country by changing the importance (weight) given to it to assess the rate of change in covid cases.

For this we'll need to find out relationship or significance of indicators w.r.t. rate of covid cases. 

## 3. County/State View

- Covid deaths vs actual number of deaths in county/state.
- Covid cases per state
