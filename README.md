# Electric car price prediction
In this project I scrape electric car data from the Netherlands and update a regression model daily. The data is scraped from autoscout24.nl to get the new listings for today, then the linear regression model is updated and today's prices are predicted with the updated model.

Because I am quite interested in electric cars (and especially the amazing Polestar 2!) I wanted to start this project. In this project I wanted to learn more about web scraping and this was a nice project to be able to use a model to predict on new data. 

The R-markdown file updates with the new electric car listings and saves the data to "newest_electric_car_data.Rds". The model is then updated and new prices are predicted. Everytime the script is run, a pdf is generated with the current model performance (A), the main factors driving the predicted price (B), and the predicted prices for new cars (C).
