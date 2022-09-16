# Government Debt Bar Chart
This chart visualizes the debt-to-GDP ratios of each country in 2020 and ranks them from the lowest to the highest. Estonia has the lowest ratio among the selected countries while Japan has the highest.
<iframe src="https://data.oecd.org/chart/6Ob1" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Ob1" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

# Grid of Line Charts
This is the grid of line charts showing the trend of debt-to-GDP ratio of countries during the period of 1995 to 2021. We can have an overlook on the trend of debt-to-GDP ratio change of the selected countries. We can also see that many counties experienced an increasingly serious level of debt issue during that time when data is available.
<div class="flourish-embed flourish-chart" data-src="visualisation/11141746"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# A Look at the Change of Debt-to-GDP Ratios among G7 Countries in the 2010s
During the period of 2010-2020, Japan remained the country that had the highest debt-to-GDP ratio among all G7 countries every year. And it showed an upward trend. Meanwhile, Germany remained the country that had the lowest debt-to-GDP ratio in the group. The two countries demonstarted an increasing gap in terms of debt-to-GDP ratio.
<div class="flourish-embed flourish-scatter" data-src="visualisation/11142140"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Summary
On this page, three charts are included: a bar chart, a grid of line charts, and a scatter plot. The bar chart makes it easy to compare the ratios among all countries in the same year. Since the bars are already sorted, we can easily find the countries with the lowest and the highest ratio. The downside is that it only shows the data for one specific year. The grid of line charts shows many charts, which indicate the trend of debt-to-GDP ratio change for each country, at the same time. We are presented with a lot of information in this case. If we are looking for the historical trend for a particular country, we can find the chart for that country to see if it is going upward or downward. However, it is difficult to compare the trend of different countries as the lines are on separate charts. 

For the third data visualization, I wanted to find a balance between easy comparison and trend presentation. But there are also a lot of data to work with in the original data source. So I decided to narrow down the scope and focus on only a few countries and time periods in order to convey meaningful information. I selected the G7 countries and used a scatter plot to show their trend of debt-to-GDP ratios during the 2010s. From the scatter plot, we can see that the ratios of all G7 countries are going up except Germany, which had some fluctuation but largely remained the same over the decade. Importantly, the ratio of Japan is much higher than other G7 countries, so I used red color to highlight this information. Red attracts readers' attention and indicates the serious problem in Japan. On the contrary, I used green color on Germany to show contrast and opposition to Japan.

# Working with Tableau
<div class='tableauPlaceholder' id='viz1663292602194' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP Ratios by CountrySource: OECD Data ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;de&#47;debt-to-gdpratiosbycountry&#47;Debt-to-GDPRatiosbyCountry&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='debt-to-gdpratiosbycountry&#47;Debt-to-GDPRatiosbyCountry' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;de&#47;debt-to-gdpratiosbycountry&#47;Debt-to-GDPRatiosbyCountry&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663292602194');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
