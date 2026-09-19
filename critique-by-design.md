| [home page](./) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Turkey Likes Birds... Who Would Have Thought?!

<!--
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._
-->

## Step one: the visualization

<!--
_Include link to the original data visualization (or screenshot - make sure to correctly cite your sources, etc.).  Include paragraph or two on why you selected this particular data visualization.  For obvious reasons, the data visualization you select should come from a publicly accessible source._
-->

The visualization I chose came from: https://makeovermonday.vercel.app/dataset/2025-week-14-pet-ownership

I chose this visualization because I had wanted to work with something animal-related, and none of the others I had found piqued my interest. This visual had an immediately interesting and unique design, and I didn't see too much wrong at first glance; it was surprisingly effective at conveying what it intended. What stood out to me was the overall completeness of the picture it painted. It essentially gives the percentage of people living with dogs, cats, fish, or birds in particular countries/cities in 2016. Starting in the middle, the little animal drawings and color-coding make it fairly straightforward to interpret what it is communicating and to go around country by country (Or skip to whichever one you are interested in). While the colors are not perfect, they are not too distracting, the pet shapes themselves are simple but appealing, and despite all of the numbers, it doesn't seem too crowded. 


## Step two: the critique
<!--
_Don't forget to complete the Google Form found on the assignment page.  You can summarize your thoughts here._
-->

With that being said, it is not perfect, especially the longer you look at it. There is no easy way to compare country to country, at least some light math is needed. Depending on where you're looking, the eye travel distance might be higher, especially when comparing multiple pets. For example, comparing Poland and Germany, which should be right next to each other, requires alternating from the left to right side, which is disorienting and easy to be bothered by. The visualization is great to note what the values are for one specific country that you care about, but the moment it becomes a comparison then it falls apart.

Additionally, while alphabetical order makes a particular country easy to find by following the circle, it also makes it geographically challenging to get an immediate reference for what other included-in-the-data countries are near it. No matter how geographically well-versed a reader is, there is an extra burden placed on them. This is my most important critique, and the primary reason that I even decided to look into rebuilding this visualization. While I've said the alphabetical order is helpful, I believe that separating by region and making subsections would have been more generally insightful. If all of the European countries (which there are ~11 of) were on one side, then organized in a way that grouped adjacent countries together, this would already be a significantly more useful visual. While it may trade the initial speed in finding the desired country, it eliminates the eye travel for relevant comparisons. There are more directions that grouping could take, but given the sparse nature of the non-European data, it is not necessary to go into detail. 

Light math is also necessary for comparing countries, there is no easy visual comparison, but it is understandable considering how cluttered it would otherwise get. If that was the only goal, it would be useful to use something like split bars.

There are also a few small critiques that can be made:
- Two blues are used by the pet categories. While this works technically, it is far from ideal.
- The yellow shade used is just slightly too light for comfort, it should be at the very least darkened.
- There is a random city, Hong Kong, in a set of countries.

## Step three: Sketch a solution

<img width="731" height="599" alt="International Pets Sketch" src="https://github.com/user-attachments/assets/ade3b062-5753-44c3-adb8-033395c7c946" />

My sketch was done very roughly to show the general idea, and doesn't include most of the country-specific data values on the side.

## Step four: Test the solution

<!--
_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._
-->

Because my sketch was not "finished" I gave a description to my critique group prior to asking any questions and discussing with them.

Questions that I asked: 
- Is there anything you find confusing or surprising?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?

Results: 

| Question | Interview 1 | Interview 2 | Interview 3 |
| --- | --- | --- | --- |
| **Is there anything you find confusing or surprising?** | I was surprised that each country is filled with only one solid color. Is there any way to display multiple colors, or like mixing them together to show pet diversity? | Why is Russia so green? The strong color coding makes it look like everyone there lives with a cat... | I'm surprised by how it looks when a single top pet defines the whole nation, missing the breakdown of other pets. |
| **Who do you think is the intended audience for this?** | People who are interested in learning about different global cultures and general animal or pet enthusiasts. | Vets and pet professionals trying to understand the market's trends. | People traveling and curious readers looking for quick culture trivia. |
| **Is there anything you would change or do differently?** | Use a color gradient to represent how heavily people live with dogs vs. cats. Also consider cutting the map down (Maybe to just Europe?). | Remove countries without data to make space. | Watch out for people who have red and green colorblindness. |

Synthesis: 

Everybody in the group thought that the coloring oversimplified the data, which I do not disagree with. However, my sketch did not do a good job representing how each country was going to display the numbers near it in a similar way to the original visualization. This was partially due to not wanting to add too much clutter, but also not wanting to remove parts of the map and leaving the map feeling incomplete. Removing the space without data was a common suggestion made by my peers, and I am in total agreement, but going the step further and just having it be Europe is even more effective. With this, there is less to worry about in terms of placement and feeling of clutter. Another way to help with the solid coloring is having a gradient to at least be able to compare the relative max values for each country with the same top pet.

Something that I had forgotten to consider was the red and green color combination. As the two most recurring colors in the sketch, it would be difficult for those with red/green colorblindness to tell cat countries apart from dog countries.

There were multiple interesting intended audiences named. I would agree with most of them, however I'm not entirely sure how to go about catering to their specific needs.

<!--
_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._
-->

## Step five: build the solution

<!--
_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._
-->

<iframe 
  src="https://public.tableau.com/views/TopPetsinEurope2016/Sheet1?:showVizHome=no&:embed=true" 
  width="100%" 
  height="650" 
  style="border: none;">
</iframe>


My final version failed to incorporate many of the crucial aspects that I wanted to incorporate, and ended up rather simple. It tells the story of what each country's top pet is, with the interesting standout from Turkey as the only country that has birds as the top pet. I tried incorporating the gradient, but for some reason Tableau was only giving me the option of either the top pet color or top pet percentage gradient, rather than using the top pet percentage as the value for the gradient of the particular top pet. I also was not sure how to even begin tackling the beast of including all 4 of the individual pet values and symbols (in an appropriate region) for each country. 

While my new visualization tells a story, it doesn't nearly as deeply explore the story that I intended for it to tell. I'm glad that the map gives a visualization of where what countries are in reference to each other. Also, cutting non-European countries ended up being great for having attention in one place, but I believe the data is a tad too limited to make an effective full story; too many countries are greyed out.

## References
“Man’s Best Friend: Global Pet Ownership and Feeding Trends.” NIQ, 22 Nov. 2016, nielseniq.com/global/en/insights/report/2016/mans-best-friend-global-pet-ownership-and-feeding-trends/. 

## AI acknowledgements
I used Gemini to help me figure out how to navigate Tableau's basic functions because I am still fairly new to it.
