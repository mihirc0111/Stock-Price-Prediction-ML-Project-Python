# Stock-Price-Prediction-ML-Project-Python
 To train the machine using data present to have a look at the effect of the pandemic on stock prices of various companies.

#### Graph of Stock Prices with Time

<img src="https://user-images.githubusercontent.com/84846378/221657783-778a917d-87db-4df4-af1f-e5cc5c8e84dd.png" width="50%" height="50%">

#### Comparison of Prices of SPY vs AAPL vs MSFT vs Amazon vs JNJ vs PFE vs F vs Google

<img src="https://user-images.githubusercontent.com/84846378/221658597-0b7e713b-52e2-4ff9-9947-28af084e0abe.png" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/84846378/221658856-604ba5fa-faa5-4162-a73f-9609118f77cd.png" width="50%" height="50%">

#### Data within a range of time

<img src="https://user-images.githubusercontent.com/84846378/221659073-60930ed3-c334-4e1c-b01e-e29295fb4fc3.png" width="50%" height="50%">

#### Graph for selected stocks

<img src="https://user-images.githubusercontent.com/84846378/221659455-436118a6-0625-4129-a17c-37ef5789fba6.png" width="50%" height="50%">


#### Normalizing the data

<img src="https://user-images.githubusercontent.com/84846378/221659817-c35ffa03-e651-4221-b189-dfe896850001.png" width="50%" height="50%">

#### Effect of pandemic on stock prices

<img src="https://user-images.githubusercontent.com/84846378/221660245-d0bf2209-1a44-4e1d-a726-da43c7eb2a84.png" width="50%" height="50%">
...
<img src="https://user-images.githubusercontent.com/84846378/221660563-ed791c6e-0960-4466-8c52-904294435041.png" width="50%" height="50%">
...
<img src="https://user-images.githubusercontent.com/84846378/221660303-e87991aa-7cac-4324-b225-4223801ce290.png" width="50%" height="50%">

#### Rolling Mean for MSFT/Microsoft

<img src="https://user-images.githubusercontent.com/84846378/221660793-857aaea0-acae-4218-b409-225eb4d67e55.png" width="50%" height="50%">

#### Computing Daily returns of Microsoft

<img src="https://user-images.githubusercontent.com/84846378/221661094-e337979d-488e-454d-a3fb-db91b152eec1.png" width="50%" height="50%">

#### Predicting Adjusted Close value of MSFT

<img src="https://user-images.githubusercontent.com/84846378/221661319-aee48193-fa88-44d7-b8a0-7640693381d0.png" width="50%" height="50%">

#### Predicting using Long Short-Term Memory (LSTM)

<img src="https://user-images.githubusercontent.com/84846378/221661637-6f88a6a9-8e69-4f63-ab19-bc2966442bdf.png" width="50%" height="50%">


#### Predicting using Linear Regression

<img src="https://user-images.githubusercontent.com/84846378/221661775-5357447e-22d7-45e3-a116-f4194a8eb452.png" width="50%" height="50%">


#### creating an instance of a Random Forest Regressor 

<img src="https://user-images.githubusercontent.com/84846378/221661990-817ec8e9-efeb-4d2f-81a7-a1793a02d2d9.png" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/84846378/221662355-1b575138-db8c-40b2-afe0-10cb05435d32.png" width="50%" height="50%">



> #From my investigation of three different models, I observed that RandomForestRegressor delivered a much lower mean absolute error  than the LSTM  or LinearRegression  for Microsoft and Google respectively. I also observed that tunning the parameters for LSTM (e.g the number of epochs and batch_size) resulted in better prediction.

> #Interesting facts about the project
> #When exploring the data, it was interesting to see how the stock prices of different companies changed due to the pandemic and how the technological companies stock prices bounced back more quickly than the other companies considered. It was also interesting to see how Pfizer stocks improved as the vaccine rollout began.

> #Here are some major highlights from the data exploration section:

> #2019: Before the pandemic, most of the companies stocks were doing relatively well with Apple and Microsoft taking the lead and Pfizer trailing behind.
> 
> #2020: On the onset of the pandemic around Spring, there was a fall in stock prices for all the companies, but afterwards the technology companies like Amazon, Apple, Microsoft and Google started to grow again. But companies like Pfizer, Ford and S&P 500 did not do very well especially Ford.
> 
> #2021: As the vaccine rollout began and the lockdown began to be lifted, there was significant growth in the stock prices of Ford in particular given its very stock prices which was low in 2020 due to the pandemic. Companies like Google and Microsoft,S&P 500 also grew. Overall there was an improvement in the stock prices of all the companies we considered.
> 
> #Difficulties encountered
> 
> #Getting the data from yahoo fincance wasn't very obvious. After several research I was able to find an article that guided me on how to obtain the data.
> 
> #In the modelling part (particularly the LSTM), one would have to spend some time tuning the parameters and training it to get the best results.

### Continued development

I would like to learn futher advance techniques which will help my model to reduce the mean absolute error.

#### Author

LinkedIn - [Mihir Chavan](https://www.linkedin.com/in/mihir-chavan-643615234/)
Github - [@mihirc0111](https://github.com/mihirc0111)

#### Acknowledgments

I learned ML from acmegrade modules of Sir Noble Xavier.

