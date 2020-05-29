# Weather-App
Weather App which utilizes a dark sky RESTful API and HTTP to receive weather data and display to an Android device.

I have included the four most important files for the project. 

The first one being the AlertDialog.java file. This class is needed in order to utilize AlertDialog in the main class.

The second class, CurrentWeather.java, contains all the weather data received from the dark sky API. This includes temperature, humidity, time, timezone, and a weather summary.

The main class tells the Android app what to do when it is first run, in the onCreate() method. The MainActivity class is responsible for actually making an HTTP request out to the dark sky web server and for receiving the response.

If you would like to run the project you may do so by downloading the Android Studio IDE and by installing the app onto your phone.

I haven't released the app to the play store yet as I want to continue to add to it.


