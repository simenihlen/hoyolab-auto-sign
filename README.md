﻿# hoyolab-auto-sign

## Setup
1. Go to [Google Apps Script](https://script.google.com/home/start) and create a new project with your custom name.
2. Select "main" and click the "Run" button at the top.
   Grant the necessary permissions and confirm that the configuration is correct (Execution started > completed).
3. Click the trigger button on the left side and add a new trigger.
   Select the function to run: main
   Select the event source: Time-driven
   Select the type of time based trigger: Day timer
   Select the time of day: recommended to choose any off-peak time between 0900 to 1500.

## Configuration

```javascript
const token = "ltoken=xxxxxxxxxxxxxx; ltuid=xxxxxxxxxxxxxx;"
//Replace the string with the token that is used in the post request for the daily check-in
```
