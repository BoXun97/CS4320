**Boao Huang**
---

> *We want to develop software for an alarm clock.*

> *The clock shows the time of day. Using buttons, the user can set the hours and minutes fields individually, and choose between 12 and 24-hour display.*

> *It is possible to set one or two alarms. When an alarm fires, it will sound some noise. The user can turn it off, or choose to “snooze”. If the user does not respond at all, the alarm will turn off itself after 2 minutes. “Snoozing” means to turn off the sound, but the alarm will fire again after some minutes of delay. This “snoozing time” is pre-adjustable.*

---

**Use Case Diagram**

![Error](https://github.com/BoXun97/CS4320/blob/master/Challenge%20Alarm%20Clock%20Use%20Case/use%20case%20diagram.jpg)

---

**Use Case Description**

> Description - This part is helpful for people to create a software of alarm clock. User can set many ways of clock to display, alarm, and turn off. It divide the work into many block. It helps people to solve the problem when they are developing the software.

|Scenario|Create a alarm clock include clock setting and alarm setting|
|:-|:-|
|Triggering event|User can set alarm clock and turn off the alarm of clock|
|Actor|User|
|Related use cases|N/A|
|Stakeholders|Alarm clock user, merchant, customer|
|Pre-condition|User can set the time display and the alarm|
|Post-condition|User can turn off the noise of clock or the clock can turn off by itself|
|Flow of events|Actor:    1.User uses the buttom to set time display    3.User uses the button to set the mode of alarm  5.User can turn off the alarm clock's noise by different way     System:      2.Clock will display time in different way     4.Clock will be set in different way to alarm and turn off 5.Clock can be turn off by botton, itself, or "snoozing"|
|Exceptions|1.If the alarm clock does not display in correct way, you can refresh the program and reset it   2.If the alarm clock does not generate noise by the correct way, the setting alarm has error then user can correct it  3.If the alarm does not turn off by the correct way, you can close the software and correct the alarm setting part|


