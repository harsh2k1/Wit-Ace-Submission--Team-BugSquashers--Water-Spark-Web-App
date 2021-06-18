
# To download the code, Please download this zip as code uploaded on github is not working properly
[Bug Squahsers- Wit Ace-Water Spark.zip](https://github.com/sourabhv/FlapPyBird/files/6678097/Bug.Squahsers-.Wit.Ace-Water.Spark.zip)

# Spark Water

A solution for "Clean Water and Sanitation" theme of Wit-Ace Hackathon.
# Short Description
**What's the problem?**

Water is the natural resource that is most threatened by
climate change and is a prerequisite for life on earth. 
Due to lack of Clean Water and Sanitation,
 2.2 billion people around the world do not have safely
 managed drinking water services, 4.2 billion people 
 do not have safely managed sanitation services,
 and 3 billion people lack basic handwashing facilities.
 These services are critical in preventing the spread of 
 COVID-19 and other diseases.

**How can technology help?**

From intelligent solutions for small farmers to 
recycling showers, technology can make a significant
impact on the availability of water and its consumption.
It can also help in locating soil moisture content density 
in order to facilitate agriculture activities. It can alert and 
help people relocate during bad weather conditions.

**The Idea**

A web application which will interact with User and provide with geolocations and data of
Clean Water availability and it's toxicity level, soil moisture content density and 
Weather Data.

# Demo Video

https://www.youtube.com/watch?v=LmKEogQi-2E

# Architecture

![architecture](https://user-images.githubusercontent.com/86097511/122518889-6fa42200-d02f-11eb-82cb-b3ba87165bff.png)

- User will interact with Web application
- Web application will get data from APIs and externally through 
database.
- We have used Node-Red technology to create our services.
- Watson Assistant can be used to enhance User experience.





# Long Description

**Spark Water**

The idea revolves around APIs used in a Web application
for water data collection and dissemination,
Soil moisture analysing and Weather API.
We have designed an Web application which will:
- Show user geolocations for availability of fresh water and soil moisture content denisty.
- It will give toxicity level, in water, EPA limit and health risk.
- Also, it will provide user with Current weather conditions including temperature, pressure, solar radiation, humidity etc. 
- On top of that, it will show hourly data for temperature for past 7 days and can give average temperature of any historical date.

With this idea, you could have a centralized way to:
- Query geolocations of soil moisture content.
- Query availability of fresh water.
- Analyse water toxicity level for a basin.
- Find weather conditions of past 7 days.
- Simplify coordination and funding for water construction projects.
- Find weather alerts and relocate people beforehand.
- Locate suitable agriculture land and simplify funding for that.
- Enable transparent water usage, cleanliness results, and site-to-site comparison.


## Features

- **Geolocations for Clean Water Availability**
    
    Using this service, user can find geolocations for Fresh Water 
    availibility in their area. We have used USGS NLDI API and
    Node-Red service of IBM in this feature.

- **Weather Conditions Viewer**

    Using this service, user can find out weather conditions of their area, 
    Average temperature of Day and hourly temperate for past 7 days.
    User can search their personalised data stations using station ID
    and retrieve data. This feature can be used to apply certain measures
    to avoid mishappenings in case of bad weather. Hourly temperature data
    can be used in agriculture methods for growing crops suitable to 
    temperature conditions.  It will help in sustaining Green ecosystem.
    

    We have used wunderground API and Node-Red technology in this feature.

- **Geolocations for Soil Moisture Content Density**

    Using this service, user can find out the moisture content in the soil.
    This will help in agriculture and Green Consumption cause.
    Plus, it will help locating underground water availibility which can be
    used in various ways by digging borwells. It will contribute towards
    UN Sustainable Development Cause.

    Docker and Elyra technologies along with Copernicus data provider
    API key can be used in this feature.

- **Chat Assistant Bot**

    IBM Watson Assistant is a great tool for interacting with User.

  # Roadmap
  The project currently does the following things.

- Locating Geolocations for Clean Water Availability
- Weather Conditions Viewing
- Locating Geolocations for Soil Moisture Content Density (not working yet)
- Chat Assistant Bot



See below for our proposed schedule on next steps
 after Wit-Ace 2021 submission.

  ![roadmap](https://user-images.githubusercontent.com/86097511/122521804-e262cc80-d032-11eb-9d84-0bf860250d52.PNG)


# Getting Started
- Download the code in zip format
- **Create a new folder in **
- Copy paste the html code in your editor and open with Live server.
- Follow the links to view features.

# Built with
- IBM Cloudant
- IBM Node-Red
- IBM Watson Assistant
- USGS NLDI API
- Wunderground Weather API

# Acknowledgements

Based on Billie Thompson's README template.
