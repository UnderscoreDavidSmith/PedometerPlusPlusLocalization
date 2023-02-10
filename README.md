# PedometerPlusPlusLocalization

This is a public repository of languages strings for Pedometer++.  It is my hope that I can get better translations by working with *actual* users of the app.

# Workflow

I'm still working out exactly how this will work in practice, but my idea is to put the strings files in this repository and then anyone who is interested in improving their languages translation can create a Pull Request with the improvements in it.  I'll then review and incorporate these into the app.

The main file that you'd be editing is the `Localizable.strings` file in whichever directory cooresponds to the language code you're interested in.

This file takes a form of `"key" = "value";`, where the `key` is the source string, typically an English version of the string, and the `value` is the translated form in the relevant language. 

The baseline translations were done with an automated tool to allow me to start testing, these almost certainly lack context and clarity.  

In order to add a new Language, I have added a [blank](https://github.com/UnderscoreDavidSmith/PedometerPlusPlusLocalization/blob/main/BlankTemplate.strings) file which would need to be filled in to establish the needed translations for that language. 

# Attribution

If you'd like to be credited in the Pedometer++ Help section please indicate this along with your Pull Request. 

Thank you so much for helping me make Pedometer++ as awesome as possible!

This project was inspired by the work of [@steventroughtonsmith](https://github.com/steventroughtonsmith)
 with [Broadcasts](https://github.com/steventroughtonsmith/broadcasts-localization).
