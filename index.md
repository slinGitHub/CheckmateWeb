<img src="https://user-images.githubusercontent.com/53019596/114172661-3c119100-9936-11eb-826f-375bff51032b.png" width="100" height="100">


## Welcome to the Checkmate Homepage
Checkmate was written to give you a fast overview of your current diabetic treatment status (Based on your Nightscout cloud data). 
This project is published as open source.

### Download APK
Download the latest Checkmate version here: 
[CheckmateV01.apk](https://github.com/slinGitHub/Checkmate/releases/download/CheckmateV01/CheckmateV01.apk)

### Checkmate Features
- Visualize the daily GMI (Glucose Management Indicator) or average blood sugar level
- Visualize your daily "in Range" in percent (In range borders are configurable)
- Visualize the estimated HbA1c level over a 30 day period
- Visualize the "in Range" over a 30 day period
- Visualize the glucose profile over a day for an easy understanding of the GMI and In-Range values
- A notification informs you every day about your GMI and In-Range results

### Checkmate GUI Overview
<img src="https://user-images.githubusercontent.com/53019596/115973698-5d3dc880-a557-11eb-9c51-bdc6b29b020e.png" width="300">

### Checkmate Code Repository
The Checkmate source code can be reviewed and compiled from:  
[Link to Checkmate Source]()

### Checkmate Documentation
- HBA1C Calculation  
  hba1c = ((SumOfAllGlucoseValues/NumberOfGlucoseValues) + 46.7) / 28.7  

(More will be added soon, please come back later..)

### Used Data Sources

**[Nightscout Project](http://www.nightscout.info)**  
Checkmate is using the Nightscout glucose data API to receive your raw glucose data and calculate and visualize the up- and downs of your current diabetic treatment status. Therefore a nightscout database is mandatory to run Checkmate. Follow the guide here to set-up a nightscout database [https://nightscout.github.io/](https://nightscout.github.io/).

**[XDrip+](https://jamorham.github.io)**  
XDrip (with for example the Dexcom G6) can be used to upload glucose data from the smartphone to the nightscout cloud.
This programm is not replacing any functionality of XDrip which can be downloaded at [Jamorhams Page](https://jamorham.github.io).

### Acknowledgement
I want to thank the nightscout project, Jamorham, and PhilJay from MPAndroid for making this project possible and for improving my life as a diabetic to a degree which would be not possible with the commercialy available software.

### Donations
**This project can be supported by you!** If you would like to support this project's further development, feel free to donate. Your donation is highly appreciated (especially for all the coffee during programming) Thank you!

**Paypal**  
[Donate 5 $](https://www.paypal.com/donate?hosted_button_id=CF3AHXTKNARRL): Thank's for working on this project, here's a coffee for you!

### Disclaimer
Checkmate was not written for commercial purposes and is published as open source.
Therefore I will not take any responsibility for using this app.

Copyright by N.B., April 2021  
(slincheckmate(at)gmail.com)
