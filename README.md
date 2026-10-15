# Sun Tracker

A tiny mobile web app that draws the sun's path over your phone's camera view, so you can see where the sun is at any hour, and its whole path through the day, in any month of the year. Pick a month and drag the time slider: the big sun shows where the sun is at that time, and the orange line is its whole path that day (the 21st, so June and December show the solstices) with hour marks. The dashed blue line is today and the small disc is the sun right now. **Now** resets the slider to the current time.

**Open:** https://linusljungblom.github.io/sun-tracker/ in Chrome on Android, tap **Start AR**, and allow camera, location and motion sensors. Use *Add to Home screen* to install it as an app; it works offline after the first visit.

**If the path looks off:** wave the phone in a figure-8 to calibrate the compass, or, when the sun is out, tap **Align**, put the sun in the middle of the screen and tap it. This corrects the compass (sideways) and tilt (up/down). Then drag until the white line sits on a distant real horizon for a precise up/down fix, and tap Done. It is remembered on the phone.

No camera or compass? *View without camera* shows the same paths on a painted sky; drag to look around.

Plain HTML/JS, no build step. Sun maths by [SunCalc](https://github.com/mourner/suncalc) (BSD-2-Clause, (c) Vladimir Agafonkin), vendored in `suncalc.js`. Everything runs on the device; nothing is sent anywhere.
