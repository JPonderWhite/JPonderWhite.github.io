# Ponder

![Its Me!](https://avatars0.githubusercontent.com/u/67644074?s=460&u=a44d92beca0056bee0babd61d9bb81d139f13d34&v=4)

[Where I currently Work](https://zoellner.cas.lehigh.edu/contact-us)

## About Me

Hey I'm Ponder. I currently work at Lehigh University as the Assistant Lighting Coordinator of the Zoellner Arts Center. I am mostly an itenerant lighting tech, but I am learning some coding, and trying to pick up some other skills while I can. 

I am taking this class to learn more about how data and information is processed and communicated. I have a strong backing in how narratives are communicated, but no first hand experience in how data is processed and passed around. I'd like to fix that, and am always looking for ways to obtain new skills and information.

# Tableau

<div class='tableauPlaceholder' id='viz1596153805920' style='position: relative'><noscript><a href='#'><img alt=' 'src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BZ&#47;BZW2KP9X2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;BZW2KP9X2' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BZ&#47;BZW2KP9X2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div><script type='text/javascript'> var divElement = document.getElementById('viz1596153805920'); var vizElement = divElement.getElementsByTagName('object')[0]; if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='977px';} var scriptElement = document.createElement('script'); scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

# ArcGIS Twitter Heatmap

This is a tweetmap taken on 7/21/2020 based around the searchterm #portland. [This article](https://www.opb.org/news/article/federal-law-enforcement-unmarked-vehicles-portland-protesters/) from Oregon Public Broadcasting had broken a week prior with the news of unidentified federal officers illegally arresting protesters the week prior, and the news that the program was being expanded to Kansas City and Chicago was just breaking. #portland was chosen instead of #portlandprotest to try and get more tweets about the federal officers and the program rather than tweets about the protests in general. 

<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="portland_twitter_7_21" src="//lu.maps.arcgis.com/apps/Embed/index.html?webmap=4650a4ead59e443a8c304705e2252f38&extent=-141.4781,13.8799,-37.9429,55.9487&zoom=true&previewImage=false&scale=true&disable_scroll=true&theme=light"></iframe></div>

You can clearly see the vast majority of the tweets are coming from Portland, and its direct surroundings. After that it holds to population pretty closely, with biases towards west coast cities (likely due to their physical proximity) and Washington, DC (due to politicians). There are a few surprises, but that seems to be mostly based on how Twitter determines location. I'm a bit surprised not to be seeing more activity from Kansas City and Chicago, seeing as they are the next targets, but perhaps a more recent heatmap taken a few days later would tell a different story.


# US Federal Reserve Charts
I'm experimenting with how different charts affect impact of data presented. So here is a quick series of charts based off of the same data from the Federal Reserve. The first two will show overall trends. The first measuring percentage of total wealth (in USD trillions), the second chart will be raw total wealth. The next series of charts will compare the earliest easily available data (1989) to the most recent (2020). All will be measured by Income Percentile. 


### Wealth over time
I don't think that the first chart is very impactful. It is very static and you can't see much change. The second chart I think works a lot better. You see how the total wealth change has affected things.


<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="Interactive line chart" id="datawrapper-chart-eybcj" src="https://datawrapper.dwcdn.net/eybcj/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="500"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>  

<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="Interactive line chart" id="datawrapper-chart-u98PQ" src="https://datawrapper.dwcdn.net/u98PQ/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="500"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>  


### Comparing 1989 to 2020
The two are pie charts. The only difference being that the first is in terms of % of total, while the second gives the relevant numbers. I'm honestly not sure which I think is more impactful. 


<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-rvAHM" src="https://datawrapper.dwcdn.net/rvAHM/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="342"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-4Uctf" src="https://datawrapper.dwcdn.net/4Uctf/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="342"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

This chart is a bar chart version of the above.

<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-LcfQg" src="https://datawrapper.dwcdn.net/LcfQg/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="300"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

This separates the bars by income. I'm not sure which I prefer.

<iframe title="Distribution of US Household Wealth by Income Percentile" aria-label="chart" id="datawrapper-chart-n8eRo" src="https://datawrapper.dwcdn.net/n8eRo/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>



# Lehigh Enrollment 2017
This is series of pie chart I made for my Data Storytelling class. They show undergraduate enrollment at the various colleges at Lehigh University, first by a gender breakdown, and then by total enrollment. They show that the College of Arts and Sciences is the largest, with the College of Engineering, and the College of Buisness being the next most populous in second and third place respectively.

<iframe title="Lehigh Enrollment 2017" aria-label="chart" id="datawrapper-chart-ukKJG" src="https://datawrapper.dwcdn.net/ukKJG/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="370"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>


# Lehigh Enrollment 2011-2020
This line chart was also made for Data Storytelling. It tracks the enrollment over the past decade. One interesting note is that while 2017 saw the largest enrollment being in the College of Arts and Sciences, while this chart shows the College of Engineering being the most populous. I'm not quite sure what the disconnect is. My guess is either bad data, or a mismatch between counting grad students and not.

<iframe title="Lehigh Enrollment 2011-2020" aria-label="Interactive line chart" id="datawrapper-chart-iB8zk" src="https://datawrapper.dwcdn.net/iB8zk/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>
