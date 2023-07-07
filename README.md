# silviaCommute
display best route to work and home

## stuff im using
- using parts of [WazeRouteCalculator](https://github.com/kovacsbalu/WazeRouteCalculator) to get ETAs from waze
- python for code
- likely will run on raspberry pi that will need internet
  - VF display for period-correctness long-term but simplest display possible short term
  - need to power from car and run script on pi as soon as it boots
  - 2 buttons, one for "ETA and best route HOME" other for "ETA and best route to WORK"

## hardware ideas
- 1x20 VFD Display (noritake itron)  https://au.element14.com/noritake-itron/cu209-tw202a/vfd-module-1x20-9mm/dp/1216670
  - pros: looks good and seems reliable
  - cons: expensive
  - relevant link maybe: https://www.smbaker.com/interfacing-a-vfd-display-to-the-raspberry-pi
