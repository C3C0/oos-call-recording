## OOS Call Recording Enabler
Enables call recording feature in OxygenOS for "over-seas" users without changing region to China.

## Background
This is a Magisk alternative to a [build.prop method](https://forum.xda-developers.com/oneplus-3t/how-to/call-recording-oos-4-1-6-rooted-op3t-t3621652) originally introduced by [sparky vicky@XDA](https://forum.xda-developers.com/member.php?u=5196812)
which was based on changing system-wide region to China, which resulted in quite many unpredictable side-effects for "over-seas" region users.
Magisk module modifies only a necessary part of the system without changing current region.

## Requiremenets
- Magisk v13 or later
- Version of OxygenOS should match version of the module for the best experience

## What gets modified
Module replaces stock in-call screen app (/system/priv-app/OPInCallUI).
The one and only modification is that isSupportCallRecorder() method of OPPhoneUtils class was made to always return true.

## Credits
- [spark vicky@XDA](https://forum.xda-developers.com/member.php?u=5196812) for original build.prop method

## Source code
- [GitHub](https://github.com/C3C0/oos-call-recording)

## Change log
- 2017/07/11 -> migrated to template v4 (Magisk v13)
- 2017/06/16 -> initial release compatible with OxygenOS 4.1.6

## Like it?
Consider [buying me a coffee](https://forum.xda-developers.com/donatetome.php?u=5008415)