# BA L10N Viewer (BALV)
BA L10N Viewer (*Blue Archive Localization Viewer*, abbr. **BALV**) is a project dedicated to the mobile gamw **Blue Archive**, with an aim of providing an easy access to in-game localization texts.

In the face of the ongoing "bad localizations" happening in the EN community, BALV tries to make in-game texts available to the public, in a way that allows comparison and fact checking. With multiple languages in a row and the built-in Google Translate support, we're making translators and even the general public to take part in the said preocess.

## Project Structure
As mentioned in the [About page](https://ba-l10n.cnfast.top/about), BALV utilizes Python for backend data preprocessing and Vue for frontend functionalities.

Be noted that, BALV does NOT own any in-game assets and texts, and all the data used in the project is all **provided by third-parties**. We therefore mare a disclaimer that, all of the said data is ***FOR REFERENCE ONLY***, and the data is subject to change at any time. **WE DO NOT GRANTEE THE DATA ACCURACY.**

## Features & Data Coverage
Features including:

- Cross-Language Localization Comparision
  - 3 languages for destop/PC, 5 languages for mobile
- Built-In Machine Translation
   - currently only supports Google Translate, but enough most of the time
   - doesn't support name/description of a story yet

Available Data
- Scenario (Normal Story)
- Momotalk
- Voicelines (Nexon In-game Data SchaleDB)
- Profile (WIP)

Be noted that, due to certain situations, BALV is only able to serve a limited port of the CN server data through SchaleDB, specifially thr character profiles and voicelines, and the delay is expected normally.

## Intended Users
**All Blue Archive players apparently.** However, since BALV is partly inspired by [a database for NIKKE](https://nikke.win/), we are, to some extents, aiming at a userbase similar to theirs.

- Average Blue Archive Lore Enjoyer
  - Through lacking much details, BALV provides a clear, text-only version of the in-game stories, making it possible to read through quickly when you're in a hurry or confirming your references to the stories.
- Localizers/Translators
  - <s><i>You know the rules, and so do I</i></s> By having cross-language and built-in Google Translate support, BALV tries to simplify and ease the process of fact-checking - after all, it's time- and energy-cosuming to screenshot and edit posts.
  - An example of such quick fact checking can be found in [this tweet of mine](), through the wording  was a little too harsh in retrospect.

## Future Plan?
**No promises here**, but we do have a to-do list of some notable incluing:

- CSV Export
- UI Rework (half way as of writing this README)

However, due to the very limited availability of the main developer, BALV is expected to remain pretty much time for some time. In fact, currently BALV is going to enter "maintainance mode" (only bugfixes)  once it reaches V1.0, which is comming soon.

All in all, we hope you can find it useful at the end of the day. Have fun reading!
