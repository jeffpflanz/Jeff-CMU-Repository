# Assignment 3 


The context of this graph can be found in this article: ["The Haters Are Losing The War On Kickers"](https://fivethirtyeight.com/wp-content/uploads/2016/01/morris-kicking-11.png?w=1150) (January 2016). 
The re-created data from the original 538 graph is downloadable below. 

![538 Kickers](https://fivethirtyeight.com/wp-content/uploads/2016/01/morris-kicking-11.png)

## Criticism 

The original graph is above. As I mentioned in my feedback, something just did not sit right with me - it felt like two graphs were being forced together. The line connecting the different data "year" points wasn't informative. And, as we learned in week 2, the title/subtitle did not add to the visualization - it was actually just repeating information found on the axes. 

My main task was to try to design/sketch wireframes that contained all of this information. I started with the simplest solution - two line graphs stacked - with year vs distance and year vs field goal simplicity. Then I tried *numerous* other graphs - area charts, line chart with two lines, grouped columns, something I learned was called "bullet bars." I kept running into the same problem - there wasn't an easy way to convey something like time (x-axis) versus two measures that had variance in a very short window - distance in yards (~36-38 range) and field goal percentage (78-86). After showing my roommates my options and running through the questions, they more or less reflected my concerns - that I was trying to force this information together and it might make sense to break it up. One even suggested simply taking out the connecting line out of the 538 graph and just leave the scatter plot. 

## Re-kick 

With that feedback, I tried to experiment a little with DataWrapper and Tableau to see if there were any visual approaches that I was missing. I took about an hour to experiment, but to no avail. In the end, I concluded simplicity is better - and will fully admit that this approach is not that much more informative than a simple table. I tried to incorporate the more nuanced things about data viz, like changing the chart title to reflect more of a story - and not just repeating the axis labels.

I  wanted to explore and highlight the apparent "jump" in distance that happened after the 2011 season (easy to see in 538 graph). To my disappointment, there is no information I could find that explained what caused this.  

<iframe title="Kickers Are Taking Longer Attempts Than Ever:&amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp;&quot;Today's kickers are bigger and stronger...&quot;&amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp;&amp;nbsp;" aria-label="Interactive line chart" id="datawrapper-chart-oxZb1" src="//datawrapper.dwcdn.net/oxZb1/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();</script>

<iframe title="&quot;...and increasingly more accurate&quot;&amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp; &amp;nbsp;&amp;nbsp;" aria-label="Interactive line chart" id="datawrapper-chart-j6pEU" src="//datawrapper.dwcdn.net/j6pEU/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();</script>

To critique my own output - I could not figure out how to change the text size of the subtitle on DataWrapper. Ideally I would've followed the title/subtile model of 538. And, maybe I'm missing something, but I could not figure out how to put labels on the axes. I would've labeled each of the y axes instead of putting the 'legend' at the top. I would appreciate any ideas/feedback on how I could have represented this data differently and better. 
