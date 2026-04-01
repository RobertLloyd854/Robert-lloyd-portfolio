| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and you attempted to show or do different._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization
Here is the chart I chose for this critique with its corresponding article also linked below 

<img width="634" height="636" alt="Screenshot 2026-04-01 at 10 26 02 AM" src="https://github.com/user-attachments/assets/ae28bd6b-ec5f-42c4-b2e1-e49bf8b08d6a" />

“How Cost Effective Is Your High Protein Diet.” The Bodybuilding Dietitians, https://www.thebodybuildingdietitians.com/blog/how-cost-effective-is-your-high-protein-diet

Article: https://lifehacker.com/the-cheapest-ways-to-get-your-protein-right-now

I chose this visualization because the topic interests me and I found the article very informative. Over the last few years I have made the concious decision to eat more protein, but quickly found that it would be a relatively expensive endeavor. Therefore, I am interested in what everyday food products are the most cost-effective way to get my daily protein intake. Additionally, I found the chart a bit cluttered and so I thought there were changes that could be made to improve its readability. 


## Step two: the critique
I really enjoyed the Stephen Few approach to critiquing visualizations; I found it focussed my eye on aspects of the graph I otherwise wouldn't have noticed. 

Some things I like about the visualization: Something I liked about the graph was the use of pictures so that it was clear what specific product each data point represents. Additionally, I thought the title and axises were very clear. 

Some things I didn't like about the visualization: Something that didn't work so well is that chicken breast was all the way to the right (the smallest bar) even though it represents the most cost-effective measure. At first glance, it being the smallest bar makes it seem like it is the least cost-effective. Also another critique is that there is no color differentiation amongst the bars so your eye isn't drawn instantly to one/a group of data point/s. Additionally, the amount of calories in these foods does not have anything to do with the cost-effectiveness of the product so it will likely distract the reader from the true purpose of the visualization. Instead of calling out the calorie amount I think it would be far more valuable to call out the cost per 30g of protein for each product, so that people can get an actual dollar amount, especially for the most cost-effective options like chicken breast and WPI.   

Preliminary ideas of what to focus on in my redesign: I will focus on a way to emphasize the "small" nature of the most cost-effective food options, so that they aren't hidden by the opther data points. Also I want to call out specific cost data points so that the chart has a larger impact. Something that could be cool is to compare all of these foods to the average cost per 30g of protein and have line vertical line in a horizontal bar chart to diffentiate which foods are above and below average. 

## Step three: Sketch a solution

I made my first redesign on paper and went through several iterations based on my intuition about which versions were the clearest and best told my story—specifically emphasizing the most cost-effective foods in terms of protein. I then transferred my design to an Excel file (linked below). My initial idea was to group foods into three categories: most cost-effective, average, and least cost-effective, and to color-code each group (as shown below with green, yellow, and red). I chose green for the most cost-effective foods to signal that these are the “best” options. I also decided on a horizontal bar chart so that viewers’ eyes are immediately drawn to the top, where the foods I want to highlight are placed. Similarly, I tried to use a faded out red color for the least cost-effective foods but I think it came out a little awkward and unappealing in the first go around. 

<img width="733" height="487" alt="Screenshot 2026-04-01 at 10 44 05 AM" src="https://github.com/user-attachments/assets/c3dd21d6-51b9-4455-a2e7-dad096ef92e0" />

## Step four: Test the solution
In class I tested my graph on a group of 3 other students and asked the following questions. 
- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 
The initial feedback was positive. At a high level, my classmates understood what the graph was meant to convey and even commented on the most cost-effective foods—many were surprised to see chicken, skim milk, and peanuts at the top. Most of the constructive feedback came after I asked, “Is there anything you find surprising or confusing?” The most common issue people raised was the color scheme. Without a clear key, it was difficult to understand what the colors represented, and the meaning wasn’t immediately obvious without additional context. One student also pointed out that the transparency of the red (least cost-effective) bars actually drew her attention to those items, which had the opposite effect of what I intended.
One student recommended that I color the most cost-effective products green and then grey out the other ones in order to effectively call attention to the desired data points. 
Another student recommend that I do a golor gradient where the more cost-effective foods are darker and the less cost-effective foods are lighter. 
When asked, Is there anything you would change or do differently? One student said that she would include a horizontal line that represents the average, so that someone reading the chart can very quickly discern whether or not a specific product is above or below the average cost per 30g of protein in the dataset. 
Similarly, a different student said that it would be very valuable to include callouts outside the bars of each food's specific cost, so that people aren't guessing based on the end of the bar. This way people are more likely to take a figure, that can be easily referenced.  


## Step five: build the solution

Design changes implemented: After consulting with my class mates I implemented their recommendations in Tableau. The first decision I made was to fix the colors. I decided to use the gradient, single color, approach to highlight the most cost-effective foods. I used a reversed continuous color gradient so the most cost-effective foods were highlighted with a dark saturated color and the more expensive ones were "faded out" (represented using a lighter shade). 
Next I added dollar amounts outside each bar and added dollar signs to the axis to make the unit of measurement more clear. 
Lastly I added a horizontal line representing the average cost/30g of protein that served as a reference line. I struggled a bit with this as it was difficult to control where the line's label would go. At first it was at the bottom of the line, conflicting with other bars and labels. 

Thoughts on the critique process: I like the iterative nature 


Here is my final product!
<div class='tableauPlaceholder' id='viz1774972079948' style='position: relative'><noscript><a href='#'><img alt='&lt;Protein Per Dollar: Ranking Foods by Cost Efficiency &gt; ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProteinData&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ProteinData&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProteinData&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1774972079948');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


## References
“How Cost Effective Is Your High Protein Diet.” The Bodybuilding Dietitians, https://www.thebodybuildingdietitians.com/blog/how-cost-effective-is-your-high-protein-diet

Article: https://lifehacker.com/the-cheapest-ways-to-get-your-protein-right-now

## AI acknowledgements
I used AI in the sketch process to see if it could come up with a better visualization than myself. I ended up just going with Excel as it did not produce a much better version of the original. 

Additionally, I used AI to help with some of the tableau software commands (as this tool is still relatively new for me). 

