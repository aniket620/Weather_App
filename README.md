# Weather_App


Overview

Developed a weather application that monitors the weather conditions for four cities by utilizing multithreading and MongoDB. Obtained API access key by subscribing to the OpenWeatherMap website. Implemented a multi-threaded program with distinct threads for various tasks. One thread is responsible for downloading the 5-day/3-hour forecast, another thread for retrieving weather maps, and a third thread for opening and displaying the latest weather map in a window, showcasing the most recent image based on the timestamp.

The forecast threads are designed to issue alerts in case of rain, snow, or freezing temperatures (<2 degrees Fahrenheit) during any forecast period. Additionally, the program displays forecast and historical data from the database in a graphical format.


