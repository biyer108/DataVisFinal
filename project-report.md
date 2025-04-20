# Project Report - CS 625, Spring 2025

Bhargav Iyer
Due: April 20, 2025

## Dataset

Stars are the birthplaces of planets, and their properties—like mass, temperature, and spectral type—can significantly influence the characteristics of orbiting planets. Understanding how planetary systems vary across different types of stars can give us insights into planet formation, system evolution, and even where life might be more likely to exist. With thousands of discovered exoplanets, we can now visualize patterns in real data to better understand our cosmic neighborhood.  I have always been interested in planets and stars and want to learn more about it through visualizing it.

The Planetary Systems Composite Parameters Planet Data table (PSCompPars) is a compilation of system, stellar, and planetary parameters for known Confirmed Exoplanets. The purpose of this table is to enable a more statistical view of the known exoplanet population and their host environments.  I am using the different features such as stellar temperature, stellar mass, planet's equilibrium temperature, and Stellar Types (Type of Star a planet is orbitting).

Link:  https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PSCompPars

(NASA Exoplanet Archive data comes from a combination of sources and is curated by NASA and Caltech/IPAC (Infrared Processing and Analysis Center))

### Heading: How Stellar Properties Shape Planetary Systems: From Spectral Types to Planet Temperatures

## How does the number of known planets vary across different spectral types of stars?



Idiom: Histogram Chart / Mark Color
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Stellar Type | key, categorical | vertical spatial region (y-axis) |
| Number of Planets | value, quantitative | horizontal position on a common scale (x-axis) |

## How does a planet’s equilibrium temperature relate to its host star’s mass and temperature?

Idiom: Scatterplot Chart / Mark Color
| Data: Attribute | Data: Attribute Type  | Encode: Channel | 
| --- |---| --- |
| Stellar Mass | value, quantitative | vertical spatial region (y-axis) |
| Planet Equilibrium Temperature | value, quantitative | horizontal position on a common scale (x-axis) |

## Final Thoughts
Developing this visualization project using the NASA Exoplanet Archive dataset was an insightful and rewarding experience. The overall process—from formulating meaningful questions, exploring the dataset, to building interactive visualizations—took approximately 12–15 hours spread across several sessions.

1. Initial Data Exploration & Question Design (3–4 hours):
- Understanding the structure and richness of the dataset took a significant amount of time. It involved filtering for the most reliable fields (e.g., pl_eqt, st_teff, st_mass, st_spectype) and crafting questions that would go beyond simple descriptive stats to uncover meaningful patterns.

2. Visualization Development (6–7 hours):
- This was the most time-consuming phase. Building interactive visualizations with Plotly required careful selection of chart types, tuning layout aesthetics, and implementing features like dropdowns and sliders to make the experience intuitive and engaging. Debugging interactivity issues—especially around grouping spectral types and enabling responsive filtering—also added to the workload.

3. Narrative Structuring & Storytelling (2–3 hours):
- Connecting both visualizations into a cohesive story took focused effort. The challenge was not just in explaining what the visualizations show, but why those insights matter scientifically. Writing the narrative to logically progress from general patterns (planet counts by star type) to specific conditions (planetary equilibrium temperatures) helped reinforce the value of the data.

## References

*Every report must list the references (including the URL) that you consulted while completing the assignment. Replace the items below with the references you consulted*

* Reference 1, <https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PSCompPars>
* Reference 2, <https://www.example.com/reallyreallyreally-extra-long-URI/>
