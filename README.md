# 5G_Impact_On_Canada_GDP

In this project, we predict the 5G impacts on GDP of Canada and other three areas, including Ontario, Albert and Quebec. 
We study the formulas that indicates the relationship between 5G deployment cost and GDP increment. The GDP multipliers that can be used to convert investment in the 5G ecosystem into economic outcomes which is the GDP increment. Besides, the population density, land area and 5G deployment cost on IoT will influence the total deployment cost. 

<img width="383" alt="image" src="https://user-images.githubusercontent.com/70187992/160931239-5eb99c79-18f6-44c5-a3fe-354c6f584eaa.png">
<img width="303" alt="image" src="https://user-images.githubusercontent.com/70187992/160931325-8b2069b6-698e-4d08-b4b4-4deda344c59a.png">
<img width="324" alt="image" src="https://user-images.githubusercontent.com/70187992/160931437-666c6f4f-ea49-4c82-907e-e628ba789137.png">
<img width="340" alt="image" src="https://user-images.githubusercontent.com/70187992/160931477-414cb122-910c-4a0a-a72f-4bc30fc4b3c1.png">


According to these equations, the prediction processes are given below. The data in the blue box can be found online and the data in the yellow box needs to be calculated and predicted. We select the autoregressive moving average model to conduct the prediction, which use the time series data to better predict the future trend.

<img width="350" alt="image" src="https://user-images.githubusercontent.com/70187992/160927958-b3be2aa6-1d2f-4892-b682-386661c34046.png">

Based on the process, the files CanadaGDPimpact.ipynb, onGDPimpact.ipynb, alGDPimpact.ipynb, QGDPimpact.ipynb contains the code and the result to predict GDP in Canada, Ontario, Albert and Quebec respectively. In conclusion.ipynb, it summarizes the four sets of GDP data forecasted before. We provide the overall trend of GDP from 2010 to 2030 based on the previous data and the predicted value, which is shwon below.

<img width="380" alt="image" src="https://user-images.githubusercontent.com/70187992/160928692-f03c2e86-9f67-49fd-91e6-655f40038804.png">


