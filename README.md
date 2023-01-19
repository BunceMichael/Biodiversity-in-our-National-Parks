# Biodiversity in our National Parks
### a.	Introduction

This analysis aims to explore the geographic location of National Parks in the United States and the biodiversity within them. The U.S. is home to a diverse array of ecosystems, and National Parks serve as important protected areas for the conservation of these ecosystems and the species that inhabit them. The location of a given National Park naturally has an effect on the distribution of species that live there and this study will use a combination of geographic information and field research to investigate patterns and explore potential factors in that distribution. The results of research like this could provide valuable insights for policymakers and conservationists working to protect and preserve the biodiversity of the United States.

### b.	The Dataset

The dataset used in this study was created using data provided by the National Parks Service (NPS), an agency of the United States Department of the Interior that manages and protects the country's National Parks and was obtained from Kaggle. The dataset includes two .csv files, one outlining the geographic information of each National Park and one with a list of species found in each National Park, along with other taxonomical and conservatory information. The development and infrastructure of National Parks can vary widely, making data collection a challenging process, with a lot of variables from park to park. As such, this dataset is considered a work in progress and is likely far from complete and comprehensive.

I chose to analyze biodiversity in National Parks because of my deep appreciation for these protected areas. As someone who has had the privilege of visiting many of them throughout my life, I have seen firsthand the incredible natural beauty and diversity that they hold. I believe that learning about and understanding our ecosystems is essential in order to protect and preserve them for future generations. Additionally, I have always been fascinated by geography and the ways it shapes the distribution of plants and animals. Combining my passion for national parks, my belief in the importance of understanding our ecosystems and my interest in geography, this research was the perfect opportunity for me to practice my python, pandas, matplotlib and data visualization skills.

### c.	Other’s Findings

The NPS determined that the Great Smoky Mountain National Park in NC/TN is the most biodiverse park in the U.S. (https://www.nps.gov/grsm/learn/nature/index.htm)

The website Towards AI analyzed similar data and discovered that mammals and birds had a higher likelihood of being an endangered species. ( https://towardsai.net/p/l/analysis-on-the-biodiversity-in-national-parks-projects)

Isabel Bukovnik analyzed biodiversity in National Parks and took into consideration factors such as richness and abundance to make some amazing graphics and a great website that dives deep into the importance of this topic. (https://storymaps.arcgis.com/stories/4a4ad9e91f8e446d8fc2fc972bef282e)

### d.	Sources

I obtained my data from https://www.kaggle.com/code/jonathanbouchet/biodiversity-in-us-national-parks-2016

### e.	Summary

After converting the data to a GitHub repository, I imported it into Google Colab and began to explore the information I had using pandas. I calculated the mean, median, mode, maximum, and minimum values for all applicable columns and got a sense for the types of data I was working with. Then I went to work manipulating the dataframe in order to best access the variables I was looking to compare and visualize. Using matplotlib I was able to make various graphs exploring the distribution of National Parks throughout the country and the biodiversity within them.

### f.	Graphs

At this point the graphs are largely histograms and bar graphs because this is the best way to compare a nominal variable (such as 'State' or 'Park Name') to a continuous variable (such as 'Latitude' or 'Species Count'). 

### g.	Conclusion

While I think that my exploration of this dataset has been a success to this point, I do think there is more to uncover. I focused on a handful of specific columns for the purpose of this analysis, and I think that revisiting the removed data could provide further understanding. As I continue to explore this data I hope to increase the complexity of the visualizations and incorporate some other types of graphs as well.  

