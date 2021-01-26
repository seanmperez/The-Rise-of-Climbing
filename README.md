# Climbing Visualization of 8a.nu Users with Python, SQL, and Tableau

## Introduction
Climbing has transformed from an off-the-beaten-path lifestyle, to a competitive sport being featured in the 2021 olympics. Unlike a lot of other popular sports such as basketball and football, data is sparse when it comes to climbing!

## The Data¶
Luckily, kaggle has a great dataset of users from the world's largest rock climbing logbook, 8a.nu. The dataset was collected on 9/13/2017 and can be found on kaggle https://www.kaggle.com/dcohen21/8anu-climbing-logbook. The data is held in a sqlite database.

## Questions
#### 1. *What yearly trends do we see in the popularity of climbing?*


#### 2. *Who is the average climber?*

## Results
![Tableau Viz]
(<div class='tableauPlaceholder' id='viz1611621388740' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cl&#47;ClimbingGrowth&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ClimbingGrowth&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cl&#47;ClimbingGrowth&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1611621388740');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='420px';vizElement.style.maxWidth='650px';vizElement.style.width='100%';vizElement.style.minHeight='587px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='777px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>)

Check out my [Dashboard](https://public.tableau.com/profile/sean.perez#!/vizhome/ClimbingGrowth/Dashboard1) or the jupyter notebook to view in depth results.


## Insights

1. The vast majority of users on 8a.nu (86%) are male.
2. Females are, on average, 27 lbs lighter and 5 inches short than males.
3. Males tend to climb a few grades above females in both bouldering and routes (possibly due to user bias).
4. Most astonishingly, we can see the average user on 8a.nu is quite strong! The average max boulder climbed was V6-V8/9, and the average max route climbed was 5.12a-c, both of which are considered at the advance to expert level!

Checkout https://www.guidedolomiti.com/en/rock-climbing-grades/ for more details.

## Future Plans
There are quite a few improvements that can be gleaned from the modern climber that weren't done in this simple analysis. A few more metrics that would be great to calculate in the 8a.nu dataset include:

1. How climbers are improving over time.
2. A world map to show where climbers are.

More importantly, our analysis showed that 8a.nu user aren't representative of many new climbers in general! The users on this site are advanced to expert climbers. If I can find a dataset that is able to capture the more modern climbers that are both new and climb mostly indoors, I'm sure the data would tell a very different story.


Contributers:
Sean Perez (Data analytics, concept)
Jane Choi (Graphic design/UX, concept)