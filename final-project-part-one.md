| [home page](./) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Summary

Giraffes, one of the most beautiful, yet underappreciated animals in the world. So elegant, tall, and handsome… It's almost like looking in the mirror! There’s a reason they have been my favorite animal for quite some time now, and I have been a giraffe for Halloween for 2 years in a row now, most likely going on to 3 this year.

As giraffes are becoming an increasingly endangered species, this project aims to visualize where the wild populations reside, as well as track the conservation efforts that different countries are making to potentially see the trend of their effects on the population downtrends. From 1985 to 2015, the giraffe population had fallen from about 155,000 to 98,000, a nearly 40% decline over 3 decades, and unfortunately also had gone extinct in at least 7 different countries. As a result of this rapid, widespread decline, in 2016, the International Union for Conservation of Nature (IUCN) reclassified giraffes from least concern to vulnerable (savegiraffesnow.org).

Giraffes had previously been considered one species, Giraffa camelopardalis, with 9 subspecies:
- angolensis
- giraffa
- peralta
- rothschildi
- antiquorum
- camelopardalis
- reticulata
- tippelskirchi
- thornicrofti

However, research published in the late 2010s demonstrated that they were actually 4 different species, meaning that how populations were reported on needed to change (3 are highly threatened):

- Northern giraffe
  - Kordofan, Nubian, and West African
- Reticulated giraffe
- Masai giraffe
  - Masai, Luangwa
- Southern giraffe
  - South African, Angolan

Source: savegiraffesnow.org


With all of this being said, keeping giraffe populations safe and out of harm’s way is crucial; the countries of Africa must minimize the factors that cause these, including habitat loss, poaching, and civil conflict. With a 19 to 22 month interbirth interval on average (San Diego Zoo Wildlife Alliance Library), their slow reproductive rate requires intense intentional care to ensure the populations thrive both in the wild and in captivity.


# Outline

## The Big Picture

Audience: African Policy Makers, NGOs, etc

To start, I would like to initially really emphasize the urgency of this heavy drop in giraffe population over the decades. This will be a fairly simple graphic with not too many points due to very limited data, but it will be enough to sell the urgency from the very beginning. I decided on using particularly endangered subspecies due to it being more accurate with regard to surveying methods. Green and blue are neutral colors that work well to separate, but now I’m considering yellow and light brown to have some type of theme going in the final version.

<img width="680" height="530" alt="Kordofan + Nubian Giraffes Sketch" src="https://github.com/user-attachments/assets/2e7cc55f-5339-42eb-b85b-ed52dc9e62bb" />\
*Potentially add in the West African giraffe subspecies to make it all of the Northern giraffe species


## Causes

Why is this happening? (Give a brief description for each, maybe add visuals)
(From: savegiraffesnow.org)
- Habitat Loss / Deforestation

<img width="762" height="661" alt="The Consequences of Deforestation in America Sketch" src="https://github.com/user-attachments/assets/07dd22a8-b719-4679-a85a-81dd0e41ab88" />\
This visual is sketched from one from: https://earth.org/nature-and-culture-at-risk-the-consequences-of-deforestation-in-africa/

- Poaching (Find poaching, poaching tourism, permits, enforcement data and maybe make a visualization)
- Civil Conflict
- Slow Reproductive Rate

## Conservation Efforts All Around

Moving from that, I can show the conservation efforts:

| Geographic Range of Giraffes in 2016 | Protected Area Percentage 2016 |
| :---: | :---: |
| <img width="370" height="311" alt="Giraffes Area in 2016 Sketch" src="https://github.com/user-attachments/assets/472da576-2990-4333-9460-c57adc2e80e5" /> | <img width="370" height="311" alt="Protected Area Percentage Sketch" src="https://github.com/user-attachments/assets/ff57e24c-3d81-4e5e-8ea4-f3dff528f6fe" /> |

Sources:\
https://www.iucnredlist.org/species/9194/136266699#population
https://data.worldbank.org/indicator/ER.LND.PTLD.ZS

The geographic range here can probably be improved. I’m not sure recognizing different species is necessary for making the point I am trying to make. I am considering, if I can figure it out, to add a giraffe pattern for the range if it makes it pop enough. Then, potentially layering the two visuals can be warranted.

Make note of the slight correlation between the protected areas and geographic ranges; Botswana, Namibia, Zambia, and Tanzania, all countries with 25%+ protected area in 2016, contain a majority of the geographic giraffe ranges. There is clearly something to be said about that, but I unfortunately do not have the time-series data to compare how the areas have changed over time, so any conclusions are very limited here. 

With that being said, the Southern Giraffe has nearly doubled in population in the last three decades (Giraffe Conservation Foundation), and with a population of over 52,000 in 2016, it is the largest among the 4 species, more than the other 3 combined. The South African giraffe subspecies, makes up about 39,000 of them (Giraffe Conservation Foundation), and it is estimated that over 60% (~24000) reside in South Africa (Deacon, F., & Tutchings, A., 2018). South Africa has 14.2% protected area, which falls on the lower end when compared to the larger surrounding countries. The conservational success comes from the population being spread across national parks, nature reserves, and privately owned game ranches; steady population growth across both private and state-managed land demonstrates that a hybrid system of public parks and private land ownership offers the most reliable path to long-term species recovery.

While South Africa’s conservational success relies on fenced, private property, Niger takes a different route to conservation. In 1995, the West African giraffe subspecies was nearly at extinction, with only 49 individual giraffes remaining (Save Giraffes Now). The Niger Government strictly began enforcing national anti-poaching legislation, while supporting public education campaigns, which resulted in only three cases of it between 2005 to 2009 (Suraud, J.-P., et al., 2012). 

Instead of relying on fenced reserves, Niger’s strategy centers on unfenced cohabitation, where remaining West African giraffes live entirely outside protected areas, sharing lands directly with local farming and herding communities. Supported by the government’s anti-poaching enforcement and community-led awareness programs, local residents became active guardians of the species; this also allowed close-range individual monitoring to study population dynamics with minimal flight response. The absence of local predators, in conjunction with this, led to an annual growth rate of 12-13% from 2005 to 2008, and proved that physical fencing was not an absolute necessity for population growth (Suraud, J.-P., et al., 2012). Today, this population of 49 has grown to about 600 giraffes (Save Giraffes Now).

Look into remaking this visual or something similar:\
https://www.researchgate.net/figure/The-West-African-giraffe-population-estimates-in-Niger-from-1996-to-2019-Note_fig2_378457493

~~After this, I can start building the population percentage disparity of each country, indicated by bar chart with a green if the change is positive, red if negative (Could also be a map, most will be red because so many are now 0)~~ - I don’t think I can find the country-specific data for this, and it may not be necessary in any case.

Different countries are clearly putting in varying amounts of effort, but it doesn’t have to be that way. South Africa and Niger provide two vastly differing approaches to conservation, and have been wildly successful, despite neither having a protected population over 20%. It simply comes down to the intention placed on conservation; you don’t have to protect more area, you just have to be intentional with giraffes. The countries and organizations of Africa must continue to put more effort into giraffe conservation to save these beautiful, unique animals.

Call to action: Don’t “wait and see.” Let’s be more intentional with our conservation efforts.


Additional Ideas:\
Splitting a map of all the subspecies and color code how endangered they are


# Method and Medium
I will be using Tableau for all of my visualizations and Shorthand in my final draft to put everything together. Some of my visualizations are already screenshots from Tableau, and I will likely be refining them even further for the final iteration of the project.


## References

WDR-Admin. “Giraffe Population Decline: A Data-Driven Timeline (1980–Present).” Save Giraffes Now, 8 July 2026, savegiraffesnow.org/giraffe-population-decline/.

San Diego Zoo Wildlife Alliance Library staff. “Libguides: Giraffes (Giraffa Spp.) Fact Sheet: Reproduction & Development.” Reproduction & Development - Giraffes (Giraffa Spp.) Fact Sheet - LibGuides at International Environment Library Consortium, ielc.libguides.com/sdzg/factsheets/giraffes/reproduction. Accessed 30 Sept. 2026.

“Conservation Status & Distribution Africa’s Giraffe Conservation Status.” Giraffe Conservation Foundation, giraffeconservation.org/wp-content/uploads/2016/09/Conservation-Status-Distribution-poster-2016-LR-c-GCF.pdf. Accessed 2 Oct. 2026.
Deacon, F., & Tutchings, A. (2018). "The South African giraffe Giraffa camelopardalis giraffa: a conservation success story." Oryx, Cambridge University Press, 52(4), 620–621. Accessed 2 Oct. 2026.

Suraud, J.-P., et al. “Higher than Expected Growth Rate of the Endangered West African Giraffe Giraffa Camelopardalis Peralta: A Successful Human–Wildlife Cohabitation: Oryx.” Cambridge Core, Cambridge University Press, 4 Oct. 2012, www.cambridge.org/core/journals/oryx/article/higher-than-expected-growth-rate-of-the-endangered-west-african-giraffe-giraffa-camelopardalis-peralta-a-successful-humanwildlife-cohabitation/73BF29285A33B20D210790ECC786D079.

## The Data

Giraffe Area Map: https://www.iucnredlist.org/species/9194/136266699#population<br>
This data presents all of the different giraffe subspecies based on the old identification under one species. I took this data and shifted the areas' names into the modern naming conventions of the four giraffe species and subspecies after 2018-2020. The data visualized is for the four species of giraffes based on where they were in 2016.<br><br>
Protected Area Percentage Map: https://data.worldbank.org/indicator/ER.LND.PTLD.ZS\<br>
I had initially taken the data from each country profile from
https://giraffeconservation.org/programs/giraffe-conservation-status-assessment/ 
To build my map, but there were a few gaps in the countries that the areas covered, so I figured it would be most effective to take from one more cohesive source. This would not only be one source of more countries (All of Africa), but also give me control over the particular year represented. My previous set was based on fragmented random years from around 2020 to 2025. I wanted to take the most recent year available in all of my countries, but decided on 2016 because it was a critical year for recognizing how impacted giraffes were, so I didn’t wanna misrepresent based on what changes were made in the decade since.


## AI acknowledgements
I used AI to brainstorm ideas for what direction to take in my final project, as well as for working with my data in tableau. I also used it to find some of my sources, particularly the academic literature.

<!--
> A project structure that outlines the major elements of your story.  Your Good Charts text talks about story structure in Chapter 8 - you should describe what you hope to achieve.  Make sure the outline is detailed enough that we can see how you anticipate your story unfolding.  You can incorporate your Story Arc from the in-class exercise along with your user stories and one sentence summary to make the topic even more clear. 

Text here...

## Initial sketches
> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  

Text here...

# The data
> A couple of paragraphs that document your data source(s), and an explanation of how you plan on using your data. 

Text here...

> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your Github repository, Box account or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available please talk to me first. 

| Name | URL | Description |
|------|-----|-------------|
|      |     |             |
|      |     |             |
|      |     |             |



--!>
