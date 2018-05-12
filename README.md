# Mp3tag Actions Pack

## What it is?
[Mp3Tag](https://www.mp3tag.de/en/) is a great software for managing tags in audio files. With it you can quickly and easily delete certain tags (like artist, title, album, year, cover, so on) or modify them. That helps you to organize your music collection and make browsing and searching through it much easily.

[Mp3Tag has a special feature, called an action](https://help.mp3tag.de/options_format.html) which helps you to program mp3tag to do certain acts automatically on one click. For example, via Actions you can uppercase every word, remove double spaces, or move the "feat"-part from title tag to artist tag.

However, Actions sometimes might be complicated to handle and program properly, especially if you have never done Regular Expressions(https://en.wikipedia.org/wiki/Regular_expression) and terms like "boolean", "string", "if-else" from in-build functions(https://help.mp3tag.de/main_scripting.html) make your head dizzy. To add more complication, Mp3Tag has two different syntax you need to master with different escaping rules and logic.

That repository aims to provide a **handful pack of prebuild, easy-to-use, actions**. With that pack you can quickly and easily to handle simple and complicated tasks.

In other word **pack provides various actions you can use out-of-the-box with no programming skills required**.

## What it is NOT?
Mp3tag Actions Pack _is not a magic wand_ that can satisfy any need and can handle any situations.

Do not expect that this pack can solve any tagging problem. Think of this pack/repository as a framework.

If you have special case and Mp3tag Actions Pack cannot help you, then you mush either [learn the syntax by yourself](https://community.mp3tag.de/t/actions-and-batch-operations/967/12) or ask for the help on the [forum](https://community.mp3tag.de/).

## Is it free?
Absolutely.

## How to install?
1. **Download** that repository (see that big green button at the top-right?)
2. **Unpack** archive into one of the following folder:
	* C:\Documents and Settings\ _(username)_ \Application Data\Mp3tag\Data\Actions (_Windows XP_);
	* C:\Users\ _(username)_ \AppData\Roaming\Mp3tag\Data\Actions (_Windows Vista, 7, 8, 8.1, 10_);
	* _(mp3tag location)_ \Data\Actions (_[Portable Mp3Tag Mode](https://www.mp3tag.de/en/portable.html)_);

If you did everything right, then you should see new actions in the menu.

## Required Mp3Tag Version?
* Mp3Tag 2.87 and higher.
Might work on older versions, but why you need to use old versions to begin with?

## What does numbers 10_, 12_, 14_ and so on, in filenames mean?
They exist for sorting purposes.
Without them actions would have been sorted according to the first letter, which is not comfortable to read and follow. Instead, those numbers help to sort actions according to their function and what tag is affected.

## I am tired to select dozen actions over and over, how can I simplify selection?
1. Manually copy-paste actions into one single action (via any text editor), see 00_MAIN.mta as an example
2. Create an action group that contains other actions. See the [screenshot](/help/help002.png)
