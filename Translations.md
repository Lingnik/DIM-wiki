#Translating DIM

DIM's translations are stored in [dimApp.i18n.js](https://github.com/DestinyItemManager/DIM/blob/dev/app/scripts/dimApp.i18n.js). You can edit this file directly from GitHub to add or correct translations and submit a PR. We use [Angular translate](https://angular-translate.github.io/docs/#/guide/02_getting-started) for all our translated strings, so if you want to translate something that's currently English-only, take a look at that. Usually it's as simple as replacing some text with `<span translate="KEY"></span>` and then defining KEY in the i18n file. Within code, you need to use the `$translate` service - see `dimStoreService` for an example.

# Sourcing translations

In order to maintain a consistent style it is recommended that all translations are sourced directly from Bungie, either from bungie.net or Destiny. First and foremost, we attempt to use strings directly from the manifest (definitions database) where possible, since those are the official translations. What we need help with are the other strings that don't fall under that bucket.

##From PS/XBOX:
In order to translate a string from Destiny, first launch Destiny in your native language, locate the word that needs translating, hopefully it will be by itself.  

After locating the word that needs translating, change the system language of your PS/Xbox to the desired language. Relaunch Destiny, it will download a language pack. Go back to the exact screen that you located the text from. Your translation should be relatively easy to find.  

##From bungie.net:
Locate the word that needs to be translated from bungie.net in your native language, then scroll to the bottom of the page and change the language to the desired language. Some words are able to be copy and pasted directly from the web page, others need to be inspected, (right-click inspect), then on the element you inspected, copy the data from the developers console, remove the div data and voila you have your text for the desired language.  

##TIPS
Do not try to use this method to translate a word that is located in paragraph form, it will be tedious. Find your desired word in a title such as `POSTMASTER` from the actual Postmaster screen. This will ensure you get the word exactly as Bungie has been displaying it to Destiny users.
