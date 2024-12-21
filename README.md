# TLDR
This research gives a detailed overview for people thinking of moving to different states in the US. It covers important factors like Medicaid expansion, how easy it is to get around in cities, the cost of living, the political landscape, the people who live there, the weather, and the overall quality of life. 

- **Medicaid:** Looks at which states have expanded Medicaid and how they have implemented it.
- **Urban Mobility:** Shows how easy it is to walk, bike, or take public transportation in different areas.
- **Cost of Living:** Breaks down the financial aspects of living in each state.
- **Politics:** Gives information on which political party is in power.
- **Demographics:** Looks at the religious makeup of the population and the vaccination policies.
- **Climate:** Covers things like how much sunlight, snow, and rain to expect.
- **Quality of Life:** Considers things like outdoor activities, reproductive rights, and how happy people are in each state.

## Things we need to know
- list of all states [x]
- which [states](https://www.kff.org/medicaid/issue-brief/status-of-state-medicaid-expansion-decisions-interactive-map/) are on the expanded medicaid plan [x] 
	- most states, including OK, have accepted the fed funding
	- even in those that have, implementation is left up to the states and coverage varies widely even among "liberal" states 
		- more info on [state by state coverage](https://www.healthinsurance.org/medicaid/#)
- walkscore [x]
	- get the walk, transit, and bike scores for each state [x]
	- calculate medians for each of those scores by state [x]
	- calculate a [z-score](https://www.z-table.com/how-to-use-z-score-table.html) for median walk, transit, bike by state [x]
		- helps understand how meaningful the different scores are compared to each other 
	- walk, transit, and bike scores were accessed using a few different links
		- where I originally [found](https://www.reddit.com/r/fuckcars/comments/15cb7o1/i_mapped_out_each_states_largest_citys/?sort=old) the data
		- where the data were [aggregated](https://docs.google.com/spreadsheets/d/1sYdLwQd2czaHUmygStG7L1XMdqRx2z8uuoX0eNPl8nc/edit#gid=0)
		- original [source](https://www.walkscore.com/AL) for each state
	- What each score [means](https://www.redfin.com/how-walk-score-works)
#### Walk
| Score  | Category          | Definition                               |
| ------ | ----------------- | ---------------------------------------- |
| 90–100 | Walker’s Paradise | Daily errands do not require a Car       |
| 70–89  | Very Walkable     | Most errands can be accomplished on foot |
| 50–69  | Somewhat Walkable | Some errands can be accomplished on foot |
| 25-49  | Car-Dependent     | Most errands require a car               |
| 0-24   | Car-Dependent     | Almost all errands require a car         |
#### Transit
| Score  | Category          | Definition                                 |
| ------ | ----------------- | ------------------------------------------ |
| 90–100 | Rider’s Paradise  | World-class public transportation          |
| 70–89  | Excellent Transit | Transit is convenient for most trips       |
| 50–69  | Good Transit      | Many nearby public transportation options  |
| 25-49  | Some Transit      | A few nearby public transportation options |
| 0-24   | Minimal Transit   | It is possible to get on a bus             |

#### Bike 
| Score  | Category          | Definition                               |
| ------ | ----------------- | ---------------------------------------- |
| 90–100 | Biker’s Paradise | Daily errands can be accomplished on a bike       |
| 70–89  | Very Bikeable     | Biking is convenient for most trips |
| 50–69  | Bikeable | Some bike infrastructure |
| 0-49  | Somewhat Bikeable     | Minimal bike infrastructure               |

- Public transportation access/usability []
	- There's not a lot of info about this available. What's most often available are something like "the percentage of the population using public transportation"
		- I see this in 2 ways: either people won't use it because it sucks or people will still use it because it's their only option 
		- Idk if this is a good metric for accessibility and quality 
- How expensive it is to live in the state 
	- median [wage](https://worldpopulationreview.com/state-rankings/median-household-income-by-state) in state [x] 
	- median [home price](https://worldpopulationreview.com/state-rankings/median-home-price-by-state) in state [x] 
	- median [rent](https://worldpopulationreview.com/state-rankings/average-rent-by-state) in state [x] 
	- big mac [index](https://worldpopulationreview.com/state-rankings/big-mac-index-by-state) [x] 
		- This is a decent indicator of [consumer purchasing power](https://www.investopedia.com/ask/answers/09/big-mac-index.asp) and can be used to make comparisons between nations (or states)
	- median [utility costs](https://www.move.org/utility-bills-101/#Methodology)
 		- looks at costs for electricity, sewer, natural gas, water, trash services, and internet
  	- has [relocation incentive package](https://www.makemymove.com/) thing [x] 
		- not a primary reason to move to a particular state, but could help settle ties
	- Average [healthcare cost](https://www.kff.org/other/state-indicator/health-spending-per-capita/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D) per capita [x]
	- Effective local [tax rate](https://worldpopulationreview.com/state-rankings/highest-taxed-states) [x]
	- [Livable](https://research.zippia.com/living-wage.html) wage [x]
		- MIT created and maintains this [calculator](https://livingwage.mit.edu/pages/about) to show what a livable wage would be in a city based on number of adults and children in the household
			- From the specific source I'm using
        > So to clear this up a little bit, we’ve done a little digging. We researched the Living Wage for each state in the U.S., and mapped it out. Because pictures make everything easier. 
        > And just to be clear, the Living Wage we’re talking about here is how much it will cost you (annually) to actually live in each state; more specifically—the income needed to support **two adults and one kiddo** (emphasis mine)
- Which political ideology controls the state
	- [governor](https://www.kff.org/other/state-indicator/state-political-parties/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D) party [x] 
	- [house](https://www.kff.org/other/state-indicator/state-political-parties/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D)party [x] 
		- nebraska has a unicameral legislature
			- more republicans than other parties, [as of 2023](https://en.wikipedia.org/wiki/Nebraska_Legislature#:~:text=The%20Nebraska%20Legislature%20officially%20recognizes,one%20is%20a%20registered%20nonpartisan.) 
		- Penn. is having a special house election for 3 seats typically held by democrats
	- [senate](https://www.kff.org/other/state-indicator/state-political-parties/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D) party [x] 
		- nebraska has a unicameral legislature
			- more republicans than other parties, [as of 2023](https://en.wikipedia.org/wiki/Nebraska_Legislature#:~:text=The%20Nebraska%20Legislature%20officially%20recognizes,one%20is%20a%20registered%20nonpartisan.) 
	- [trump or biden](https://www.fec.gov/resources/cms-content/documents/2020presgeresults.pdf) in 2020 [x] 
	- Philosophical [vaccine exemptions](https://www.nvic.org/law-policy-state/vaccine-laws) [x]
		- religious 
		- medical
		- philosophical 
		- Included because I'd prefer to not live in a state that allows religious or philosophical exemptions 
- How many religious nutters are there 
	- Percentage of [religious](https://www.pewresearch.org/short-reads/2016/02/29/how-religious-is-your-state/?state=alabama)adults [x]
	- [Number](https://www.usreligioncensus.org/node/1639) of religious congregations per 100,000 [x]
		- [US Religion Census](https://www.usreligioncensus.org/node/1641)
			- The USRC, conducted every 10 years by the Association of Statisticians of American Religious Bodies (ASARB), is the most comprehensive effort to document religious life in every U.S. county
			- National summary data and information for individual religious bodies by nation, state, and county, as well as maps, are available on the U.S. Religion Census website
- Climate
	- Average [hours of sunlight](https://www.currentresults.com/Weather/US/average-annual-sunshine-by-city.php) [x]
		- Missing data for some states. Included because I still have data spanning the long/lat range within the US
		- [Latitude](https://www.latlong.net/category/states-236-14.html) of each state [x]
			- States between the same lines of latitude should experience [similar amounts](https://en.wikipedia.org/wiki/Daytime#) of sunlight 
		- Average annual number of clear days [x]
		  > "[S]o few weather stations [measure sunshine](https://www.currentresults.com/Weather/US/average-annual-state-sunshine.php), meaningful state-wide averages aren't available."
		- City level data for percent of [total possible sunshine](https://smartasset.com/mortgage/cities-least-depressing-winters)
	- Average [temps](https://worldpopulationreview.com/state-rankings/average-temperatures-by-state) for year [x]
	- Average [snow](https://worldpopulationreview.com/state-rankings/snowiest-states) per year [x]
	- Average [precipitation](https://worldpopulationreview.com/state-rankings/driest-states) [x]
	- Average summer highs []
		- Finally found some decent sources for this, but they don't include data less than 14 years old. Here they are for reference
			- 1981 - 2010: https://www.usclimatedata.com/climate/united-states/us
			- 1971 - 2000: https://www.currentresults.com/Weather/US/average-state-temperatures-in-summer.php
- Quality of life
	- [Outdoor options?](https://www.playgroundequipment.com/us-states-ranked-by-state-and-national-park-coverage/) (I don't know how to word this but access to beach, mountains, national parks, outdoor/nature accessibility) [x]
		- I specifically included the combined number of national and state parks in each state as a separate field, but other fields containing composite scores include various entertainment options, such as beach access, in their scoring criteria
	- [Legal abortion](https://reproductiverights.org/maps/abortion-laws-by-state/) [x]
		- 0 = illegal
		- 1 = hostile
		- 2 = not protected
		- 3 = protected 
		- 4 = expanded access 
			- laws vary
	- Right to [contraception](<- https://www.kff.org/womens-health-policy/issue-brief/the-right-to-contraception-state-and-federal-actions-misinformation-and-the-courts/>) [x]
		- laws vary by state; some are constitutionally protected some are simply laws which could potentially be overturned
	- Insurance covered [contraception](https://www.guttmacher.org/state-policy/explore/insurance-coverage-contraceptives) 
		- Laws vary by state regarding which kind of contraception, including sterilization, IUDs, and condoms
		- 0 = No
		- 1 = Prescription
		- 2 = Over-the-Counter
		- 3 = Both
	- [Quality of life](https://wallethub.com/edu/best-states-to-live-in/62617) by state [x]
		- Factors in affordability, economics, public transportation use, and safety, among other metrics
		- low score = better
		- z score [x]
	- [Happiness](https://wallethub.com/edu/happiest-states/6959) by state [x]
		- Factors in life expectancy, safety, unemployment rate, and weather, among other metrics
		- high score = better 
		- z score [x]
