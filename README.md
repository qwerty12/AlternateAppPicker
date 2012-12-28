AlternateAppPicker: bring back the ICS default app picker in Jelly Bean
=======================================================================

This replaces the rather annoying default application selector we have in Jelly Bean with one that you just tap on the icon once to launch the app, and select a checkbox beforehand if you want it to be the default app.
Since this, thanks to Xposed, works on a global level, it replaces all of the default application selector dialogs, regardless of Intent.

This Xposed module is based on Zaphod-Beeblebrox's work on originally including this feature for the AOKP ROM.

NOTE: The non-Touchwiz compatible version is the only version that I will publically share. I feel that my ways of getting it to work with TouchWiz are unacceptable, but I cannot do any better. So I leave the code here (this is not an example of good coding, far from it) for the sake of completeness.
