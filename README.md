# Highlighting stories of Berkeley Japanese Americans incarcerated during World War II. 

### This project was completed as part of the Lede Program. See the resulting project page [here](https://jamesjwilde2.github.io/Incarcerated-Japanese-Americans-from-Berkeley/).

The goal of this project was to highlight some of the stories contained within the Berkeley Historical Society and Museum's [exhibit](https://berkhistory.org/2024/08/23/roots-removal-and-resistance-japanese-americans-in-berkeley/) on Japanese Americans and their "Here Lived" [map](https://berkhistory.org/japanese-americans-in-berkeley-here-lived-map/). 


## Data collection: 
I pulled data from the "Here Lived" [database](https://docs.google.com/spreadsheets/d/1B46EULTl5qBbcp0GHv4cIY5Wwf6Sa7_mPx9khRsE6AQ/edit?gid=1927072334#gid=1927072334) created by Michael Several, which was also [mapped](https://berkhistory.org/japanese-americans-in-berkeley-here-lived-map/) by Elina Juvonen. 

I also used multiple images and sources linked from the Here Lived database, including sources from [Topaz Stories](https://topazstories.com/letter-to-a-nisei-son) and [Densho](https://encyclopedia.densho.org/Yoshiko_Uchida/#Books_for_Children_and_Young_Adults_by_Yoshiko_Uchida).

I used pandas, Datawrapper, and QGIS to geocode the addresses of each person in the database and then create a map that I customized using Illustrator. 

## Analysis:
I analyzed the data using a Python notebook available in this repo. For now, I mostly just needed to geocode each address, which I then used to map the data using Datawrapper and Adobe Illustrator. 

I then visualized the maps using a scrollytelling template, which I customized for this project.

## What I learned:
The bulk of the work for this project came in creating the visuals and customizing the html, css, and Javascript to get the scrollytelling product to work as I wanted it to.


## Future wish list:
There’s a lot I would love to add to this project:
* Making the scrollytelling design responsive for mobole.
* Updating the scrollytelling to use ai2html to again make the webpage more responsive and friendly to different screen sizes.
* Expanding on the writing and reporting of the story, which is currently pretty light.
* Integrating some of the pandas data analysis I did into the story (looking at things like years released, camps sent to, occupations, etc.). I would love to add some additional charts and graphics to the lower half of the story.
* Adding additional stories I found to the page.

Hopefully, updates will be coming soon!
