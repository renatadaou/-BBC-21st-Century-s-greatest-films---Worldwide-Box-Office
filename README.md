# BBC 21st Century's greatest films - Worldwide Box Office 📣🎬🎥🎞
 In this project, the objective was to extract data from the [BBC Culture](http://www.bbc.com/culture/story/20160819-the-21st-centurys-100-greatest-films) website, specifically from the [long list](https://www.bbc.com/culture/article/20160819-the-21st-centurys-100-greatest-films-who-voted) encompassing everyone who participated in a poll of 177 film critics, determining the best films of the 21st century.

To achieve this, I utilized Beautiful Soup and regular expressions for extracting pertinent information from the webpage. The outcome was the creation of a searchable database that effectively organizes data by film, director, and critic. A well-designed database schema facilitated this organization. Additionally, from a geocoding perspective, I generated a map using Mapbox to visually represent the dataset, emphasizing the countries of origin of the critics. 

Upon successfully formatting the initial page into a structured database, the project proceeded to enrich the dataset with supplementary information from another source. Specifically, I incorporated box office gross data from different countries, utilizing [Box Office Mojo](https://www.boxofficemojo.com/?ref_=bo_nb_tt_mojologo) for comprehensive worldwide box office statistics.

The encountered challenges can be summarized as follows:

1. Formulating a structured database by formatting the initial page.
2. Enhancing the dataset with additional relevant information from Box Office Mojo, considering potential disparities in movie availability between the BBC list and the secondary source.
3. Using Mapbox GL JS (JavaScript library/API) to create an interactive map that effectively conveyed the previously gathered information in a clear and easily comprehensible manner for the audience.