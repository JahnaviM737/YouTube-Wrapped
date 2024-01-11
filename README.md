# YouTube-Wrapped
Making my own YouTube and YouTube Music Wrapped using data from Google Takeout because my YouTube Music Recap of 2023 was definitely not accurate (and because I used one account till July and another from August so the actual numbers are the aggregation of both *sigh*)

### If you want to watch a fun video instead of reading about this project: https://youtu.be/Pdwi8ROtxMk

### Figma prototype: {Click to view the UI Screens in Action}[https://www.figma.com/proto/kqW1YuJvqCbYx2PvkMVUk2/YouTube-Wrapped?type=design&node-id=4-75&t=EF5ZA7bwezexGYp1-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=4%3A75&show-proto-sidebar=1&mode=design]

Let's do this a bit more formally, shall we? <br>
## Introduction
This repository encapsulates the comprehensive analysis and exploration of my YouTube Wrapped for the year 2023. The initiative was sparked by the revelation that YouTube's automated service inaccurately identified my top song, setting the stage for a deep dive into the intricacies of my music consumption throughout the year.

## Motivation
YouTube Wrapped, a yearly feature that summarizes users' viewing and listening trends, served as the impetus for this independent investigation. The discrepancy in the identified top song not only raised concerns about the reliability of the provided statistics but also presented an opportunity to craft a personal, data-driven narrative.

## Data Quest
The initial phase involved problem identification and data acquisition. Contrary to initial expectations, obtaining the actual watch history required a meticulous process, including Google Takeout for data extraction. The collected raw data, sourced from two separate accounts due to a geographical relocation, laid the groundwork for subsequent analysis.

## Data Preprocessing Ballet
Data preprocessing became a pivotal step in refining the collected information. The ballet of data science unfolded, involving the handling of outliers, addressing missing data points, and ultimately preparing the dataset for analysis. Unexpectedly, the data arrived in HTML format, prompting an exploration of web scraping techniques using the BeautifulSoup library.

## Data Modeling
Normalization emerged as a critical aspect of data modeling. The structure of the data, which encompassed both YouTube video watches and YouTube Music song listens, necessitated the creation of distinct tables. A detailed sketching process aided in conceptualizing and organizing the relational connections between tables.

## Analysis Rodeo
The analysis phase delved into the nuances of data manipulation using SQL queries translated into Pandas functions. Filtering, merging, aggregating, and sorting maneuvers were executed to derive meaningful insights. The project showcased the amalgamation of coding skills and creativity in transforming raw data into coherent visualizations.

## Results Unveiling
The grand unveiling presented a meticulous breakdown of YouTube Music and YouTube Video Wrapped for the year 2023. Detailed statistics on streaming minutes, top artists, tracks, and notable consumption patterns were disclosed, accompanied by commentary on surprising revelations and personal reflections.

## Conclusion
In conclusion, this project encapsulates a multi-faceted journey, encompassing data acquisition, preprocessing, modeling, analysis, and results presentation. Beyond the unveiling of personal music trends, the endeavor facilitated skill development in SQL, Pandas, web scraping, UI design, and long-form video editing.

## Project Structure
* code/: Python scripts and Jupyter Notebooks for data extraction, preprocessing, and analysis.
* data/: Raw data extracted from Google Takeout and intermediate CSV files.
* figures/: Visualizations and graphs generated during the analysis.
* README.md: This comprehensive report providing an overview of the project.