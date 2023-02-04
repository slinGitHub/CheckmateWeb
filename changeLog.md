## Checkmate Change-Log

###V034
- Remove greyed out lines

###V033
- Bug fix : Daily chart line is now rendered 
- Feature: Load data only once at start up (instead twice)  
    - Only retrieve latest data
    - Load data incremental; combine stored file and new data
    - Do not load data when already loading or latest data is less than 5 minutes old
    - Feature: Add a menu clear data
- Bug fix: Remove the last incomplete day

###V031
- Bug fix : Daily notification with token access to nightscout not working

###V03
- Access with Nightscout token possible
- Screen size can be adapted
- mmol/L added


###V02
- Owl icon appears when in range
- Measurements with 0 are not recognized by the algorithm
- Glucose mean chart added
- Glucose mean chart: 7/15/30/90 day overview (just click on the white circle with the day number)
