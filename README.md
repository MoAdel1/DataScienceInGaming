# Data science in gaming industry

## Introduction

This repository is my attempt to show why I am a good fit for the senior data scientist position by:

- Discussing possible applications using data science in Kolibri games
- Give a demo for one of the problems that can be solved using machine learning with real life example data

While Koilbri games may already be working on some or all of the proposed applications, the purpose here is to demonstrate my own:

- Research skills
- Creativity
- Data science/Machine learning skills
- Software development skills
- Huge interest in working in Kolibri games as a new and exciting challenge for me

I hope this would give you the opportunity to know me better than a cover letter or an assigned task.

-----------------------------------------------------------------

## Data sources

Usually we can split the data sources in gaming industry into three sources:

- User/player data (play logs, purchases, events, etc...)
- Performance data (game logs, crash down data, etc...)
- Macro data (play store stats, reviews)

![Data sources](./resources/data_source.png)

Different data sources are stored in the proper databases (structured/unstructured), based on the datatype. The data is passed through data extraction and feature engineering pipelines before being used in any of the data science dependent applications.

-----------------------------------------------------------------

## Applications

It is safe to assume that applications dependent on data may fall into one of the two categories:

- Analytical applications: gives insights into the business 
- Actionable applications: gives recommendations and actions to act upon 

Some of these applications are illustrated in the following chart

![Applications](./resources/applications.png)

### Analytical applications:

1. **Game KPIs**

    Monitor on a daily basis the important KPIs such as number of downloads, average play time and number of new users, etc...

2. **Game performance**

    Monitor the actual performance of the game, any unexpected crash down or similar events.

3. **Features effects**

    Track the effect of new/existing feature in terms of players engagement and effect on overall KPIs as an example.
 
4. **Purchase tracking**

    Tracking for the current purchases inside the game and come up with KPIs to monitor as well.

5. **Offers effects**

    Track the effect of new/existing offers in terms of players engagement and effect on overall KPIs as an example.

### Actionable applications:

1. **Predict player lifetime value**

    Build machine learning models to predict how much revenue could be expected from a certain player.
    
2. **Targeted Ads**

    Build models to start giving certain Ads to certain customers which should increase convergence rate.

3. **Targeted offers and deals**

    Instead of general offers, we send specific offers and deals based on the player current behaviour and probability of leaving the game permanently (customer churn). This should keep the player engaged even for a longer time by giving him/her what he/she wants.
 
4. **Sentiment analysis for reviews**

    Given the huge number og players it becomes hard after some time to go through all the reviews on the play store manually, this is where sentiment analysis models come in. It goes through provided review to determine if it is positive or negative and much more.  

5. **Players clustering**

    On its own one may not see the value of clustering similar players together based on their behaviour/features; however such product is helpful for other products such as **[targeted offers and deals]** and **[targeted Ads]** to name a few. 

6. **Customer churn**

    Predict the probability of a player to stop playing the game for good within a certain time frame.
