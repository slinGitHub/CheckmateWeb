## Overview Program Structure

Checkmate is using a simple program flow which is always re-run when the app is opened or resumed from the background.


<img src="https://user-images.githubusercontent.com/53019596/118677693-b9190b80-b7fc-11eb-9e8d-10bdf8d0c2c1.png" width="400">

1. Try to read local copy of dataset (Speed up)
2. Read in data from Nightscout (.csv) (On a separate thread to avoid lag in main thread as it takes time until Nightscout provides the data)
3. Calculate the GMI and InRange Values (CalcHba1c.java)
4. Draw the graphs for GMI, InRange and the DailyGraph
5. Save local copy to reduce loadup time during next startup (On a separate thread to avoid lag in main thread)

## Program features

### GMI/HbA1C Estimation 

hba1c = ((SumOfAllGlucoseValues/NumberOfGlucoseValues) + 46.7) / 28.7  

Source: [https://pubmed.ncbi.nlm.nih.gov/18540046/](https://pubmed.ncbi.nlm.nih.gov/18540046/)

