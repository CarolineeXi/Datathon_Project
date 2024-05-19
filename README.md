# DubsTech-Datathon-2024
Team: STAT342 Team

## Intro
Drug overdose is not just a statistic—it's a devastating reality that plagues communities across the United States. In 2019 alone, the toll of drug overdose deaths reached a staggering 70,630, marking a 4.8% increase from the previous year. Behind each number lies a story of loss, of shattered dreams, and of futures cut tragically short.

At the heart of this crisis lies the specter of opioids, which have emerged as the primary culprit behind the rising tide of overdose deaths. In 2019, opioids accounted for a staggering 70.6% of all drug overdose deaths—a harrowing statistic that underscores the urgent need for action.

Faced with this sobering reality, the U.S. government has turned to data and analytics in search of answers. They have enlisted you and your team to provide insights that can guide the development of better policies and health interventions—ones that can stem the tide of overdose deaths and offer hope to those struggling with addiction.

## Methodology 
Throughout the analysis of the graphs, we can see that as the year increases more estimated deaths are expected to occur with males taking up a higher proportion of fatalities for gender. Depending on the drug we can also see that different age groups are more susceptible to overdose as seen in our detailed analysis. We also see that overall the white population is the most susceptible to drug overdose.

We use random forests to forecast future drug overdose death rates for each demographic group. After using hyperparameter tuning, we have the improved model with the RMSE equals to 1.26 and marginal of error equal to 0.07. By exploring feature importance in the random forest, we can conclude that drug overdose type and age are most strongly associated with higher death rates.

## Datathon Submission Presentation
* Code: All code for graphs are in the Datathon_Flex.rmd file, all code for the ML model are in the files labeled Machine Learning
* Our Final Product is a Dashboard
    * Option 1 Run the dashboard
       * Install R and RStudio
       * Open Datathon_Flex.rmd and press Run Document with these file in the current working directory:
         * Drug_overdose_death_rates__by_drug_type__sex__age__race__and_Hispanic_origin__United_States_20240518.csv
         * Feature_Importance.png
         * Residuals.png
    * Option 2 downlaod and watch the recording and pause if necessary:
        * https://github.com/CarolineeXi/Datathon_Project/blob/main/Flex_Recording.mp4
     
    

