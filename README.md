# Sun Tracker

A tiny mobile web app that draws the sun's path over your phone's camera view, so you can see where the sun rises, travels and sets in any month of the year. Pick a month at the bottom: the orange line is that month's path (on the 21st, so June and December show the solstices), the dashed blue line is today, and the glowing disc is the sun right now.

**Open:** https://linusljungblom.github.io/sun-tracker/ in Chrome on Android, tap **Start AR**, and allow camera, location and motion sensors. Use *Add to Home screen* to install it as an app; it works offline after the first visit.

**If the path looks off:** wave the phone in a figure-8 to calibrate the compass, or, when the sun is out, tap **Align** and then tap the real sun to correct the heading.

No camera or compass? *View without camera* shows the same paths on a painted sky; drag to look around.

Plain HTML/JS, no build step. Sun maths by [SunCalc](https://github.com/mourner/suncalc) (BSD-2-Clause, (c) Vladimir Agafonkin), vendored in `suncalc.js`. Everything runs on the device; nothing is sent anywhere.
