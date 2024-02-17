Restaurant Review Analysis - OpenTable Suggested Award Winning Restaurants
Project's Title
OpenTable Review Insighter: Unveiling the Dining Experience of Award-Winning Restaurants.

Project Description
This project delves into the world of culinary reviews, dissecting customer feedback from OpenTable's award-winning restaurants. Utilizing Python for data scraping and sentiment analysis, and Tableau for vivid visualizations, the aim was to uncover the narrative behind the ratings. Technologies like Selenium, BeautifulSoup, Pandas, and NLTK were pivotal in translating raw data into meaningful insights. Challenges included the intricate data preprocessing and the nuanced interpretation of sentiment scores. Future enhancements may include real-time analysis and broader data sources.

Table of Contents (Optional)
Project's Title
Project Description
Installation
Usage
Visuals
Contributing
License
Contact

How to Install and Run the Project
This section provides a guide to set up the project environment:

Clone the repo: git clone https://github.com/yourusername/OpenTable-Review-Insighter.git
Install required packages: pip install -r requirements.txt
Run the scraper: python scraper.py
Execute the data processor: python data_processor.py
Perform sentiment analysis: python sentiment_analysis.py
Aspect analysis: python aspect_analysis.py
Launch Tableau Desktop and open the .twbx file included in the repo.
How to Use the Project
To utilize this project:

Review the code for understanding the data extraction and processing phases.
Explore the CSV files to see the raw and processed data.
Open the Tableau workbook to interact with the visualizations.
Embed Tableau visuals into web pages using the links provided in the 'visuals' folder.
Visuals

Interactive dashboards provide a snapshot of the analysis. Find the embedded Tableau links below:

Rating Overview Dashboard 
<div class='tableauPlaceholder' id='viz1708133450930' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Op&#47;OpenTableRatingOverview&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OpenTableRatingOverview&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Op&#47;OpenTableRatingOverview&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1708133450930');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='977px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

Sentiment Analysis Over Time
<div class='tableauPlaceholder' id='viz1708133542516' style='position: relative'><noscript><a href='https:&#47;&#47;github.com&#47;Tushar-Pingle&#47;OpenTable-Review-Analysis'><img alt='Comparing trends of rating and sentiment score ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Op&#47;OpenTableRatingOverview_17071810318720&#47;Comparingtrendsofratingandsentimentscore&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='OpenTableRatingOverview_17071810318720&#47;Comparingtrendsofratingandsentimentscore' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Op&#47;OpenTableRatingOverview_17071810318720&#47;Comparingtrendsofratingandsentimentscore&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1708133542516');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1727px';vizElement.style.height='923px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1727px';vizElement.style.height='923px';} else { vizElement.style.width='100%';vizElement.style.height='1027px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


Aspect Analysis Visualization

<div class='tableauPlaceholder' id='viz1708133566751' style='position: relative'><noscript><a href='https:&#47;&#47;github.com&#47;Tushar-Pingle&#47;OpenTable-Review-Analysis'><img alt='Aspect Analysis ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;AspectAnalysis_&#47;AspectAnalysis&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AspectAnalysis_&#47;AspectAnalysis' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;AspectAnalysis_&#47;AspectAnalysis&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1708133566751');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1177px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
