# Image filter recommendation of Instagram posts by Image segmentation 

Image filter recommendation of Instagram posts by Image segmentation 

Social media like instagram are photo-based engagement. People post photos with differecnt filters and sometime it is hard to choose a good/fit one. 
This project is trying to provide filters recommendations for the instagram photos to get more likes from others. 

Image data sources are downloaded here [Instagram Basic Display API]( https://developers.facebook.com/docs/instagram-basic-display-api/ )

# Instagram photos scraping
Images and tabular data scraped from Instagram. You can find details from "Web Scraping_2019.ipynb" under main directory.
You can find the [instagram-scraper](https://github.com/arc298/instagram-scraper/)

# Model Training
There are two models trained by this project: CNN and [Tabular model](https://docs.microsoft.com/en-us/analysis-services/tabular-models/tabular-models-ssas?irgwc=1&OCID=AID2000142_aff_7593_1375745&tduid=(ir__rorjnyrxpgkftnrvkk0sohzize2xiyqprpxbcq2q00)(7593)(1375745)()()&irclickid=_rorjnyrxpgkftnrvkk0sohzize2xiyqprpxbcq2q00&view=asallproducts-allversions)


# Model results 
|Image Model	 |  Precision	   | Accuracy	  |  Recall |
| ------------ | ------------- | ---------- | --------| 
|Tabular model |0.187|0.711 |0.171|
| CNN+ Tabular model | 0.485 | 0.854| 0.592|

More details about model tranings can be found in "Model Training_2019.ipynb"
