# Machine-Learning-Python

Our application is based on linear regression models on historic data. The goal is to analyze correlations between the odds, that are released by Betting Houses before the game, to predict the outcome of the match.  To achieve that, our application downloads the relevant data from the three most recent seasons (this is done dynamically: always current + two past seasons) automatically from an online datasource, prepares it for data analysis and performes linear regression models on the data.  
Afterwards, the user can interact with the app, by typing in the odds that are currently available for future games, to receive a prediction of the game outcom. This predicted outcome is based on the analysis of odds and game outcomes of the last three seasons. Because the online data base, that our application utilizes, is updated after every matchday, the automated prediction model also gets updated with the newest data.  

Important Note: For the Code to run successfully, open the .exe file or the .ipyng file only if it WITHIN the same  folder as the icons (.png and .ico files are stored in same .zip location)
