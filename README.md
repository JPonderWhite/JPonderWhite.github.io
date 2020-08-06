# Ponder

![Its Me!](https://avatars0.githubusercontent.com/u/67644074?s=460&u=a44d92beca0056bee0babd61d9bb81d139f13d34&v=4)

[Where I currently Work](https://zoellner.cas.lehigh.edu/contact-us)

## About Me

Hey I'm Ponder. I currently work at Lehigh University in the Zoellner Arts Center. I am mostly an itinerant lighting tech, but I am learning some coding, and trying to pick up some other skills while I can. 

I took a Data Storytelling class to learn more about how data and information is processed and communicated. I have a strong backing in how narratives are communicated, but had no first hand experience in how data is processed and passed around. I wanted to fix that, and am always looking for ways to obtain new skills and information, so the class seemed like an easy choice. This is a portfolio of some of the work I did.

# Twitter Heatmaps

## #portland with ArcGIS

This is a tweetmap taken on 7/21/2020 based around the searchterm #portland, and created with ArcGIS. [This article](https://www.opb.org/news/article/federal-law-enforcement-unmarked-vehicles-portland-protesters/) from Oregon Public Broadcasting had broken a few days prior with the news of unidentified federal officers illegally arresting protesters the week prior, and the news that the program was being expanded to Kansas City and Chicago was just breaking. #portland was chosen instead of #portlandprotest to try and get more tweets about the federal officers and the program rather than tweets about the protests in general. 

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="portland_twitter_7_21" src="//lu.maps.arcgis.com/apps/Embed/index.html?webmap=4650a4ead59e443a8c304705e2252f38&extent=-141.4781,13.8799,-37.9429,55.9487&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>

You can clearly see the vast majority of the tweets are coming from Portland, and its direct surroundings. After that it holds to population pretty closely, with biases towards west coast cities (likely due to their physical proximity) and Washington, DC (due to politicians). There are a few surprises, but that seems to be mostly based on how Twitter determines location. I'm a bit surprised not to be seeing more activity from Kansas City and Chicago, seeing as they had just been deemed the next targets, but perhaps a heatmap taken a few days later would tell a different story.


## #portland Maps in Tableau

This was made as a followup to my previous #portland map and data, this time using Tableau to display the information. I wanted to see how the trend had evolved over time as the situation had continued to develop. The first map is from 7/21, shortly after [the OPB article](https://www.opb.org/news/article/federal-law-enforcement-unmarked-vehicles-portland-protesters/) broke. The second is from 7/30, the day before federal agents were ordered to pull back. 

<div class='tableauPlaceholder' id='viz1596288285969' style='position: relative'><noscript><a href='#'><img alt=' 'src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Po&#47;PortlandProtests&#47;Story1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /><param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='PortlandProtests&#47;Story1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Po&#47;PortlandProtests&#47;Story1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'> var divElement = document.getElementById('viz1596288285969'); var vizElement = divElement.getElementsByTagName('object')[0]; vizElement.style.width='1016px';vizElement.style.height='991px'; var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>
  
  
I talked about the first map in my first rendition of it in ArcGIS, but it unsurprisingly shows most of the tweets coming from the Portland area with less people talking about it the further you get from Portland, adjusting for population, with a bias to the west coast cities and Washington, DC. The second map shows a greater concentration of Portlanders using the #portland, while less of the country does. The greatest decrease has been in Massachusettes, but the numbers both before and after are pretty small, so I do not think it indicative of anything in particular. That in of itself is worthy of note, people across the nation are still discussing what is going on in Portland. The story hasn't gone away. I'll be interested to keep checking in on it in a few more days, now that the Agents have withdrawn and the protests have become peaceful once more. Both tweets, and number of people attending the protests.

  
# Display experiments with US Federal Reserve Data

## US Federal Reserve Data with Datawrapper
I was experimenting with how different charts affect the impact of the data presented. So here is a quick series of charts, using Datawrapper, based off of the same data from the Federal Reserve. The first two will show overall trends. The first measuring percentage of total wealth (in USD trillions), the second chart will be raw total wealth. The next series of charts will compare the earliest easily available data (1989) to the most recent (2020). All will be measured by Income Percentile. It is important to note that the relative value of a dollar is not at all taken into account for any of these charts or data. A more thorough analysis of wealth over time would account for inflation and purchasing power.


### Wealth over time
I don't think that the first chart is very impactful. It is very static and you can't see much change. The second chart I think works a lot better. You see how the total wealth change has affected things.


<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="Interactive line chart" id="datawrapper-chart-eybcj" src="https://datawrapper.dwcdn.net/eybcj/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="500"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>  

As I said, this is a pretty uninteresting chart. Its mostly flat with very narrow trends over time. Perhaps the most interesting bit is the 2008 financial crisis, where despite everyone losing money, the top 20% of earners end up 'losing' enough more to take a hit in the percentage, but bounce back quicker than the lower 80%.

<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="Interactive line chart" id="datawrapper-chart-u98PQ" src="https://datawrapper.dwcdn.net/u98PQ/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="500"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>  

I think this is the most impactful chart of the whole lot, it does track wealth over time, instead of just relying on the percentages, and it is pretty shocking to see the differences.

### Comparing 1989 to 2020
These are two sets of charts, starting with pie graphs, then line graphs. The only difference being that the first is in terms of % of total, while the second gives the relevant numbers. 1989 and 2020 were chosen as the oldest and most recent data available from the federal reserve. The affect of the ongoing Pandemic has had some shocking effects on the economy, but the overall trend still holds. 


<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-rvAHM" src="https://datawrapper.dwcdn.net/rvAHM/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="342"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

I think this is the better of the two pie charts, which was a bit surprising to me, given how little I liked the percentage line graph. But in this case, percentages play to the pie graphs strengths. You can also see pretty easily how wealth has continued to accumulate at the top, as the wedge representing the top has grown, squeezing the lower earners even smaller.

<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-4Uctf" src="https://datawrapper.dwcdn.net/4Uctf/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="342"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

The image is the exact same as the first chart, but I like the numbers less. They lack context without showing the growth over time, and don't really seem to match or matter as much. I think I'll save pie graphs for percents of the whole unless I have a really good reason not to. 

Now the bar charts.

<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-LcfQg" src="https://datawrapper.dwcdn.net/LcfQg/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="300"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

This is a personal aestetic thing, but I really don't like the style of the above chart in general, and I don't think it works very well here. There are too many things contrasting all at once and not enough clarity. 

<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-n8eRo" src="https://datawrapper.dwcdn.net/n8eRo/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

This is slightly better, but also suffers from the same problem as above. Yes there is more money in 2020, but it is difficult to compare those values to the other earning groups within that year. I don't think that either of these bar charts do any good frankly. 

## US Federal Reserve Data with Tableau

This is mostly a revist of what I felt was the most impactful chart that I made before, but with Tableau instead of Datawrapper. It is harder to make the charts, but much more customizable. In this case you can toggle on and off different income levels, so that you can make what comparisons you want to. These charts show total wealth (in US $ trillions) by Income Percentile over time from 1989 to the first quarter of 2020. This data was provided by the Federal Reserve. The first chart defaults to showing all income levels over time. The second chart compares the wealth of the top 1% of earners to the bottom 60%.

<div class='tableauPlaceholder' id='viz1596153805920' style='position: relative'><noscript><a href='#'><img alt=' 'src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BZ&#47;BZW2KP9X2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /><param name='embed_code_version' value='3' /><param name='path' value='shared&#47;BZW2KP9X2'/><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BZ&#47;BZW2KP9X2&#47;1.png' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div><script type='text/javascript'> var divElement = document.getElementById('viz1596153805920'); var vizElement = divElement.getElementsByTagName('object')[0]; if (divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if (divElement.offsetWidth > 500) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='977px';} var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>
  
  
The second chart is the most impactful to me. You can clearly see the (relatively) recent explosion of wealth among the top single percentile of earners. From controlling slightly less than the bottom 60%, still a massive accumulation, to now being worth close to double. This means that the top roughly 3 million people controll more than double the wealth of the bottom 180,000,000 people. The 2nd quarter of 2020 reports were just released, and I'm interested to see how the mass unemployment caused by COVID-19 will contribute to this horrific disparity.
  
  
# Google Tour to the Star of Bethlehem

A Google Tour I did with some 360 videos. The lockdown was getting to me so I did this one about getting out of the apt to a place with a view.

<iframe width="100%" height="480px" src="https://poly.google.com/view/dDKCUJHeLet/embed?chrome=min" frameborder="0" style="border:none;" allowvr="yes" allow="vr; xr; accelerometer; magnetometer; gyroscope; autoplay;" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel="" ></iframe>

The only analysis I can make is that it is really good to get outside whenever you can.

# Lehigh Enrollment 2017
These pie charts show undergraduate enrollment at the various colleges at Lehigh University, first by a gender breakdown, and then by total enrollment. They show that the College of Arts and Sciences is the largest, with the College of Engineering, and the College of Buisness being the next most populous in second and third place respectively.

<iframe title="Lehigh Enrollment 2017" aria-label="chart" id="datawrapper-chart-ukKJG" src="https://datawrapper.dwcdn.net/ukKJG/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="370"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


# Lehigh Enrollment 2011-2020
This line chart tracks the enrollment at Lehigh over the past decade. One interesting note is that while 2017 saw the largest enrollment being in the College of Arts and Sciences, while this chart shows the College of Engineering being the most populous. I'm not quite sure what the disconnect is. My guess is either bad data, or a mismatch between counting grad students and not.

<iframe title="Lehigh Enrollment 2011-2020" aria-label="Interactive line chart" id="datawrapper-chart-iB8zk" src="https://datawrapper.dwcdn.net/iB8zk/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>
