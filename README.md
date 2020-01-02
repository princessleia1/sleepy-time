# Sleepy-Time
**Sleepy-Time** is a Fitbit Ionic and Versa App for Fitbit OS for monitoring your sleeping habits. **Sleepy-Time** uses the new [Fitbit SDK 4.1](https://github.com/Fitbit). This App utilises Fitbit Sleep API V2.

## Sleep Logs
**Sleepy-Time** gets data from the Fitbit OS Get Sleep Logs by Date endpoint. It returns a summary and list of a user's sleep log entries (including naps) as well as detailed sleep entry data for a given day.

* Date of sleep
* Duration of Sleep
* Level of Sleep (Deep, Light, REM, Wake).
* Average Duration of Sleep over 30 day period.

## Sleep Data
**Sleepy-Time** uses **Stages** Level. Data is returned with 30-second granularity. **'Sleep Stages'** levels include *deep*, *light*, *rem*, and *wake*.

## Sleep Goal
**Sleepy-Time** uses the Sleep Goals endpoint that returns a user's current sleep goal using unit in the unit system that corresponds to the Accept-Language header provided in the format requested.

## Devices
**Sleepy-Time** is built for Fitbit Devices: Ionic (348x250), Versa (300x300), Versa 2 (300x300), and Versa Lite (300x300).

<p align="left">
  <img width="175" height="175" src=./screenshots/sleepy-time-versa-1.png>
  <img width="175" height="175" src=./screenshots/sleepy-time-versa-2.png>
  <img width="175" height="175" src=./screenshots/sleepy-time-versa-lite-1.png>
  <img width="175" height="175" src=./screenshots/sleepy-time-ionic-1.png>
</p>

**TODO:**
- [ ] Update CSS, JS, GUI Files to support new Versa 2 Device and Fitbit SDK 4.1.
- [ ] Update/ optimise Background Image for Versa 2 Device compatibility.

## License
**Sleepy-Time** App is licensed under the terms of the [GPL-3.0 License](/LICENSE). 

<p align="middle">
<img width="80" height="80" src=./resources/icon.png>
</p>
