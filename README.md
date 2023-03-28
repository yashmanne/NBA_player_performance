## Exploration of NBA Player Performance &amp; Salary

A three month project culminating in a 10-minute poster presentation/Q & A session. Through the project, I scraped and wrangled data from multiple sources & generated concise, unbiased visuals in Python to effectively 
showcase player performance and highlight the cost-effectiveness of team salary spending over time.

**NOTE**: 
* A continuation of the project to build an interactive dashboard can be found [here](https://github.com/vaibhavmehrotraml/NBA-Player-performance-and-Salary).
* [UPDATED INTERACTIVE TABLEAU DASHBOARD](https://public.tableau.com/views/NBAFinalProject_16705333901440/MainDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)
  * [Write-up of dashboard development process](./Interactive_Dashboard_Writeup.pdf)

### Directories
* [Data](./Data): Contains all data files used for analysis and data scraping [code](./Data/SalaryDataScraping.ipynb). Data collected from FiveThirtyEight & BasketballReference.com
 * Data Sources:
   * [RAPTOR](https://github.com/fivethirtyeight/data/tree/master/nba-raptor)
     * Contains several metrics such as RAPTOR, WAR, and PREDATOR to evaluate the performance of players on offense & defense in both the regular season and postseason updated annually.
     * WAR: [Wins Above Replacement](https://www.nbastuffer.com/analytics101/wins-above-replacement-player-warp/)
     * RAPTOR: [Robust Algorithm (using) Player Tracking (and) On/off Ratings](https://fivethirtyeight.com/features/how-our-raptor-metric-works/)
     * PREDATOR: [PREDictive rApTOR](https://fivethirtyeight.com/features/how-our-raptor-metric-works/#:~:text=RAPTOR%2Ddriven%20predictions,PREDATOR%20(PREDictive%20rApTOR).)
   * [ELO](https://github.com/fivethirtyeight/data/tree/master/nba-forecasts)
     * Game-by-game ELO ratings for each team as well as some metadata about each game played
     * Metadata defined [here](https://github.com/fivethirtyeight/data/tree/master/nba-elo)
     * [More Info](https://en.wikipedia.org/wiki/Elo_rating_system)
   * [DRAYMOND](https://github.com/fivethirtyeight/data/tree/master/nba-draymond)
     * Alternative metric for defensive prowess (limited range). Methodology defined [here](https://fivethirtyeight.com/features/a-better-way-to-evaluate-nba-defense/)
* [final_poster](./final_poster): Contains finalized plotting [code](./final_poster/final_plots.ipynb), plots, & poster. 
* [draft_poster](./draft_poster): Contains plots and draft poster as well as feedback from midway through project.
* [draft_visualizations](./draft_visualizations): Contains data wrangling [code](./draft_visualizations/ContractValuesDataMunging.ipynb) as well as draft plots & feedback from early into the project.

## Other Files
* [Final Write-up](./ManneY_FinalWrite-up): Concise summarization of project and my thoughts on the project. 
