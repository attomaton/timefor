# Changelog

## 1.0.1

- Fixed: an app could close a few minutes after you chose a longer time. A timer left over from
  an earlier session (for example, one that ran out while the phone was asleep) ended the new
  session.
- Fixed: when the time was up, YouTube and other video apps kept playing in a floating mini
  player. Timefor now pauses playback before leaving the app, and pauses it again if you try to
  resume in the mini player.

## 1.0.0

First public release.

- Before a limited app opens, asks how long you want to spend in it (presets from 1 to 60 minutes
  or any value up to 180).
- Warns one minute before the end. When the time is up, returns to the home screen and closes
  the app. The next launch asks again.
- Choose which apps to limit from a searchable list.
- English and Russian interface.
