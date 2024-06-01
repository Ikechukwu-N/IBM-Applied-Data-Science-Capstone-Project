**Background**

SpaceX, a leader in the space industry, strives to make space travel affordable for everyone. Its accomplishments include sending spacecraft to the international space station, launching a satellite constellation that provides internet access and sending manned missions to space. SpaceX can do this because the rocket launches are relatively inexpensive ($62 million per launch) due to its novel reuse of the first stage of its Falcon 9 rocket. Other providers, which are not able to reuse the first stage, cost upwards of $165 million each. By determining if the first stage will land, we can determine the price of the launch. To do this, we can use public data and machine learning models to predict whether SpaceX – or a competing company – can reuse the first stage.

**Questions to be answered**
- How do variables such as payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?
- Does the rate of successful landings increase over the years?
- What is the best algorithm that can be used for binary classification in this case?

**Methodology**
1. Data collection methodology
-Using SpaceX Rest API
-Using Web Scrapping from Wikipedia
2. Performed data wrangling
-Filtering the data
-Dealing with missing values
-Using One Hot Encoding to prepare the data to a binary classification
3. Performed exploratory data analysis (EDA) using visualization and SQL
4. Performed interactive visual analytics using Folium and Plotly Dash
5. Performed predictive analysis using classification models
-Building, tuning and evaluation of classification models to ensure the best results
