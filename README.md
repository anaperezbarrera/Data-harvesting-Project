[Ana Pérez](https://github.com/anaperezbarrera) and [Laura Martínez](https://github.com/laura-martinez00)
# Data-harvesting-Project
This project was born from the motivation of helping other youngsters that might be doubtful of which one can be their best option for partying in Madrid, and since there is a webpage [Fourvenues](https://www.fourvenues.com/es/discotecas-madrid) that concentrates the sale of tickets of the majority of events and clubs in Madrid, we thought it was the best option for getting our data.

Thus our scraper will be on the page of Forvenues in which every day new events come up allowing people to buy tickets through their webpage. The web has a main page that displays all the options with different dates and times and once you enter into each event types of tickets come up, allowing the user to choose the entry that best suits their interests.

The ultimate goal of this project is to retrieve and analyze the events of the month of march using RSelenium and the Google Maps API.  Here, you can find a step-by-step guide to set your own Google Maps API and replicate this exact project.

## Google Maps API

1. Create a Google Cloud Platform (GCP) Account: If you don't have one already, you need to create a Google Cloud Platform account at https://cloud.google.com/. You'll need a Google account to sign up. (Note that: Google may require you to set up billing information to use their APIs, even if you're using them within the free tier. Follow the instructions provided to set up billing if prompted)

2. Create a New Project: Once you're logged in to your GCP account, navigate to the Google Cloud Console. Then, select an existing project or create a new one and name it. Projects provide a way to organize and manage resources, and each API usage is associated with a project.

3. Enable the API options: Once in your project, in the sidebar menu, go to "APIs & Services" > "Library". Search for "Maps JavaScript API" and enable it. Inside, you will also have to enable "Places ID" and "Geocoding API".

4. Get an API Key: After enabling these options, go to "APIs & Services" > "Credentials". Click on "Create credentials" and select "API key". Copy and save the generated API key. (Note that: this is your personal key to access the Google API services).

5. Go back to Rstudio: In Rstudio, create a Text file and write down: apiKey=YOUR API KEY. Then, save this file in your working directory as .env and read the subsequent lines.

You can find further detailed information on how to reproduce this exact project in our Rmd file above. 
