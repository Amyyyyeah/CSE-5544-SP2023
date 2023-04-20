# Final Project | CSE 5544 (SP2023) | Well-being AS
Factors Analysis Contributing to Well-being Across Countries

# Overview
## Dataset

We used OECD Better Life Index dataset. The OECD Better Life Index is a dataset that allows users to compare countries' performance in various areas of well-being, such as education, income, and health. The data is sourced from various reputable international organizations and is publicly available on the OECD website.
```shell
https://www.oecdbetterlifeindex.org/#/11111111111
```
## User's guide how to use our project

The users of the visualization of the OECD Better Life Index data can be varied, depending on the context and purpose of the visualization. However, the target audience generally includes policymakers, researchers, analysts, educators, and the general public who are interested in comparing well-being indicators and outcomes across different countries. The visualization aims to provide a user-friendly and interactive tool for exploring the data and understanding how different countries perform in different aspects of well-being, such as education, health, environment, and more.

The main deliverables of this project are diverse visualizations that provide a comprehensive and comparative view of the well-being of populations across different countries. The visualizations include:
    
    * World map that shows the Life satisfaction index for various countries with a user-interface design
    
    * Stacked bar plot that depicts the correlation between Education Attainment and Years in Education Index for various countries, along with a user-friendly interface design.
    
    * Heatmap that represents water quality and air pollution index values for different countries or regions, with a user-interface design.
    
    * Plot chart that shows the average income and economic freedom and quality of life factors comparing the top and bottom earners

We then interpret the visualization results to explore insight in the dataset. Based on the research questions, we can derive research findings from each visualization. For example, we can find out through visualization whether economic freedom and quality of life factors are closely related to social status, and whether there is a difference between the top earners and the bottom earners in economic freedom and quality of life factors. 

Especially, the project can contribute to international society by discovering best practices and improvements for various well-being index factors and thus providing suggestions that can promote learning and collaboration between countries.

## Visualization 1
World map that shows the Life satisfaction index for various countries with a user-interface design

### Data & Tools
```shell
- Tools = Tableau
- Code = Vis1.twb
- Proceeded Data = data.xlsx
```
<img src="https://github.com/Amyyyyeah/CSE-5544-SP2023/blob/main/fig1_1.jpeg" width="700px" height="500px" title="server result2" alt="server2"></img><br/>
* Description of how the completed project corresponds to the proposal
    - To provide the user-friendly interface design, we created a world map. The countries colored as blue and red have higer and lower Life satisfaction index, respectively.
    - We added filters for other social factors to investigate relationships between the factors and Life satisfaction index. The filters can simultaneously display the countries within filtered values (range) and their satisfaction index. 
    - We can find which social factors are highly related to the Life satisfaction index.

## Visualization 2
Stacked bar plot that depicts the correlation between Education Attainment and Years in Education Index for various countries, along with a user-friendly interface design.

### Data & Tools
```shell
- Tools = Tableau
- Code = Vis2.twvb
- Proceeded Data = Vis2.xlsx
```
<img src="https://github.com/Amyyyyeah/CSE-5544-SP2023/blob/main/fig2_1.jpeg" width="650px" height="530px" title="server result2" alt="server2"></img><br/>
* Description of how the completed project corresponds to the proposal
    - To achieve a user-friendly design, we created a map graph that displays the education attainment and duration of education for each country.
    - If a country has a longer duration of education, it results in higher education attainment.  We can infer the correlation between education attainment and years of education for different countries.


## Visualization 3
Heatmap that represents water quality and air pollution index values for different countries or regions, with a user-interface design.

### Data & Tools
```shell
- Tools = Tableau (with the extension Add-on Charts)
- Code = Vis3.twvb
- Proceeded Data = Vis3.xlsx
```

<img src="https://github.com/Amyyyyeah/CSE-5544-SP2023/blob/main/fig3_1.jpeg" width="650px" height="530px" title="server result2" alt="server2"></img><br/>
* Description of how the completed project corresponds to the proposal
    - To enhance the user interface design, we incorporated a dot graph. The purple graph is water quality and the red graph is air pollution. If the gap between the purple and red graphs is larger than the others, it indicates that the country has a very healthy environment, and vice versa.
    - If the color of the air pollution column is darker gray, it indicates that the country has a higher level of air pollution. If the color of the water quality column is more purple, it means that the country has a good level of water quality.

## Visualization 4
Plot chart that shows a comparsion of top and bottom earners on the Life satisfaction index and quality of life factors. 
### Data & Tools
```shell
- Tools = Python
- Code = Vis4.html
- Proceeded Data = preprocessed_data.csv
```
<img src="https://github.com/Amyyyyeah/CSE-5544-SP2023/blob/main/fig4_1.jpeg" width="590px" height="530px" title="server result2" alt="server2"></img><br/>
* Description of how the completed project corresponds to the proposal
   - We created a scatter map that shows the relationshipt between the Life satisfaction index and one of the quality of life factors. To compare top and bottom earners, they are color coded differently.
    - To provide the user-friendly interface design, we set a box where one of the quality of life factors can be selected. Users can view the results of any factor that is selected.
    - For more information, we can check income, country name, and selected factor's and the Life satisfaction's values through mouseover.

## REFERENCES
[1] C. M. Freitas, P. R. Luzzardi, R. A. Cava, M. Winckler, M. S. Pimenta,
and L. P. Nedel. On evaluating information visualization techniques. In
Proceedings of the working conference on Advanced Visual Interfaces, pp.
373–374, 2002.

[2] B. Nikolaev et al. Economic freedom and quality of life: Evidence from the
oecd’s your better life index. Journal of Private Enterprise, 29(3):61–96,
2014.

