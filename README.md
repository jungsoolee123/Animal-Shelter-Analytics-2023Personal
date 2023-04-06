### Analyze Animal Info in Austin Animcal Center
1.  CSV files
	- Intakes: Information about the intake cases in Austin Animal Center. Contain animal names, animal age, intake type, intake date&time, found location, etc.
	- Outcomes: Information about the intake cases in Austin Animal Center. Contain animal name, animal age, outcome type, outcome date&time, etc.
	- Stray Map: Informtaion about found location of animals.
	
2. Exploratory Data Analysis
https://public.tableau.com/views/AnimalIntakeAnalysis/AnimalTypeIntakeTypeIntakeCondition?:language=en-US&:display_count=n&:origin=viz_share_link
<div class='tableauPlaceholder' id='viz1680758390376' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnimalIntakeAnalysis&#47;AnimalTypeIntakeTypeIntakeCondition&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AnimalIntakeAnalysis&#47;AnimalTypeIntakeTypeIntakeCondition' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnimalIntakeAnalysis&#47;AnimalTypeIntakeTypeIntakeCondition&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1680758390376');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.minHeight='1750px';vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
	- Intakes_EDA: Explored Intakes data. Derived several insights such as intake type of aged animals, rate of returned animals, seasonality of adoption.
	- Outcomes_EDA: Explored Outcome data. Derived several insights such as outcome type of aged animals, rate of returned animals, seasonality of outcome.
	- Intakes_Outcomes_Combined: Merged intake and outcome datasets together using animal IDs and dates from each table.
	- Stray Map: Visualized a map using geocoding.
3.
	- Outcome type Prediction
	- Clustering

