# Tsumamigui 3 translation

![overview](etc/patched_game_screenshot.jpg)

## What the patch includes (or not), for now
- Translation of the story very beginning
- Font size change
- No UI translation

## How to patch
- Download a release
- Copy the .ain and .ex files from the patch to your install directory over the existing files
(of course you would be wise to back up the original files)

## How to contribute
If you want to contribute, please send me a mail. I will test you to ensure that you can contribute with a minimum level of quality.

## Translation guidelines
It's hard to make exact guidelines about how to translate, but some aspects should be simple enough to be respected precisely as rules (these are somewhat more superficial). These rules are open for discussion. Also, for the hardly definable aspects, there are some general guidelines.

### Rules (mostly for consistency)
- Replace ！？。、 by ! ? . , 
Notice that the former characters are full width.
- Adhere to English punctuation style for the above characters (stick right next to the words)
- Leave other characters unchanged (that goes for 「」（）…)
- Leave the names in Familyname Firstname order
- About honorifics. I have removed them in the few events I have translated. But I think we should keep them. If we make sure to add them in a consistent way, it will be easy to
automatically remove them and make a patch version without honorifics, if that is what people want.

### General guidelines
- Be consistent
- Try to keep the original sentence nuances as much as possible
- Make something that reads like English (try to balance between this and the previous point)
- You can use the tools (like Bing translate) you like but don't trust them too much

### Technical side
- Just change the text between the " quotes.
- Keep the amount of lines as is and balance the text over the lines for multiline messages.
- Leave the ";" in front of all the lines. I will remove them as needed.
- With some rare exceptions, you do not need to change any of the lines starting with ";s[". That goes for the ones that mention the character speaking. (Explanation: most of them are used by the game engine as keys to look up some data structures)
- If you have doubts about the translation you produce, you can leave a (short) comment at the end of the line, starting with ";". That way it will be easier to review.

## Thanks
Thanks to nunuhara for alice-tools. I am using these tools to extract the game text data and patch the game files.
